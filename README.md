# xoloUno Blog

A minimal Jekyll blog hosted on GitHub Pages.

## Writing Posts

1. Create a new file in the `_posts` folder
2. Name it: `YYYY-MM-DD-your-title.md` (e.g., `2025-01-15-hello-world.md`)
3. Add this header at the top:

```yaml
---
layout: post
title: "Your Post Title"
date: 2025-01-15
---
```

4. Write your content in Markdown below the header
5. Commit and push—your site updates automatically in about a minute

## File Structure

```
├── _posts/              # Your blog posts go here
├── _layouts/            # Page templates
├── assets/css/          # Stylesheet
├── about.md             # About page
├── archive.md           # Archive page
├── index.html           # Homepage
├── feed.xml             # RSS feed
└── _config.yml          # Site settings
```

## Customization

- **Site title/author**: Edit `_config.yml`
- **About page**: Edit `about.md`
- **Styling**: Edit `assets/css/style.css`

## Posting from iPhone

Use Working Copy (Git client) to clone your repo, create/edit Markdown files, and push changes.
