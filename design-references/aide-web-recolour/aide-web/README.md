# Aide web app

A single-page web app with three views: Home (3D living-room banner), Track & Monitor (sundowning episode log and chart) and Companion (speaks messages, plays recordings, rings).

## Run locally
Open `index.html` in a browser, or serve the folder:

    npx serve .

## Deploy
Upload the folder to any static host (Netlify, Vercel, GitHub Pages, Cloudflare Pages). No build step.

## Notes
- 3D uses three.js r128 from cdnjs; fonts come from Google Fonts.
- Episodes and settings are stored in the browser's localStorage only.
- Spoken messages use the browser's built-in speech synthesis.
- Pages are reachable as `#home`, `#monitor` and `#companion`.
