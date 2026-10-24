# KNIGHT — Portfolio

A responsive, static portfolio for Kris Tan (KNIGHT), featuring app showcases, creator bio, support QR codes, and light/dark themes.

## Preview locally

From the repository root, run any static file server, for example:

```bash
python3 -m http.server 4173
```

Then open `http://localhost:4173`.

## Deploy with GitHub Pages

This repository includes a GitHub Actions workflow at `.github/workflows/pages.yml`.

1. Push this site to the repository's `main` branch.
2. In GitHub, open **Settings → Pages**.
3. Set **Build and deployment → Source** to **GitHub Actions**.
4. The workflow publishes the site on every push to `main`; the deployed URL appears in the Actions run and Pages settings.

The site is static and works from a project subpath (for example, `https://username.github.io/repository/`): asset links are relative, so no repo-specific base URL is needed.

## Structure

- `index.html` — site, styling, interactions, and project content
- `public/images/` — logo, creator portrait, and support QR codes
- `public/screenshots/` — locally bundled project screenshots
- `.github/workflows/pages.yml` — GitHub Pages deployment

Project descriptions and features are summarized from the associated public GitHub READMEs. App screenshots are bundled locally as animated WebP showcases, including Tuhkar’s full-screen Android captures.
