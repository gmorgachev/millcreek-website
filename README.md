# MillCreek R&D

A minimal, single-page website for MillCreek Research & Development, focused on verifiable AI inference and training in distributed and untrusted environments.

Based on `v/01.html` (v1) from `millcreek-site-drafts-r4.zip`. Preserves the original engraved mill illustration, white background, and serif typography, with clearer introductory copy.

## Local preview

Run from the repository root:

```sh
python3 -m http.server 8000
```

Open http://localhost:8000. No build step, JavaScript, package manager, or external font service is required.

## Files

- `index.html` — page content and inline SVG mill illustration.
- `styles.css` — responsive layout and typography.
- `fonts/` — supplied Source Serif 4 and IBM Plex Mono fonts.
- `logo/favicon.svg` — supplied favicon.
- `.github/workflows/pages.yml` — deploys the site on pushes to `main`.

## GitHub Pages

In the repository's **Settings → Pages**, select **GitHub Actions** as the source. Push to `main` or run the **Deploy GitHub Pages** workflow manually.

The workflow publishes only the page, stylesheet, fonts, favicon, and `.nojekyll` file. Relative asset URLs support both a repository subpath and a custom domain.

Edit the text in `index.html` and the appearance in `styles.css`; pushing changes to `main` updates the site automatically.
