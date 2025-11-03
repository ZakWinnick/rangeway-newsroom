# Rangeway Energy Newsroom (Beta)

Beta version of the Rangeway Energy newsroom site, featuring the new Rangeway Beta design system. Built with Jekyll and hosted on GitHub Pages.

## About

This is a **beta version** of the Rangeway Energy newsroom that uses the dark, modern design from beta.rangeway.energy. This site serves as the media center for Rangeway Energy, featuring:
- Press releases
- Case studies
- Company blog
- Media kit and brand assets
- RSS feeds for all content types

## Setup

This site is built with Jekyll and designed to be hosted on GitHub Pages.

### Local Development

1. Install Jekyll and dependencies:
```bash
gem install jekyll bundler
bundle install
```

2. Run the site locally:
```bash
bundle exec jekyll serve
```

3. View at `http://localhost:4000`

### Adding Content

**Press Release:**
Create a new file in `_press_releases/` with the format `YYYY-MM-DD-title.md`:

```markdown
---
layout: press-release
title: "Your Press Release Title"
date: 2024-11-02
description: "Brief description for SEO"
---

Your press release content here...
```

**Blog Post:**
Create a new file in `_posts/` with the format `YYYY-MM-DD-title.md`:

```markdown
---
layout: post
title: "Your Blog Post Title"
date: 2024-11-02
author: Author Name
category: blog
---

Your blog content here...
```

**Case Study:**
Create a new file in `_case_studies/` with any filename:

```markdown
---
layout: case-study
title: "Case Study Title"
subtitle: "Optional subtitle"
---

Your case study content here...
```

## Deployment

This site is configured for GitHub Pages. Simply push to the main branch and GitHub will automatically build and deploy.

### Custom Domain Setup

1. In repository settings, add `newsroom-beta.rangeway.energy` as custom domain
2. Add CNAME record in DNS pointing to your GitHub Pages URL
3. Enable HTTPS in repository settings

## Design System

This beta version uses the Rangeway Beta design system with:
- Dark theme (background: #1a1a1a, #2a2a2a)
- Poppins font family
- Coral accent color (#F09060)
- Modern card-based layouts
- Smooth transitions and hover effects
- Responsive mobile-first design

## Structure

```
rangeway-newsroom/
├── _config.yml           # Jekyll configuration
├── _layouts/             # Page templates
├── _includes/            # Reusable components (header, footer)
├── _press_releases/      # Press release collection
├── _case_studies/        # Case study collection
├── _posts/               # Blog posts
├── assets/              # CSS, JS, images
├── index.html           # Homepage
├── press.html           # Press releases archive
├── case-studies.html    # Case studies archive
├── blog.html            # Blog archive
└── media-kit.html       # Media kit page
```

## Brand Consistency

This site uses the same design system as the main Rangeway Energy site (rangeway.energy), ensuring brand consistency across all properties.

## Contact

For questions about this site, contact: media@rangeway.energy
