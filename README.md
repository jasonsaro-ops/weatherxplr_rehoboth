# WEATHERXPLR · Rehoboth Beach 19971

Local WeatherXplr board for Rehoboth Beach / ZIP 19971 (Sussex County, DE — PHI CWA).

## Layout
- **Left rail** — sample point, current conditions, gauges, AQI
- **Center** — dual Windy maps (radar + wind); secondary column bottom = **NWS alerts** (19971 point + Sussex / DE beaches)
- **Right rail** — 10-day forecast, temp / PoP / wind sparklines, NOAA tides, coastal DE hydro

## Features
- Dual Windy embeds (layer selectors)
- NWS alerts for **19971 + Sussex County / DE beaches** (PHI CWA)
- Current conditions (Open-Meteo) + 48h sparklines
- Air quality (Open-Meteo) + 48h AQI / PM2.5 sparklines
- Hydro — USGS coastal / bay gauges near Rehoboth:
  - Rehoboth Bay @ Dewey Beach `01484670`
  - Broadkill River near Milton `01484272`
  - Millsboro Pond Outlet `01484525`
  - Indian River near Oak Orchard `01484720`
  - Nanticoke River near Bridgeville `01484000`
- NOAA tides (station 8557380, Lewes, DE — nearest active)
- Click **WEATHERXPLR** (top left) to refresh data and recenter Windy maps on 19971

## Deploy
Static site — GitHub Pages. No worker required.

## Files
| Path | Role |
|------|------|
| `index.html` | Board UI |
| `app.js` | Feeds + dual Windy + alerts + sparks + tides + hydro |
