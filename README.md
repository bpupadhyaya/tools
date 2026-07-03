# Tools

The website for **local-first AI tools by Bhim Upadhyaya** — a hub that lists each tool and links
to its signed downloads. Live at **https://bpupadhyaya.github.io/tools/**.

- `index.html` — the hub (all tools).
- `maker.html` — Maker product + download page.
- `styles.css` — shared styling.
- Deployed by `.github/workflows/pages.yml` (GitHub Actions).

## Enable the site (one-time)
Repo **Settings → Pages → Build and deployment → Source = "GitHub Actions"**. Every push to `main`
then deploys automatically.

## Add a tool
Add a card in `index.html` (copy the Maker card) and, optionally, a `<tool>.html` product page.
