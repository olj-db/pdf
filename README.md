# OLJ-DB PDF Host

This repository hosts deterministic static URLs for rehosted open-access law
journal PDFs.

The public site is deployed by GitHub Actions from the `site/` folder. The
workflow uses GitHub's official Pages deployment actions and the repository's
built-in `GITHUB_TOKEN`.

Canonical article-number routes look like:

- `/alta-l-rev/vol/63/iss/1/art/13/`
- `/alta-l-rev/vol/63/iss/1/art/13/view.pdf`

First-page and DOI routes are aliases that point to the canonical article route:

- `/alta-l-rev/vol/63/iss/1/firstpage/1/`
- `/alta-l-rev/vol/63/iss/1/firstpage/1/art/13/`
- `/doi/10.29173/alr2850/`

When a bare first-page route matches multiple articles, it shows an ambiguity
page with the matching issue TOC entries.
