# Simple Weather PWA 🌦️

A lightweight, no-build weather Progressive Web App (PWA) built with vanilla HTML, CSS, and JavaScript. Get current conditions, 7-day forecasts, and animated weather radar for any location worldwide.

[**🔗 Live Demo**](https://eric-lautanen.github.io/SimpleWeather/)

---

## Features

* **Global Coverage:** Search any city or ZIP code worldwide for instant weather data
* **Current Conditions:** Real-time temperature, weather description, wind speed, humidity, and pressure
* **7-Day Forecast:** Daily high/low temperatures with weather conditions
* **Interactive Weather Map:** Animated precipitation radar with multiple visualization layers:
  - Live radar (rain/snow/mixed precipitation)
  - Satellite cloud imagery
  - Topographic terrain
  - High-resolution satellite imagery
  - NASA Earth at Night
* **Unit Switching:** Toggle between Fahrenheit/Celsius and mph/km/h
* **Theme Support:** Dark and Light mode with automatic map tile switching
* **Location History:** Saves up to 10 recent searches with one-click access
* **IP Geolocation:** Automatically detect your location
* **Fully Responsive:** Optimized for desktop, tablet, and mobile
* **Offline-Ready:** Works as a standalone desktop or mobile app (no server needed)

---

## How to Use

### Online
Visit the [live demo](https://eric-lautanen.github.io/SimpleWeather/) in any modern web browser.

### Offline/Standalone
1. Download the `index.html` file from this repository
2. Rename it to whatever you prefer (e.g., `weather.html`)
3. Double-click to open in your browser, or:
   - **Desktop:** Drag to your desktop for quick access
   - **Mobile:** Use your browser's "Add to Home Screen" feature for a native-like app experience

No installation, no build process, no dependencies beyond the browser itself.

---

## Tech Stack

* **HTML5** - Semantic markup with ARIA accessibility
* **CSS3** - Modern layouts with CSS Grid, Flexbox, and CSS Variables
* **Vanilla JavaScript** - No frameworks, just ES6+
* **Leaflet.js** - Interactive mapping library
* **LocalStorage API** - Client-side data persistence

---

## Development

This project was developed with assistance from AI coding assistants:

* **[Claude](https://www.anthropic.com/claude)** by Anthropic - Code generation and architecture guidance
* **[Gemini](https://gemini.google.com)** by Google - Feature development and problem-solving
* **[Grok](https://grok.x.ai)** by xAI - Code optimization and debugging support

---

## Credits

This project leverages several open-source libraries and public data APIs to provide real-time weather information and interactive mapping.

### Libraries & Frameworks

* **[Leaflet.js (v1.9.4)](https://leafletjs.com)** - Open-source JavaScript library for mobile-friendly interactive maps
  * License: BSD-2-Clause

### Weather Data & Geocoding APIs

* **[Open-Meteo](https://open-meteo.com)** - Global weather forecasting and current conditions data
  * Free tier with no API key required
* **[Open-Meteo Geocoding API](https://open-meteo.com/en/docs/geocoding-api)** - Location search and coordinate conversion
* **[IP-API](https://ip-api.com)** - IP-based geolocation for automatic location detection

### Map Layers & Radar Data

* **[OpenStreetMap](https://www.openstreetmap.org)** - Default base map tiles
  * License: ODbL
* **[CartoDB Dark Matter](https://carto.com/basemaps)** - Dark theme map tiles
* **[RainViewer](https://www.rainviewer.com)** - Real-time global radar and satellite precipitation overlays
  * [API Documentation](https://www.rainviewer.com/api.html)
* **[OpenTopoMap](https://opentopomap.org)** - Topographic terrain visualization
* **[Esri World Imagery](https://www.arcgis.com)** - High-resolution satellite imagery layer
* **[NASA GIBS](https://earthdata.nasa.gov/eosdis/science-system-description/eosdis-components/gibs)** - "Earth at Night" (VIIRS City Lights) visual layer

---

## License

This project is open source and available under the [MIT License](LICENSE).

---

## Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the [issues page](../../issues).

---

## Author

**Eric Lautanen**

* GitHub: [@eric-lautanen](https://github.com/eric-lautanen)
