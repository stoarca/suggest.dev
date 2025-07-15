# Moment Homepages

This repository contains marketing pages and homepages for Moment, designed for quick updates without CI/code review overhead.

## Current Sites

### suggest.dev
- **Purpose**: Ultra-low-friction feedback widget for websites
- **Features**: Quadruple-click anywhere to trigger feedback form with screen recording
- **Homepage**: Full-bleed centered hero section with CTA buttons
- **Navigation**: Docs, Pricing, Log in, Sign up

## Project Structure

```
/
├── index.html          # Main homepage
├── pages/              # Additional marketing pages
├── styles.css          # Single stylesheet for all pages
├── assets/             # Static assets (images, js)
│   ├── js/            # JavaScript files
│   └── images/        # Images and media
├── CNAME              # GitHub Pages custom domain (if needed)
└── .nojekyll          # Prevents Jekyll processing
```

## Development Guidelines

### HTML Structure
- Use semantic HTML5 elements
- Keep pages lightweight and fast-loading
- Ensure mobile responsiveness
- Include proper meta tags for SEO
- Link to styles.css in all HTML files: `<link rel="stylesheet" href="/styles.css">`

### CSS
- All styles in single `styles.css` file
- No inline styles
- Mobile-first approach
- Keep styles minimal and maintainable
- Use CSS custom properties for consistent theming

### JavaScript
- Minimal JavaScript for interactions only
- No heavy frameworks - vanilla JS preferred
- Progressive enhancement approach

### File Naming
- Use lowercase with hyphens: `about-us.html`, `contact-form.html`
- Descriptive names for all assets

## GitHub Pages Setup

1. Repository Settings > Pages
2. Source: Deploy from branch
3. Branch: main
4. Folder: / (root)

## Quick Deploy Process

1. Make changes directly in main branch
2. Commit and push
3. Changes are live within minutes at: https://[username].github.io/moment-homepages/

## Common Tasks

### Adding a New Page
1. Create HTML file in root or `/pages/` directory
2. Link to styles.css in the `<head>`
3. Link from index.html or navigation
4. Test locally before pushing

### Updating Content
- Edit HTML files directly
- No build process required
- Changes are immediate after push

### Adding Assets
- Place in appropriate `/assets/` subdirectory
- Use relative paths in HTML
- Optimize images before upload