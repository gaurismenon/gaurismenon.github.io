# Personal Portfolio Website Template

A simple Jekyll-based portfolio website template to help you create your own personal website.

## Features

- Home page with introduction
- About page
- Projects showcase
- Blog section
- Contact page
- Clean, minimal design ready for your custom styling
- SEO-friendly with meta tags
- RSS feed for blog posts
- Responsive structure

## Prerequisites

- Ruby (version 2.7 or higher)
- Bundler
- Git

## Quick Start

1. **Clone or copy this template to your local machine**

2. **Install dependencies**
   ```bash
   bundle install
   ```

3. **Customize your site**
   - Edit `_config.yml` with your personal information
   - Update pages (index.html, about.html, contact.html)
   - Add your projects to `_projects/` directory
   - Add blog posts to `_posts/` directory
   - Customize styling in `assets/css/main.css`

4. **Run locally**
   ```bash
   bundle exec jekyll serve
   ```
   Visit `http://localhost:4000` in your browser

5. **Deploy**
   - Push to GitHub and enable GitHub Pages in repository settings
   - Or deploy to any static hosting service

## File Structure

```
.
├── _config.yml              # Site configuration
├── _includes/               # Reusable HTML components
│   ├── header.html
│   ├── footer.html
│   └── structured-data.html
├── _layouts/                # Page layouts
│   ├── default.html
│   ├── page.html
│   └── post.html
├── _posts/                  # Blog posts (YYYY-MM-DD-title.md)
├── _projects/              # Project pages
├── assets/
│   ├── css/                # Stylesheets
│   ├── images/             # Images
│   └── docs/               # Documents (e.g., resume)
├── index.html              # Home page
├── about.html              # About page
├── projects.html           # Projects listing
├── blog.html               # Blog listing
├── contact.html            # Contact page
└── Gemfile                 # Ruby dependencies
```

## Customization

### Adding a Blog Post

Create a new file in `_posts/` with the format `YYYY-MM-DD-title.md`:

```markdown
---
layout: post
title: "Your Post Title"
date: YYYY-MM-DD
---

Your content here...
```

### Adding a Project

Create a new file in `_projects/` with the format `project-name.md`:

```markdown
---
layout: page
title: "Project Name"
excerpt: "Short description"
---

Your project details here...
```

### Styling

All CSS is in `assets/css/main.css`. The default styling is minimal - customize it to match your personal brand!

## License

This template is free to use for personal and commercial projects. Attribution is appreciated but not required.

## Support

For issues or questions, please open an issue on GitHub.
