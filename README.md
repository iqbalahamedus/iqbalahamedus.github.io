# Sheikh Iqbal Ahamed public website

This directory contains the initial static front page for the GitHub Pages
hosting milestone. `index.html` includes its own CSS and has no JavaScript,
external fonts, analytics, package dependencies or build step. `.nojekyll`
allows GitHub Pages to serve the files directly.

The page contains public professional information, links to the Ubicomp Lab and
the four venture websites, and a public academic email link. It clearly states
that the full academic portfolio is being prepared. The page is temporarily
marked `noindex, follow`; remove the `noindex` directive when the full portfolio
is ready for search indexing.

The private source, owner login, editing database and publishing backend will
be configured separately. This public directory must never contain source CVs,
private contact details, credentials, receipt files, database exports or raw
research inventory. No backend, blog editor or CV-download functionality is
implemented by this initial page.

The public repository is `iqbalahamedus/iqbalahamedus.github.io`, serving
`https://iqbalahamedus.github.io/`. The GitHub Actions workflow in
`.github/workflows/pages.yml` publishes only `index.html` and `.nojekyll`.
GitHub Pages settings and any future custom-domain DNS records are managed
separately. No custom domain is embedded in this bootstrap.
