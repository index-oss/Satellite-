Advanced Satellite Tracker

A real‐time satellite tracking web application using Leaflet.js, Satellite.js, Chart.js, and OpenWeatherMap API.

## Features

- Interactive Map with real-time satellite positions.  
- Tracks multiple satellites including:  
  • ISS (International Space Station)  
  • NOAA 19  
  • Hubble Space Telescope  
- Nearest Satellite Display relative to your geolocation.  
- Weather Information overlay at satellite location.  
- Live Speed Chart for each satellite.  
- Custom satellite icons with SVG styling.  
- Filter Panel to toggle satellite visibility.

---

## Project Structure

- `index.html` — Main application with HTML, CSS, and JavaScript  
- `README.md` — This file  

---

## Tech Stack

- Leaflet.js – for map rendering and interaction  
- Satellite.js – for TLE propagation and satellite tracking  
- Chart.js – for speed visualization  
- OpenWeatherMap API – for current weather info  
- HTML5, CSS3, JavaScript (Vanilla)  

---

## How It Works

1. **Geolocation**: Fetches the user's current position using the `navigator.geolocation` API.  
2. **TLE Data**: Uses hardcoded TLE (Two-Line Element) data for each satellite.  
3. **Position Calculation**: Satellite positions are updated every 3 seconds using satellite.js.  
4. **Mapping**:  
   - Satellite locations are plotted with animated trails.  
   - Clicking on a satellite shows:  
     - Location (Lat, Lng)  
     - Altitude  
     - Speed  
     - Weather at location  
     - Speed chart (last 20 data points)  
5. **Filtering**: Users can toggle which satellites are shown using checkboxes.

---

## Setup Instructions

1. Clone the Repository  
   ```bash
   git clone https://github.com/yourusername/advanced-satellite-tracker.git  
   cd advanced-satellite-tracker
