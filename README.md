# NYC Free WiFi Location Analysis

## Overview
This project visualizes the locations of free WiFi hotspots in New York City using interactive maps. The dataset includes details like provider, borough, and WiFi type.

## Features
- **Interactive Maps:**
  - Folium map displaying WiFi locations.
  - Custom Mapbox styles for enhanced visualization.
- **GeoJSON Export:**
  - WiFi location data is saved in a `ny.geojson` file for further analysis.

## Technologies Used
- Python libraries: `folium`, `numpy`, `pandas`, `requests`, `matplotlib`, `geopandas`, `geojson`, `simplejson`
- Data: NYC Open Data API
- Mapbox for advanced map styles

## Installation & Usage
1. Install dependencies:
   ```sh
   pip install folium numpy pandas requests matplotlib geopandas geojson
   ```
2. Run the script in Jupyter Notebook or Python.
3. View the generated interactive map.

## Notes
- Requires a valid Mapbox token for custom map styles.
- The dataset is fetched from an NYC Open Data API.

## Author
Bonilkumar Tailor

