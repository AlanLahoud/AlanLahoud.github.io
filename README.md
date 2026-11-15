# Alan Lahoud Quarto Website

This repository contains Alan Lahoud's personal Quarto website: a profile page and an online CV.

The rendered routes are:

- `/home/` for the personal homepage
- `/cv/` for the online CV (PDF download in `assets/Alan-Lahoud-CV.pdf`)

The `posts/` folder holds draft blog posts. They are not rendered for now: to publish them,
add `posts/**` to `project.render` in `_quarto.yml` and add a Posts link to the navbar.

## Local preview

```bash
quarto preview
```

## Render

```bash
quarto render
```

The rendered site is written to `docs/`, which is the GitHub Pages source.
