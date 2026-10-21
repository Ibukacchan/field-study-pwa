# Field Study 1 — Divide To-Do PWA

## What's included
- `index.html`: checklist app with search, episode filters, progress bars, expand/collapse, and reset.
- `data.json`: episodes 1–16, tasks, starting checked states, and suggested schedule.
- `manifest.json`, `sw.js`, `icon.svg`: install/offline PWA assets.

## Schedule
- EP 1–12: Oct 21–Nov 11, 2026; final checking Nov 12; buffer Nov 13.
- EP 13–16: Nov 21–30, 2026.
- EP 3 tasks are initially checked to match the checklist you supplied. EP 1's Observation Facilities Checklist is also initially checked.
- Checkbox progress is stored in the browser on the current device.

## How to use/install
A PWA needs to be served from HTTPS (or localhost); opening `index.html` directly as a file will not enable installation or service-worker offline caching.
1. Upload the contents of this folder to a static host such as GitHub Pages or Netlify (HTTPS).
2. Open the hosted site in Chrome on Android.
3. Open the browser menu and choose **Install app** or **Add to Home screen**.
4. Open it once while online so the app files can be cached for offline use.

The included data and checklist work without a backend. Browser storage is local to that browser/device; clearing site data may erase saved checks.
