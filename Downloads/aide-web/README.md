# Aide web app

A single-page web app with four views: Home (3D living-room banner), Track & Monitor (sundowning episode log and chart), Companion (speaks messages, plays recordings, rings) and Evidence informed (sources and what AIDE does and doesn't do). A Customise panel changes the companion's face, voice tone and room name.

## Run locally
Open `index.html` in a browser, or serve the folder:

    npx serve .

## Deploy
Upload the folder to any static host (Netlify, Vercel, GitHub Pages, Cloudflare Pages). No build step.

## Notes
- 3D uses three.js r128 from cdnjs; fonts (Outfit, Caveat Brush), logo and icons are in `assets/`.
- Episodes and settings are stored in the browser's localStorage only.
- Spoken messages use the browser's built-in speech synthesis.
- Pages are reachable as `#home`, `#monitor`, `#companion` and `#evidence`.
