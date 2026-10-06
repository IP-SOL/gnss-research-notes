# GNSS Research Notes

Technical notes on GNSS, PNT, SDR receivers, simulation, timing and ionospheric applications.

This repository contains the Quarto source for **GNSS Research Notes**, an IP-Solutions technical publication.

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

The initial GitHub Pages address can be used during setup. A custom domain such as `research.ip-solutions.co.jp` can be attached later.

## Authorship

The default post byline is **IP-Solutions Research Team**. Individual posts may override it with a named author or appropriate joint authorship.

AI systems are not presented as human authors. Material AI assistance may be disclosed in an editorial note when useful.

## New article

Copy `_templates/article.qmd` into a new directory under `posts/`, for example:

```text
posts/2026-10-xx-topic/index.qmd
```

Keep `draft: true` until the article is ready for publication.
