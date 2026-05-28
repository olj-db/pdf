# OLJ-DB PDF Host

This repository hosts deterministic static URLs for rehosted open-access law
journal PDFs.

The public site is deployed by GitHub Actions from the `site/` folder. The
workflow uses GitHub's official Pages deployment actions and the repository's
built-in `GITHUB_TOKEN`.

Current proof-of-concept routes include Alberta Law Review volume 62, issue 1:

- `/alta-l-rev/vol/62/iss/1/firstpage/1/`
- `/doi/10.29173/alr2794/`

