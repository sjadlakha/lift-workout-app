# Lift — 4 Day Program (PWA)

A lightweight, privacy-first progressive training app built as a single static Progressive Web App (PWA). Designed for mobile (iPhone-first) use — swipe through exercise cards, log sets, and use the built-in rest timer. All data is stored locally on the device (no server required).

**Key features**

- Simple, single-file app: UI + logic in `index.html`.
- Offline-capable PWA with a service worker (`sw.js`) and manifest (`manifest.webmanifest`).
- Persistent logs using `localStorage` (weights, reps, RIR, warm-up checks).
- Rest timer with vibrate support and quick +/-15s adjustments.
- Mobile-friendly layout and "Add to Home Screen" support for native-like install.

**Quick start (local)**

- Use any static server to preview the app (recommended for proper service-worker behavior).
