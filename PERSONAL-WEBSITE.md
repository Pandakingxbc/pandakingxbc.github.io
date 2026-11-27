# Zhi Yang · Personal Website

Live website: https://pandakingxbc.github.io/

This repository contains my personal academic website, built on Jekyll / al-folio with a custom homepage.

## Homepage files

- `_layouts/personal.html`: About, Publications, Experience, and Blog content.
- `_pages/about.md`: homepage route and layout selection.
- `assets/css/personal-home.css`: responsive homepage styles.
- `assets/img/zhi-yang-profile.png`: directly cropped original portrait.
- `assets/img/infonav-navigation.png`: InfoNav navigation illustration.

## Update content

Edit `_layouts/personal.html` to update the biography, experience, and publication links. The Blog section currently contains a placeholder. When adding an essay, create a post in `_posts/` using the existing Jekyll post format, then add its title, date, summary, and URL to the homepage Blog section.

## Preview and deploy

Follow the repository's INSTALL.md for the full Jekyll environment. Run `bundle exec jekyll serve` and visit http://localhost:4000/ to preview. Changes pushed to `main` trigger `.github/workflows/deploy.yml`, which builds the site and uploads `_site` as a Pages artifact and publishes it through the official GitHub Pages deployment action.

## Featured projects

- Octop: https://github.com/TencentCloud/Octop
- InfoNav code: https://github.com/Pandakingxbc/InfoNav
- InfoNav paper: https://openreview.net/forum?id=lzhhlAlmjK

The site uses the original al-folio project and retains its existing license and attribution files.
