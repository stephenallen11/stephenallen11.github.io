# stephenallen11.github.io

Personal site, built by GitHub Pages with Jekyll. Pushing to `main` publishes.

## Write a post

Add a file to `_posts/` named `YYYY-MM-DD-short-title.md`:

```markdown
---
title: The title of the post
tags: [energy]
---

Body in Markdown. Put images in `assets/` and link them as `/assets/name.png`.
```

The file name sets the date and the address (`/short-title/`). To keep a draft
out of the published site, add `published: false` to the front matter.

## Add a project

Add an entry to `_data/projects.yml` (the file has an example).

## Change the look or the text

- Home page intro: `index.html`
- About page: `about.md`
- Colours, fonts and spacing: `assets/style.css` (colours are variables at the top)
- Header and footer: `_layouts/default.html`
