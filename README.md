# Personal site

A minimal one-page personal site for Kerstin Hötte. Deploys on GitHub Pages.

## Quick start
1. Create a public repository named `YOUR-USERNAME.github.io` (or any repo for a project site).
2. Upload these files to the repo root:
   - `index.html`
   - `cv.pdf`
3. Commit and push. GitHub will publish automatically at:
   - User site: https://YOUR-USERNAME.github.io
   - Project site: https://YOUR-USERNAME.github.io/REPO-NAME/

## Dark mode
Click the **🌓 Theme** button to switch between System / Dark / Light. The choice is saved in `localStorage`.

## Analytics (stub)
The page includes a tiny local analytics stub that logs a pageview to the console. To use a hosted privacy-friendly service later:
- **Plausible**: add `<script defer data-domain="your-domain.com" src="https://plausible.io/js/script.js"></script>`
- **Fathom**: add `<script src="https://cdn.usefathom.com/script.js" data-site="YOUR-CODE" defer></script>`

If you prefer to self-host, set `window.ENABLE_ANALYTICS = true` before the script to send a `navigator.sendBeacon` to `/analytics` (you'd provide that endpoint).

© 2025 Kerstin Hötte
