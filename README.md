# GB Route Planner PWA

This folder contains the installable PWA version of the Gilgit-Baltistan Route Planner.

## Files

- `index.html` — main planner
- `manifest.webmanifest` — Android/Chrome app installation settings
- `service-worker.js` — offline caching
- `icons/` — Android home-screen icons

## GitHub Pages deployment

1. Create a new GitHub repository, for example: `gb-route-planner`.
2. Upload all files in this folder to the root of the repository.
3. Go to repository Settings.
4. Open Pages.
5. Under Build and deployment, select:
   - Source: Deploy from a branch
   - Branch: main
   - Folder: /root
6. Save.
7. Wait a few minutes for GitHub Pages to publish the site.
8. Open the published GitHub Pages link on Android Chrome.
9. Tap the three-dot menu and select Add to Home screen or Install app.

## Android install note

The PWA must be opened from an HTTPS link, such as GitHub Pages. Opening `index.html` directly from phone storage may show the planner, but normally will not install as a proper PWA.
