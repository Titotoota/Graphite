# Graphite

A lightweight graphing calculator for algebra, trig and calculus — runs entirely in the browser, installable as an offline-capable app (PWA).

**Live app:** https://titotoota.github.io/Graphite/

## Features

- Plot functions on an interactive, zoomable/pannable graph
- Sliders for parameters, with play/animate controls
- Show/hide individual expressions, color-code each one
- On-screen math keypad (works on touch devices)
- Installable to your phone's home screen and works offline after the first load

## Installing on your phone

1. Open the live app link above in Safari (iOS) or Chrome (Android).
2. Tap the Share button, then **Add to Home Screen**.
3. Open it from the home screen icon — it runs full screen and works offline.

## Development

This is a static site — no build step. `index.html` contains the app, `manifest.webmanifest` and `sw.js` provide the PWA/offline behavior, and `icons/` holds the home-screen icons.

To preview locally, serve the folder with any static file server, e.g.:

```bash
python3 -m http.server
```

Then open `http://localhost:8000`.

## License

MIT — see [LICENSE](LICENSE).
