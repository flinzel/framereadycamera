# Image Path Fix

All image, favicon, stylesheet and Open Graph asset references in HTML were changed from relative `assets/...` paths to absolute GitHub Pages URLs under:

`https://flinzel.github.io/framereadycamera/assets/...`

A `.nojekyll` file was added so GitHub Pages serves all static assets without Jekyll processing.

If images still do not appear after deployment, confirm that the `assets/` folder is present at the repository root and clear the browser cache or wait for GitHub Pages deployment cache to refresh.
