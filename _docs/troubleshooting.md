---
layout: doc
title: Troubleshooting
nav_order: 3
summary: Fix common problems that appear when developing or deploying the site.
---
## Build Issues

**Missing Gems**
: Run `bundle install` to install the GitHub Pages gem bundle.

**Port Already In Use**
: Stop the other process or launch the server on a new port with `bundle exec jekyll serve --port 4001`.

## Content Not Updating

- Make sure files include valid [YAML front matter](https://jekyllrb.com/docs/front-matter/).
- Check `_config.yml` for caching; run `bundle exec jekyll serve --livereload` to refresh when editing locally.

## Deployment Delays

GitHub Pages can take a few minutes to rebuild. Confirm the workflow status in your repository's **Actions** tab when using GitHub Pages with GitHub Actions.
