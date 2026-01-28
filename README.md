# skg_blog

Personal website for Sijo Kuruvilla George.

## Live Site

**URL**: https://www.sijokuruvilla.in/

## Tech Stack

- **Static Site Generator**: Jekyll
- **Theme**: Minima
- **Hosting**: GitHub Pages
- **Branch**: `gh-pages`

## Repository

- **GitHub**: https://github.com/sijokuruvilla/skg_blog
- **Account**: sijokuruvilla

## Project Structure

```
skg_blog/
├── _config.yml          # Jekyll configuration
├── _layouts/            # HTML templates
├── _posts/              # Blog posts (date-prefixed)
├── articles/            # Article content (archived)
├── assets/              # Static assets (CSS, images)
├── pages/               # Static pages
├── index.md             # Homepage
├── CNAME                # Custom domain config
├── Gemfile              # Ruby dependencies
└── 404.html             # Custom 404 page
```

## Related Sites

| Site | Repository | Domain |
|------|------------|--------|
| Main (this) | sijokuruvilla/skg_blog | www.sijokuruvilla.in |
| Notes | skgnotes/skg-notes | notes.sijokuruvilla.in |

## Local Development

```bash
# Install dependencies
bundle install

# Run local server
bundle exec jekyll serve

# Site available at http://localhost:4000
```

## Deployment

Changes pushed to the `gh-pages` branch are automatically deployed via GitHub Pages.

```bash
git add .
git commit -m "Your message"
git push origin gh-pages
```

## DNS Configuration

The custom domain `www.sijokuruvilla.in` is configured via:
- CNAME file in repository root
- DNS CNAME record pointing to `sijokuruvilla.github.io`

## Last Updated

2026-01-28
