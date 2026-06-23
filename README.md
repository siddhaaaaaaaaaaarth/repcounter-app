# Workout Tracker

A dark-mode, installable (PWA) gym workout tracker. Log exercises, reps, weight,
multiple workout routines, and per-set drop sets. Data is saved locally in the
browser — no account, works offline.

## Files
- `index.html` — the whole app
- `manifest.webmanifest` — makes it installable
- `sw.js` — service worker (offline support)
- `icons/` — app icons

## Deploy to GitHub Pages

1. Create a new **public** repo on GitHub (no README/license — keep it empty).
2. From this folder, point it at your repo and push:
   ```sh
   git remote add origin https://github.com/<you>/<repo>.git
   git push -u origin main
   ```
3. On GitHub: **Settings → Pages → Build and deployment → Source: "Deploy from a
   branch"**, branch **main**, folder **/ (root)**, then **Save**.
4. After a minute the app is live at `https://<you>.github.io/<repo>/`.

## Install on your phone
Open that URL in your phone's browser:
- **Android (Chrome):** menu (⋮) → **Install app** / **Add to Home screen**.
- **iPhone (Safari):** Share button → **Add to Home Screen**.

It then launches full-screen like a native app.
