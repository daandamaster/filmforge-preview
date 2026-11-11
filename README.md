# FilmForge preview

Public testlink of the FilmForge PWA. Stripe runs in mock mode. This repository has no secrets or API keys.

**Preview:** https://daandamaster.github.io/filmforge-preview/

The `gh-pages` branch is the GitHub Pages source. HTML, CSS, JavaScript, the manifest and the service worker are already live. The complete site, including the demo video, images and fonts, is stored as a checksummed payload in `payload/` on that branch.

To publish those files onto the site, allow GitHub Actions for this repository (Settings → Actions → General → Allow all actions and reusable workflows), then run the workflow **Deploy preview to GitHub Pages**.
