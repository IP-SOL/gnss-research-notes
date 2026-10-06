# GNSS Notes

Technical notes on GNSS, PNT, SDR receivers, simulation, timing and ionospheric applications.

This repository contains the Quarto source for **GNSS Notes**.

## Local editing

Install Quarto, clone this repository, then use:

```sh
quarto preview
```

For a complete local build:

```sh
quarto render
```

Rendered output is written to `_site/` and is not committed.

## Publishing

The repository includes a GitHub Actions workflow that renders the Quarto project and deploys `_site/` to GitHub Pages whenever `main` is updated.

GitHub Pages must be configured with **Settings → Pages → Build and deployment → Source: GitHub Actions**.

No Quarto Pub account is required.

For the initial free setup, the site will use:

`https://ip-sol.github.io/gnss-research-notes/`

A custom domain such as `gnss-notes.com` can be added later.

## Authorship

Authorship is selected article by article. The site does not impose a default corporate byline.

## New article

Copy `_templates/article.qmd` into a new directory under `posts/`, for example:

```text
posts/2026-10-xx-topic/index.qmd
```

Keep `draft: true` until the article is ready for publication.
