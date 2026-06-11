# freeaichat.bot Static Deploy

This folder contains the isolated static deployment artifact for GitHub Pages.

- Source workspace files are not deployed directly.
- Built assets live in `assets/`.
- `.nojekyll` is included so GitHub Pages serves all generated assets.
- `.github/workflows/deploy.yml` publishes the repository root to GitHub Pages.

The app is a static client deployment of the current Freebot Creator Studio build.
