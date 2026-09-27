# TAARA — SIH26083 Heat Risk Intelligence Prototype

A responsive React/Vite prototype for SIH26083: Extreme Heatwave Early Warning and Human Thermal Stress Index.

## Included
- Government Authority / Public demo login
- Live weather refresh using Open-Meteo current + hourly data
- Temperature, humidity, wind, solar radiation
- Thermal risk score combining weather + local vulnerability proxy
- Hyper-local GIS map with separate risk polygons for each mandal/zone
- Ward-level alert feed and demo alert creation
- Responsive modern UI for desktop/mobile
- 24-hour visual outlook

## Run locally
1. Install Node.js 18+.
2. Extract this folder.
3. Open a terminal in the folder.
4. Run `npm install`
5. Run `npm run dev`
6. Open the local URL shown by Vite.

## Deploy to GitHub + Vercel
- Push the entire folder to a GitHub repository.
- Import the repository into Vercel.
- Framework preset: Vite.
- Build command: `npm run build`
- Output directory: `dist`
- No environment variable is required for the demo weather API.

## Important production work
The included map polygons are intentionally DEMO polygons. Replace them with official ward/mandal GeoJSON boundaries. Connect a secure backend for government authentication, alert delivery, audit logs, historical health/demographic datasets, and a validated thermal-stress/mortality model.

The displayed risk score is a prototype indicator, not a clinical or official public-health risk estimate.
