---
layout: doc
title: Project Structure
nav_order: 2
summary: Understand the directory layout and what each piece of the site does.
---
## Directories

- `_layouts/` holds the HTML layouts that wrap pages, posts, and docs.
- `_includes/` stores snippets like the shared site header.
- `_posts/` contains dated blog posts. Jekyll builds the blog from this folder.
- `_docs/` is a custom collection that powers the documentation section.
- `docs/` provides a landing page for documentation.
- `assets/css/` keeps the stylesheet for the entire site.

## Configuration

Site-wide settings live in `_config.yml`. Update navigation titles, links, or plugins there. Defaults ensure posts use the `post` layout and docs use the `doc` layout automatically.

## Adding Content

- Create new posts by adding Markdown files to `_posts/` with the `YYYY-MM-DD-name.md` pattern.
- Add new documentation topics in `_docs/` with the desired `nav_order` to control sidebar ordering.
- Standalone pages (contact, team, etc.) can live at the repository root or in their own folders.
