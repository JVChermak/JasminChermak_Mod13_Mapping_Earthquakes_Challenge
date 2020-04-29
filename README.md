# Mapping Earthquakes

## Overview of the Project
The purpose of the project is to use a map to visually display the differences between magnitudes of earthquakes all over the world for the last seven days. To complete this project, the following was completed.

1. Use a URL for GeoJSON earthquake data from the USGS website and retrieve geographical coordinates and the magnitudes of earthquakes for the last seven days.
2. Use JavaScript and D3.js libraries to retrieve the coordinates and magnitudes from the GeoJSON data.
3. Use the Leaflet library to plot the data onto a Mapbox map through an API request.
4. Create interactivity for the earthquake data with styling dependent on the magnitude.
5. Use d3.json() to retrieve GeoJSON tectonic plate data.
6. Create a tectonic plate layer and overlay for the map.
7. Use three options for the base layer: street, satellite, dark

## Resources
- Data Source: (earthquake data) https://earthquake.usgs.gov/earthquakes/feed/v1.0/summary/all_week.geojson; (tectonic plates) https://raw.githubusercontent.com/fraxen/tectonicplates/master/GeoJSON/PB2002_boundaries.json
- Software: JS, D3, Leaflet
- Mapbox with API for map

## App
The map loads with the street view, earthquake circles and tectonic plates showing. Selecting any circle will display more information about the earthquake. When selecting the upper right menu, you have the option to change the base map to satellite or dark mode. You can also remove the earthquake or tectonic plate layers.
![Earthquake map in action](images/earthquake_demo.gif)
