# Jamakkol Prasanam — Alternate Site

This is a standalone static website. It requires no build step, package manager, or server code.

## Publish with GitHub Pages

1. Create a GitHub repository for this site.
2. Upload the contents of this folder to the repository root: `index.html`, `assets/`, and `.nojekyll`.
3. In the repository, open **Settings → Pages** and select **Deploy from a branch**.
4. Select the `main` branch and `/ (root)`, then save.

The site uses browser geolocation and makes HTTPS requests to Open-Meteo for sunrise and sunset data. GitHub Pages serves it over HTTPS, which supports browser location permission.
