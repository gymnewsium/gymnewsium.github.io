# README for development

## Vercel settings

- Build command: `bundle exec jekyll build --future --drafts`
- Development command: `bundle exec jekyll serve --watch --port $PORT --future --drafts`
- ENV: (production): `JEKYLL_ENV=production-noindex`
- ENV: (preview, deployment): `JEKYLL_ENV=development`

(these settings only apply if Vercel is only used for preview deployments)
