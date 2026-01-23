# Simple Weather PWA 🌦️

A lightweight, no-build weather Progressive Web App (PWA) built with vanilla HTML, CSS, and JavaScript. It provides real-time current conditions, forecasts, and an animated radar map for US locations.

[**🔗 Live Demo**](https://eric-lautanen.github.io/SimpleWeather/)

## Features
* **Instant Weather:** Get current temperature and local forecasts by ZIP code.
* **Animated Radar:** Interactive map with live precipitation loops powered by RainViewer.
* **Dynamic Colors:** Radar colors change based on temperature (Rain, Snow, or Mixed).
* **Theme Support:** Toggle between Dark and Light modes.
* **Local History:** Automatically saves your recent locations for quick access.
* **Responsive:** Designed for both desktop and mobile devices.

## How to Use
Download the raw index.html file, rename it whatever you want and put it on your desktop or homescreen.  No server needed.

# Credits

This project leverages several open-source libraries and public data APIs to provide real-time weather information and interactive mapping.

## Libraries & Frameworks

* **Leaflet.js (v1.9.4)**: An open-source JavaScript library for mobile-friendly interactive maps.
    * Website: [https://leafletjs.com](https://leafletjs.com)
* **Google Fonts**: Utilizes the system font stack and sans-serif fallbacks for a clean interface.

## Weather Data & Search APIs

* **OpenStreetMap (Nominatim)**: Used for global geocoding and location search based on city names or zip codes.
* **National Weather Service (NWS / weather.gov)**: Provides high-resolution weather forecasts and current conditions for US-based locations.
* **Open-Meteo**: Provides global weather forecasting and current weather data for locations outside the United States.

## Map Layers & Radar Data

* **RainViewer**: Source for real-time global radar and satellite precipitation overlays.
* **Esri (World Imagery)**: Provides the static high-resolution satellite imagery layer.
* **NASA GIBS**: Provides the "Earth at Night" (VIIRS City Lights) visual layer.
* **Thunderforest**: Provides the detailed topography map tiles.

## Assets

* **Leaflet Default Markers**: Used for pinpointing locations on the interactive map.
* **Base64 Icons**: Minimal UI elements used for markers and interface feedback.
