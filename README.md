# Scale & Chord Explorer (iPhone and iPad web app)

Static files only. No build step needed.

## Deploy on GitHub Pages
1. Copy this folder into your Pages repo as `scales/` (any folder name works; all paths are relative).
2. Commit and push. It will be served at https://egarcialopez.dev/scales/

## Install on iPhone or iPad
1. Open the URL in **Safari** (other browsers on iPad can't install web apps the same way).
2. Share → **Add to Home Screen** → Add.
3. Open it once while online so the fonts are cached. After that it works offline.

## Updating
Edit `index.html`, then change `VERSION` in `sw.js` (e.g. `scales-v2`) so installed copies refresh.
The app uses the network first, so a relaunch while online picks up the change.

## Files
- `index.html` – the whole app (HTML, CSS, JS in one file)
- `manifest.webmanifest` – name, icons, standalone display
- `sw.js` – offline cache
- `icons/` – home-screen icons (180, 192, 512, maskable 512)
