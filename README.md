# Med Tracker

A personal medication dosage countdown app built as a Progressive Web App (PWA).

**Live app:** [jarrettdavidson.github.io/med-tracker](https://jarrettdavidson.github.io/med-tracker/)

## Features

- **Dosage countdown** — Track remaining doses for each medication with visual progress bars
- **Time-of-day grouping** — Medications organized by Morning, Midday, Evening, Night, and As Needed (PRN)
- **Refill alerts** — Calculates when to reorder based on your supply, frequency, and pharmacy lead time
- **Took Dose / Refill** — One-tap dose logging with full timestamped history per medication
- **Offline support** — Works without internet via service worker caching
- **iPhone home screen app** — Add to Home Screen for full-screen, no-browser-bar experience

## Install on iPhone

1. Open the live URL in **Safari**
2. Tap the **Share** button (square with arrow)
3. Tap **"Add to Home Screen"**
4. Tap **Add**

## Data Storage

All data is stored in your browser's `localStorage` — nothing is sent to any server. Data persists between sessions as long as you use the same browser and don't clear site data.

## Tech Stack

- Single-file HTML/CSS/JS (no build step, no dependencies)
- PWA with web app manifest and service worker
- Google Fonts: Outfit (display), Plus Jakarta Sans (body)

## Files

| File | Purpose |
|---|---|
| `index.html` | Complete application |
| `manifest.json` | PWA manifest for install prompts |
| `sw.js` | Service worker for offline caching |
| `apple-touch-icon.png` | iOS home screen icon (180×180) |
| `icon-192.png` | Android icon (192×192) |
| `icon-512.png` | Splash screen icon (512×512) |
