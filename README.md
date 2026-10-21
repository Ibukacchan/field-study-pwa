# The Scholar's Field Journal

A mobile-friendly, dark-academia Field Study planner for GitHub Pages.

## Included files
- `index.html` — planner interface, daily and weekly personal task views, motto, and episode checklist.
- `data.json` — Field Study episode/task data used by the checklist.
- `manifest.json` — installable PWA metadata.
- `sw.js` — service worker for caching core files for offline access after the first successful visit.
- `icon.svg`, `icon-192.png`, `icon-512.png` — app icons.

## Publish on GitHub Pages
1. Download and extract this ZIP.
2. Upload **all files inside this folder** to the root of your GitHub repository (not the enclosing folder).
3. Keep the filenames unchanged, especially `index.html` and `data.json`.
4. Commit the changes and ensure GitHub Pages is enabled for the correct branch/folder.
5. Open the published HTTPS URL in Chrome. Use the browser menu and choose **Install app** or **Add to Home screen**.

## Notes
- Checklist checks and personal planner tasks are saved in this browser on this device using local storage; they do not sync automatically between devices.
- Offline caching becomes available after the first successful visit while online.
