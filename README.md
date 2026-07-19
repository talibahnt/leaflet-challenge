# leaflet-challenge
The code is in the Leaflet part 1 and 2. It can also be found in Leaflet Map 1 and Map 2.

---

```markdown
# Leaflet Challenge: Visualizing Geological Data

## Project Overview
This repository contains a dynamic, interactive web-based map built using JavaScript and Leaflet.js to visualize global geological data. The project is split into two distinct parts: mapping global seismic activity (Earthquakes) and layering tectonic boundary data to provide a comprehensive look at planetary shifting.

The complete code and implementations can be found across the project directories: **Leaflet Part 1 & 2** and **Leaflet Map 1 & Map 2**.

---

## Features

### Part 1: Earthquake Visualization (`Leaflet Map 1`)
*   **Live USGS Data Integration:** Fetches real-time earthquake data from the United States Geological Survey (USGS) GeoJSON feed (past 7 days).
*   **Proportional Marker Sizing:** The radius of each circular marker directly reflects the magnitude of the earthquake.
*   **Color-Coded Depths:** Markers are dynamically styled based on the depth of the earthquake (measured in kilometers), showing that deeper quakes present unique risks.
*   **Interactive Tooltips/Popups:** Clicking any individual data point opens a popup detailing the precise magnitude, location string, and depth record.
*   **Dynamic Custom Legend:** A static, styled contextual map legend breaks down the color scale used for depth categorization.

### Part 2: Tectonic Plates Layering (`Leaflet Map 2`)
*   **Tectonic Boundaries Overlay:** Imports a second independent dataset detailing fault lines and tectonic plate boundaries around the world.
*   **Layer Controls:** An added interactive control layer toggle allowing users to turn the earthquake data stream and tectonic plate layers on or off independently.
*   **Base Map Switching:** Seamlessly toggles between distinct style perspectives (e.g., Street View, Topographic, or Satellite views) to change the backdrop representation.

---

## Technical Stack
*   **Front-End Framework:** HTML5, CSS3, JavaScript (ES6+)
*   **Mapping Library:** Leaflet.js (v1.9.4+)
*   **Data Requesting:** D3.js (Data-Driven Documents) or native Fetch API for pulling GeoJSON data
*   **Data Sources:**
    *   [USGS Earthquake Hazards Program](https://earthquake.usgs.gov/earthquakes/feed/v1.0/geojson.php)
    *   [HugoAhlenmorius/tectonicplates](https://github.com/fraxen/tectonicplates) (Tectonic boundary structural data)

---

## Project Structure
```text
leaflet-challenge/
├── Leaflet-Part-1/          # Core files for Part 1 implementation
│   ├── static/
│   │   ├── css/style.css    # Map styles & custom legend rules
│   │   └── js/logic.js      # Main Leaflet setup and API calls
│   └── index.html           # Main view file
├── Leaflet-Part-2/          # Extended files for Part 2 layer addition
│   ├── static/
│   │   ├── css/style.css
│   │   └── js/logic.js      # Advanced logic handling layer groups
│   └── index.html           
└── README.md                # Project documentation

```

---

## Getting Started

1. **Clone the Repository:**
```bash
git clone [https://github.com/talibahnt/leaflet-challenge.git](https://github.com/talibahnt/leaflet-challenge.git)

```


2. **Open the Map:**
Because this project relies exclusively on client-side JavaScript, you do not need to install an expansive backend environment. Simply open the `index.html` file within either directory directly in a web browser, or launch it with a development environment server extension like VS Code's **Live Server**.

```

***

### Pro-Tip for your Repository:
Once you add this file, if you have deployed this project using **GitHub Pages**, you can add a link to the live preview directly at the top of the README or inside the repository's "About" section on the right side of the GitHub UI.

```
