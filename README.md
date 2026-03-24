# Coach AI — Performance Tracking System

## Deploy to Vercel

1. Fork this repo / upload to GitHub
2. Go to vercel.com → New Project → Import from GitHub
3. Deploy with default settings (no build command needed)
4. Done — accessible on web + mobile browser

## Run locally

```bash
# Any of these work:
npx serve .
python3 -m http.server 8000
# Then open http://localhost:8000
```

## Mobile (PWA)

On iPhone/Android: open in Safari/Chrome → Share → "Add to Home Screen"
Works offline after first load.

## Files

- `index.html` — Complete app (4MB, all dependencies bundled)
- `vercel.json` — Vercel config for static hosting

## Tech

React 18 + Babel JSX (compiled in browser) + Chart.js + jsPDF
No server required — 100% client-side, localStorage persistence
