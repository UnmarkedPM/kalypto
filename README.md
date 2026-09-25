# Kalypto

On-premise appliance for reversible pseudonymisation.

This repository holds public-facing publications about the product and the source for a
documentation site, along the lines of [UnmarkedPM/koord](https://github.com/UnmarkedPM/koord).

## Structure

- `publications/<topic>/` — one directory per publication. Each holds `it.html`, `it.pdf`,
  `en.html`, `en.pdf`: the Italian and English renderings of the same document, as HTML and PDF.
- `publications/index.html` — entry point of the published site, listing every publication below.
- `.github/workflows/pages.yml` — deploys `publications/` to GitHub Pages on push to `main`.

## Publications

| Publication | Italiano | English |
|---|---|---|
| How the system works (v. 1.10) | [HTML](https://unmarkedpm.github.io/kalypto/how-it-works/it.html) &middot; [PDF](https://unmarkedpm.github.io/kalypto/how-it-works/it.pdf) | [HTML](https://unmarkedpm.github.io/kalypto/how-it-works/en.html) &middot; [PDF](https://unmarkedpm.github.io/kalypto/how-it-works/en.pdf) |

The links above resolve once the repository is public and GitHub Pages is enabled
(Settings &rarr; Pages &rarr; Source = "GitHub Actions"); both require an explicit decision, not
yet taken as of 2026-09-25 — see the repository's private status.

Status: scaffolding. License and long-term structure are not yet defined.
