# IPAKLICK

IPAKLICK is a browser-based IPA type-and-click tool for inserting phonetic symbols into electronic documents.

**Live site:** https://hartmut-se.github.io/ipaklick/

## Files

- `index.html` — the GitHub Pages entry page (same content as `readme.html`)
- `readme.html` — instructions and background information
- `ipa-text-input.html` — the IPA symbol keyboard and text input interface
- `.nojekyll` — tells GitHub Pages to publish files as-is without Jekyll processing

## Publish on GitHub Pages

1. Create a repository named **`ipaklick`** under the GitHub account **`hartmut-se`**.
2. Upload the files in this folder to the repository root on the `main` branch.
3. In the repository, open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**, select branch **`main`** and folder **`/ (root)`**, then save.
5. After GitHub Pages finishes deploying, visit https://hartmut-se.github.io/ipaklick/.

The root `index.html` is the entry page for the project site. `readme.html` remains available as a direct URL, and the interface remains at `ipa-text-input.html` (formerly `interface.html`).

## Notes

The supplied HTML files are preserved, except that `readme(5).html` has been named `readme.html` so the interface's existing help link (`readme.html`) resolves correctly. `index.html` is a copy of `readme.html` so the project root opens the instructions page.

No software license file is included; add one only if you wish to specify formal reuse terms.
