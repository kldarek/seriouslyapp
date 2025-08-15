# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is the "Seriously" landing page - a static marketing website for an AI-powered nutrition coaching mobile app. The site is built with pure HTML/CSS and hosted on GitHub Pages using Jekyll.

## Tech Stack

- **Static Site**: Pure HTML/CSS/JavaScript (no framework)
- **Hosting**: GitHub Pages with Jekyll
- **Styling**: Custom CSS with CSS Grid, Flexbox, and CSS custom properties
- **Fonts**: Google Fonts (Inter)

## Project Structure

```
/
├── index.html          # Main landing page
├── styles.css          # All styling (mobile-first responsive design)
├── _config.yml         # Jekyll configuration
├── privacy.md          # Privacy policy
├── terms.md           # Terms of service
└── assets/images/      # Coach personality images and icons
```

## Development Workflow

**Important**: Always develop on a new branch and create a PR with the new functionality or bug fixes.

```bash
# Create a new branch for your changes
git checkout -b feature/your-feature-name

# After making changes, push to the branch
git push -u origin feature/your-feature-name

# Then create a PR to merge into main
```

## Deployment

The site automatically deploys to GitHub Pages when changes are pushed to the main branch. Test changes directly on GitHub Pages after merging PRs.

## Important Notes

- **No JavaScript functionality**: Currently pure HTML/CSS
- **Jekyll processes Markdown**: `.md` files are converted to HTML
- **Images in assets/images/**: Coach personality photos and app icons
- **Legal pages**: Privacy policy and terms of service must be kept updated