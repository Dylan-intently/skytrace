# ✈️ SkyTrace — Live Flight Tracker

A premium flight tracking web app inspired by FlightRadar24, built with a clean modern dark UI. Works as a single HTML file — no build step, no server needed.

## 🚀 Getting it live on GitHub Pages

1. Create a new GitHub repo (e.g. `skytrace`)
2. Upload the `index.html` file (drag and drop in the GitHub UI)
3. Go to **Settings → Pages → Source** → select `main` branch
4. Your app is live at `https://yourusername.github.io/skytrace`

## 🗺️ Adding your Mapbox token (required for the map)

1. Sign up free at [mapbox.com](https://account.mapbox.com)
2. Copy your **public access token**
3. Open `index.html` and find this line near the bottom:
   ```js
   const MAPBOX_TOKEN = 'pk.eyJ1IjoiZGVtby11c2VyI...'
   ```
4. Replace the value with your token and save

## ✨ Features

- 🗺️ Live interactive world map (Mapbox GL JS)
- ✈️ 180 animated aircraft with real heading rotation
- 🔍 Instant search — flights, airports, airlines
- 📋 Collapsible sidebar — live list, filters, airports, saved
- 📌 Aircraft detail panel — altitude, speed, heading, ETA, weather
- 🏢 Airport modal — live departures & arrivals board
- ⚙️ Settings — map style (dark/satellite/terrain/minimal), units
- 💾 Save/track flights (persisted in browser)
- 📱 Responsive — works on mobile

## 🛠️ Tech

Pure HTML + CSS + JavaScript. No frameworks, no build tools, no Node.js.
Uses Mapbox GL JS (CDN) for the map and Google Fonts (CDN) for typography.
