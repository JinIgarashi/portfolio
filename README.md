# jin-igarashi.me

Portfolio website of Jin IGARASHI, built with [Hugo](https://gohugo.io) and the [HugoBlox Academic CV](https://github.com/HugoBlox/hugo-theme-academic-cv) template (English and Japanese).

## Structure

- `config/_default/` – Hugo and HugoBlox settings (`params.yaml`), menus and languages
- `data/authors/me.yaml` – profile, experience, skills and certificates (Japanese overrides in `data/ja/authors/me.yaml`)
- `content/{en,ja}/_index.md` – home page sections
- `content/{en,ja}/{portfolio,projects,events,publications}/` – pages
- `static/files/` – CV and certificate PDFs

## Development

Requirements: Hugo extended (see `hugoblox.yaml` for the version), Go, Node.js and pnpm.

```bash
pnpm install
hugo server
```

Production build (including the Pagefind search index):

```bash
pnpm run build
```

## Deployment

Pushing to `master` builds the site and deploys it to GitHub Pages via `.github/workflows/deploy.yml`.
The repository's Pages source must be set to **GitHub Actions**.
