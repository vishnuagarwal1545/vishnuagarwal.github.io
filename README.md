# My Portfolio Website

This is my personal portfolio website built with Jekyll and hosted on GitHub Pages. It showcases my projects, blog posts, and professional information.

## Features

- **About Me**: Personal introduction and background
- **Projects**: Showcase of my GitHub projects and other work
- **Blog**: Personal blog for sharing thoughts and insights
- **Resume/CV**: Professional resume with downloadable PDF option

## How to Update This Site

### Basic Configuration

1. Edit `_config.yml` to update site-wide settings:
   - Update your name, contact information, and site description
   - Customize site appearance and features

2. Update your profile picture:
   - Replace `assets/img/prof_pic.jpg` with your own photo (keep the same filename)

### Content Pages

1. **About Me Page**:
   - Edit `_pages/about.md` to update your personal information and bio

2. **Projects**:
   - Edit existing project in `_projects/1_project.md` or create new project files
   - Link to your GitHub repositories in the project files
   - Update `_data/repositories.yml` to display your GitHub profile and repositories

3. **Blog**:
   - Add blog posts as markdown files in the `_posts` directory
   - Use the format `YYYY-MM-DD-title.md` for filenames

4. **Resume/CV**:
   - Update your resume information
   - Add your PDF resume to `assets/pdf/resume.pdf`

### GitHub Pages Deployment

This site is automatically deployed to GitHub Pages when you push changes to the main branch.

## Local Development

To run this site locally:

1. Install Ruby and Jekyll (see [Jekyll Installation Guide](https://jekyllrb.com/docs/installation/))
2. Clone this repository
3. Run `bundle install` to install dependencies
4. Run `bundle exec jekyll serve` to start the local server
5. Visit `http://localhost:4000` in your browser

## Credits

This site is built with [Jekyll](https://jekyllrb.com/) using the [al-folio](https://github.com/alshedivat/al-folio) theme.
