# T-BOOST Protocol — PWA Setup Guide

## What's in this folder
- index.html   → Main app (all content, fully offline)
- manifest.json → Makes it installable as an app
- sw.js         → Service worker (caches everything for offline use)
- icon-192.svg  → App icon (small)
- icon-512.svg  → App icon (large)

---

## How to Install on Your Phone (Android)

1. Copy this entire folder to your phone, OR host it locally (see below)
2. Open Chrome on your phone
3. Open the index.html file
4. Tap the 3-dot menu → "Add to Home Screen"
5. Done! It installs like a real app ✅

## How to Install on iPhone (iOS Safari)

1. Open index.html in Safari
2. Tap the Share button (box with arrow)
3. Scroll down → tap "Add to Home Screen"
4. Tap "Add" ✅

## How to Run Locally on PC/Mac (for phone access)

Option A — Python (simplest):
  1. Open terminal in this folder
  2. Run: python3 -m http.server 8080
  3. Open phone browser → type your PC's IP:8080
  4. Example: http://192.168.1.5:8080

Option B — VS Code:
  Install "Live Server" extension → right-click index.html → Open with Live Server

## Just Double-Click (no install needed)
Simply double-click index.html — it opens in your browser and works fully offline.
No internet required after first load.
