# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

Academic personal website for Paul Millett (Economics PhD Candidate), built with Jekyll using the Minimal Mistakes theme (forked from AcademicPages template). Deployed as a GitHub Pages site at https://pmmillett.github.io/.

## Development Commands

```bash
# Install dependencies
bundle install

# Serve locally with live reload (localhost:4000)
bundle exec jekyll liveserve

# If dependency issues arise, clean first
bundle clean && bundle install

# Minify JavaScript assets
npm run build:js

# Watch JS for changes and auto-rebuild
npm run watch:js
```

Development uses `_config.dev.yml` to override production settings (expanded CSS, no HTML compression, no analytics).

## Architecture

### Content System

Content lives in Jekyll collections and pages, all using Markdown with YAML front matter:

- **`_pages/`** - Static pages (about/home at `/`, CV, research, job market paper)
- **`_research/`** - Research papers (rendered at `/publications/:path/`)
- **`_talks/`** - Presentations (uses special `talk` layout with venue/location)
- **`_teaching/`** - Teaching experience
- **`_portfolio/`** - Portfolio items
- **`_posts/`** - Blog posts (date-prefixed filenames: `YYYY-MM-DD-title.md`)

### Configuration

- **`_config.yml`** - Main site config: author info, collections, plugins, defaults
- **`_data/navigation.yml`** - Top navigation menu (currently: CV, Job Market Paper, Research)
- **`_data/ui-text.yml`** - UI strings with multi-language support

### Theme & Templates

Based on Minimal Mistakes theme with academic customizations:

- **`_layouts/`** - Page templates (`default.html` > `single.html` for most pages, `talk.html` for talks, `archive.html` for list pages)
- **`_includes/`** - Reusable partials (author-profile sidebar, masthead nav, SEO, social sharing)
- **`_sass/`** - SCSS styles (variables, components, vendor libs including Susy grid and Font Awesome)
- **`assets/js/`** - JavaScript (jQuery, greedy-navigation, magnific-popup; bundled into `main.min.js`)

### Static Assets

- **`images/`** - Site images (author avatar, icons)
- **`files/`** - Downloadable documents (PDFs served at `/files/filename.pdf`)

### Content Generation Tools

**`markdown_generator/`** contains Python scripts and Jupyter notebooks to bulk-generate Markdown files from TSV/BibTeX sources for publications and talks.

## Front Matter Conventions

```yaml
---
title: "Page Title"
permalink: /url-path/
author_profile: true    # show sidebar with author info
layout: single          # or archive, talk, splash
excerpt: "Short description"
---
```

Collection items use date-prefixed filenames (`YYYY-MM-DD-title.md`) for ordering. Talks include additional `venue` and `location` fields.

## Key Details

- GitHub Pages gem manages Jekyll version and plugin compatibility
- Plugins: jekyll-paginate, jekyll-sitemap, jekyll-gist, jekyll-feed, jekyll-redirect-from
- Archives use Liquid templates (not jekyll-archives plugin) for GitHub Pages compatibility
- HTML compression applied in production only (via `compress.html` layout)
- The `repository` field in `_config.yml` still references the upstream academicpages repo
