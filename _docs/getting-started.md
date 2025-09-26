---
layout: doc
title: Getting Started
nav_order: 1
summary: Install prerequisites, clone the repo, and build the project locally.
---
## Requirements

- Ruby 3.1 or newer
- Bundler 2.x
- GitHub Pages compatible gems (`bundle install` handles this)

## Installation Steps

1. Clone the repository: `git clone https://github.com/ancientyolklore/ancientyolklore.github.io`
2. Install dependencies: `bundle install`
3. Start the local server: `bundle exec jekyll serve`

Once the server is running, open `http://localhost:4000` in your browser to see the site.

## Deployment

Push changes to the `main` branch. GitHub Pages will rebuild and publish the site automatically.
