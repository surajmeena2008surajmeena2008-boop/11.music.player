# 11 Music Player v0.0.1

A local-music player packaged as a static Progressive Web App (PWA). Your songs stay on your device.

## Publish on GitHub Pages
1. Create a public GitHub repository and upload all files from this ZIP to its root.
2. Open **Settings → Pages**, choose **Deploy from a branch**, select `main` and `/(root)`, then Save.
3. Open the published HTTPS link in Chrome on Android.
4. Use Chrome menu (⋮) → **Add to Home screen** / **Install app**.

## Playback controls
- **Speed** adjusts playback rate from 0.50× to 1.25×.
- **Pitch** is a conventional semitone control from -12 to +12. It changes pitch by changing playback rate, so tempo changes with pitch.
- **Normal** resets speed and pitch; **Slow** sets speed to 0.82×.

## Files
- `index.html` — player and settings
- `manifest.json` — install metadata
- `sw.js` — offline support and app version cache
- PNG icons — app icons

This release is labelled v0.0.1 as requested. If you clear browser site data, add your songs again.
