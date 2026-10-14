# EcoTrace – Daily Carbon & Water Footprint Tracker
CHY1006 Environmental Sustainability · Energy Sources & Sustainability / Water footprint

A single-page web app (PWA). Log daily electricity, cooking gas, fuel, water and diet; it shows your CO2e and water footprint (direct + virtual), 7-day charts and tips. Data stays in your browser. Works offline once installed.

## Run locally
Open `index.html` in a browser. (Install/offline mode needs HTTPS or localhost, e.g. `python -m http.server` then open http://localhost:8000.)

## Host free on GitHub Pages
1. Create a GitHub repo, upload all files in this folder.
2. Settings > Pages > Deploy from branch `main` / root.
3. Open the Pages URL. In Chrome/Edge use "Install app"; on Android use "Add to Home screen"; on iPhone use Share > "Add to Home Screen".

## Files
index.html (app) · manifest.webmanifest + sw.js (PWA/offline) · icon.svg, icon-192.png, icon-512.png

## Notes
Emission factors and prices are approximate (India grid 0.71 kg CO2/kWh, LPG 2.98 kg/kg, petrol 2.31 kg/L, diesel 2.68 kg/L). Illustrative, not an audit.
