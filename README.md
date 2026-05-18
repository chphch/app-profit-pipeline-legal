# app-profit-pipeline-legal

Hosting for privacy policies and legal documents of apps under app-profit-pipeline (worker-calc, cat-calorie, etc.).

Served via GitHub Pages: https://chphch.github.io/app-profit-pipeline-legal/

## Adding a new app

1. Create directory `<app-slug>/`
2. Add `privacy-policy.md` (with Jekyll frontmatter `--- title: ... layout: default ---`)
3. Link from `index.md`
4. Commit + push; GitHub Pages auto-rebuilds within ~1 minute
