---
layout: default
title: Hillsborough Community Map Project
---

[View the Interactive Map](map.html)

# Hillsborough County Services Visualization

**Hillsborough County Services Visualization** is a portfolio project that displays multiple service layers—including Fire Stations, Hospitals, Libraries, Schools, and Bus Stops—on an interactive Leaflet map. The project uses fully open source tools to develop a rich, data-driven visualization of key community facilities in Hillsborough County.

## Project Overview

The final solution of the project integrates several advanced features:
- **Custom Basemap with Switcher:** Users can choose between different open source basemaps (for example, Positron, Dark Matter, and OpenStreetMap) via a dropdown control.
- **Clustered Data Layers with Custom Icons:** Multiple service layers are loaded as clustered markers. Custom icons represent each category, enhancing visual clarity even in areas with high marker density.
- **Interactive Legend:** An interactive legend is positioned on the map, displaying an icon and label for each service type. Clicking on a legend item toggles the visibility of the corresponding layer.
- **Dynamic Charts:** Two interactive charts are incorporated:
  - A **Pie Chart** displays counts of markers within the current map view for active layers.
  - A **Bar Chart** shows overall counts for active layers, independent of the current view.
- **Additional Controls:** A scale bar and a coordinate display provide further context, showing the current map scale and the mouse coordinates as the user moves over the map.

## Development Process

**Phase 1: Map Setup with Leaflet**  
A basic Leaflet map was established using an open source OSM-based basemap. The map was centered on Hillsborough County at an appropriate zoom level to clearly present regional services.

**Phase 2: Custom Icons and Marker Clustering**  
Custom icons were created for each service category. Each service layer’s GeoJSON data was loaded into a clustering group to manage high volumes of markers. This approach improved the map’s readability and performance.

**Phase 3: Interactive Legend**  
An interactive legend was designed to allow users to toggle the visibility of individual layers directly from the map interface. The legend was dynamically generated based on an array of layer properties, and its appearance (such as opacity) indicated whether a layer was active.

**Phase 4: Dynamic Interactive Charts**  
Two charts were integrated to provide visual summaries of the data:
- The **Pie Chart** updates to reflect the number of markers currently visible on the map for each active service layer.
- The **Bar Chart** displays overall counts for each active service layer, regardless of the current map view.
Both charts refresh dynamically as users move around the map or toggle layers using the legend.

**Phase 5: Additional Interactive Controls**  
Additional controls were added to enhance user interactivity:
- A **Basemap Switcher** enables users to swap between different basemap styles.
- A **Coordinate Display** shows current mouse coordinates, while a built‑in scale bar provides context for distances on the map.

## Conclusion

This project evolved from a simple Leaflet map to a comprehensive interactive visualization of community services. The final solution showcases:
- A custom, switchable basemap.
- Clustered markers with custom icons for various service layers.
- An interactive legend for easy layer management.
- Dynamic pie and bar charts that update in real time.
- Additional controls such as a scale bar and a coordinate display.

The project demonstrates the effective use of open source tools to create a rich, interactive mapping application that provides valuable insights into community resources in Hillsborough County.