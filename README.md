# Quick Weather PWA 🌦️

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
1. Clone the repository.
2. Open `wx.html` in any modern web browser.
3. Enter a 5-digit US ZIP code to view the weather.

## Known Issues ⚠️
* **Radar Switching:** There are currently bugs with the radar source selector. While the UI allows selecting NOAA or OpenWeather, the map logic is currently optimized for RainViewer. A fix to enable seamless switching between sources is coming soon.

## Credits
* **Weather Data:** [National Weather Service API](https://www.weather.gov/documentation/services-web-api)
* **Location Data:** [Zippopotam.us](https://api.zippopotam.us)
* **Radar Data:** [RainViewer API](https://www.rainviewer.com/api.html)
* **Maps:** [Leaflet.js](https://leafletjs.com/) & [OpenStreetMap](https://www.openstreetmap.org/)
