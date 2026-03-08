# 5.6 Secrets Project

Small Express and EJS app using axios to fetch a random "secret" from an external API and display it on the homepage.

## Prerequisites
- Node.js (v14+ recommended)
- npm

## Install
1. Install dependencies:

```bash
npm install
```

## Run
Start the server:

```bash
node index.js
```

Open http://localhost:3000 in your browser.

## Project structure

- `index.js` — main Express server (serves static files and renders `index.ejs`).
- `solution.js` — (extra/alternate solution file if present).
- `package.json` — project metadata and dependencies.
- `views/` — EJS templates (contains `index.ejs`).
- `public/` — static assets (CSS, images).

## Notes
- The server listens on port 3000 by default (see `index.js`).
- The app uses `axios` to request a random secret from `https://secrets-api.appbrewery.com/random`.
