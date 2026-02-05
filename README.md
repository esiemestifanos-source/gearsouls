# GearSouls — Starter Website

This is a minimal static website template (HTML/CSS/JS) intended as a starting point for GearSouls.

## Files
- `index.html` — Main page
- `css/styles.css` — Styles
- `js/main.js` — Small JS helpers
- `README.md` — This file

## Preview locally
1. Clone the repo (or copy files into a folder).
2. Start a simple static server. Examples:

- Using Python 3:
  - `python -m http.server 8000`
  - Open http://localhost:8000

- Using Node (http-server):
  - `npx http-server -c-1`
  - Open the displayed URL.

## Publish with GitHub Pages
Option A — publish the repository root:
1. Push these files to your repository (e.g. `main` branch).
2. In GitHub, go to Settings → Pages → Build and deployment.
3. Choose “Deploy from a branch”, select `main` and `/ (root)`, save.
4. After a minute, your site will be live at `https://<your-user>.github.io/<repo>` (or your custom domain).

Option B — publish from a `gh-pages` branch:
1. Create a branch `gh-pages` with the site files at root.
2. Push branch and configure Pages to serve from `gh-pages`.

## Next steps / customization ideas
- Replace copy, logo, and contact info.
- Add additional pages (blog, docs) or a build system.
- Convert to a React/Next.js or static site generator (Jekyll/Hugo) if you need dynamic content.
