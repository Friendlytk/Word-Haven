# Word Haven

A relaxing, Zen-inspired word puzzle game built with vanilla HTML, CSS and JavaScript. Designed mobile-first for Android browsers and desktop web.

## Features

- Letter selection by tapping or swiping
- Hidden-word board with progress tracking
- Bonus words and coin rewards
- Hint and shuffle controls
- Level progression and locally saved progress
- Installable Progressive Web App foundation
- Service-worker caching for offline return visits
- Responsive layout for mobile and desktop

## Run locally

Open `index.html` in a browser. For full PWA/offline testing, serve the folder over HTTPS or localhost.

## Publish with GitHub Pages

1. Open **Settings → Pages** in this repository.
2. Under **Build and deployment**, select **Deploy from a branch**.
3. Choose branch **main** and folder **/(root)**, then save.
4. Wait for GitHub Pages to publish the site.

The expected site URL is `https://friendlytk.github.io/Word-Haven/`.

## Install on Android

After the site is published over HTTPS, open it in Chrome on Android and use **Install app** or **Add to Home screen**. A signed APK wrapper can be added in a later phase.

## Project files

- `index.html` — screens and game layout
- `styles.css` — responsive Zen-inspired styling
- `app.js` — gameplay, puzzle data and local progress
- `manifest.webmanifest` — PWA metadata
- `sw.js` — offline asset cache
- `icon.svg` — app icon

## Current scope

The first playable foundation has 20 puzzle templates mapped across 100 level numbers. The puzzle bank will be expanded with more unique boards, broader word validation, and tested difficulty progression in subsequent development phases.

Word Haven is an original project inspired by the general word-connect puzzle genre. It does not use ZenWord's proprietary assets or branding.
