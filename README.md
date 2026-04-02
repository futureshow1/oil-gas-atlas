# Global Oil & Gas Infrastructure Atlas

Interactive map visualization of the world's oil and gas infrastructure — pipelines, extraction fields, LNG terminals, and major transport routes across every continent.

## Live Demo

**[View the Atlas](https://futureshow1.github.io/oil-gas-atlas/)**

## Features

- **6 Regional Maps** — Europe, Asia & Middle East, North America, South America, Africa, Oceania/Australia
- **90+ pipelines** with animated flow effects, capacity data, and operational status
- **80+ oil & gas fields** with production rates, reserve estimates, and discovery years
- **70+ LNG terminals** (export and import) with capacity and status tracking
- **Hover tooltips** on all pipelines showing name, capacity, and description
- **Click popups** with detailed data for every element
- **Filter controls** — toggle pipelines, fields, LNG terminals on/off
- **Regional focus buttons** — zoom to key areas (Permian Basin, Vaca Muerta, Pre-Salt, etc.)
- **Status-aware styling** — active (green), damaged (red), shut (gray), proposed (dashed), under construction (blue)
- **Dark theme** with animated pulsing markers and flowing pipeline effects
- **Fully self-contained** — each map is a single HTML file, no build tools needed

## Technology

- **Leaflet.js** (v1.9.4) via CDN for interactive map rendering
- **CartoDB Dark** tile layer
- CSS keyframe animations for marker pulsing and pipeline flow
- Responsive design — works on desktop and mobile

## Data

Production figures, reserve estimates, and status information are based on publicly available data as of early 2026. Pipeline routes are simplified representations. This is a visualization project — actual figures may vary.

## Structure

```
index.html                    — Landing page
europe-oil-gas-map.html       — Europe (27 pipelines, 9 fields, 28 LNG)
asia-oil-gas-map.html         — Asia & Middle East (29 pipelines, 19 fields, 36 LNG)
north-america-oil-gas-map.html — North America (31 pipelines, 12 fields, 13 LNG)
south-america-oil-gas-map.html — South America (15 pipelines, 17 fields, 11 LNG)
africa-oil-gas-map.html       — Africa (12 pipelines, 19 fields, 12 LNG)
oceania-oil-gas-map.html      — Oceania/Australia (9 pipelines, 12 fields, 11 LNG)
oil-gas-world-map.html        — Combined world overview
```

## License

Open source. Data sourced from public domain resources.
