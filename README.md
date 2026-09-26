# Graphite

A lightweight graphing calculator for algebra, trig and calculus — runs entirely in the browser, installable as an offline-capable app (PWA).

**Live app:** https://titotoota.github.io/Graphite/

## Features

- Plot functions on an interactive, zoomable/pannable graph
- Sliders for parameters, with play/animate controls
- Show/hide individual expressions, color-code each one
- On-screen math keypad (works on touch devices)
- Installable to your phone's home screen and works offline after the first load
- Works on phones (portrait and landscape), iPad and computers — scroll to zoom and type straight from the keyboard on a PC

## Installing

- **iPhone / iPad:** open the live app link in Safari, tap Share, then **Add to Home Screen**.
- **Android:** open it in Chrome, then ⋮ menu → **Install app**.
- **Computer:** just use the website (Chrome/Edge also offer an install button in the address bar).

It runs full screen from the home screen icon and works offline after the first visit.

## Development

This is a static site — no build step. `index.html` contains the app, `manifest.webmanifest` and `sw.js` provide the PWA/offline behavior, and `icons/` holds the home-screen icons.

To preview locally, serve the folder with any static file server, e.g.:

```bash
python3 -m http.server
```

Then open `http://localhost:8000`.

## Versions

See [CHANGELOG.md](CHANGELOG.md) for what changed in each version, and [Releases](https://github.com/Titotoota/Graphite/releases) to view or download any past version.

## License

MIT — see [LICENSE](LICENSE).
