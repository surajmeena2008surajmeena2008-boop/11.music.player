# 11 Music Player v0.0.1

A local-music player packaged as a static Progressive Web App (PWA). Your songs stay on your device.

## Publish on GitHub Pages
1. Create a public GitHub repository and upload all files from this ZIP to its root.
2. Open **Settings → Pages**, choose **Deploy from a branch**, select `main` and `/(root)`, then Save.
3. Open the published HTTPS link in Chrome on Android.
4. Use Chrome menu (⋮) → **Add to Home screen** / **Install app**.

## Playback controls
- **Speed** adjusts tempo from 0.50× to 1.50× while preserving pitch.
- **Pitch** has an independent -12 to +12 semitone control.
- **Reverb**, **Timbre**, and **Bass Boost** are live Web Audio effects.
- Presets include Original, Slowed, Nightcore, Daycore, Night Drive, Sad Edit, Dreamcore, Space Reverb, and Phonk Drift.
- **Split Song** lets you add time-based sections and assign a different preset to each section during playback. Section edits are session-only.

## Files
- `index.html` — player and settings
- `manifest.json` — install metadata
- `sw.js` — offline support and app version cache
- PNG icons — app icons

This release is labelled v0.0.1 as requested. If you clear browser site data, add your songs again.


## Custom themes and wallpapers
- Open **Custom theme colour** to choose a main colour, an accent colour, and dark/light mode, then create and save a personal theme.
- The wallpaper panel includes seven built-in wallpapers. Select any thumbnail to apply it, or use the wallpaper pill to choose an image from your device.
- Built-in wallpapers are included in the service-worker cache for offline use.


## Audio notes
- Effects are processed locally in the browser using the Web Audio API; audio is not uploaded.
- Output quality depends on the source file, browser, device, and audio hardware.
- Split Song currently applies section presets during playback; it does not render or export a newly mixed audio file.
