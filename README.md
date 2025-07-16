# air-quality-visualizer
Air Quality Visualiser
•	MVP features:
In Scope (Must Have)
- User can see air quality metrics (AOD, NO₂) for their location on a map, derived from Google Earth Engine.
- AQI zones are color-coded (green/good, yellow/moderate, red/unhealthy, etc.) based on satellite data.
- User can view a simple historical trend graph for their location using GEE data.
- App displays health recommendations based on satellite-derived AQI proxies.

•	Data Source
- Primary: Google Earth Engine, using MODIS (AOD) and Sentinel-5P (NO₂) datasets.
- No reliance on OpenAQ.

•	Tech Stack
- Frontend: React
- Backend: Node.js + Express (or Python FastAPI)
- Database: Supabase
- Map: Google Maps API

