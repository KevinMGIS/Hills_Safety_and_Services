---
layout: default
title: Community Services Map Projects
---

[View Hillsborough County Services Map](https://kevinmgis.github.io/Hills_Safety_and_Services/map.html)  
[View Pasco County Services Map](https://kevinmgis.github.io/Pasco_Service_Visualization/map.html)

# Community Services Map Projects

This site showcases two interactive web maps that visualize community services in two different counties using different technologies.

## Hillsborough County Services Visualization

The Hillsborough County Services Visualization project displays multiple service layers—including Fire Stations, Hospitals, Libraries, Schools, and Bus Stops—on a custom Leaflet map. This project was built entirely with open source tools. It features:
  
- A custom basemap with a switcher (allowing users to choose between various open source basemaps such as Positron, Dark Matter, and OpenStreetMap).
- Multiple data layers loaded as clustered markers with custom icons.
- An interactive legend that toggles layer visibility.
- Two dynamic charts (a pie chart showing counts within the current view and a bar chart showing overall counts).
- Additional controls such as a scale bar and a coordinate display.

This solution demonstrates the flexibility and power of open source mapping libraries and techniques, offering a rich, data-driven visualization of key community facilities in Hillsborough County.

## Pasco County Services Map

In contrast, the Pasco County Services map was developed using the ArcGIS API for JavaScript. This project similarly displays service layers for Pasco County but leverages the extensive functionality provided by the ArcGIS platform. Key features include:

- A robust and feature-rich basemap from Esri with high-quality cartography.
- Data layers and features seamlessly integrated using the ArcGIS API, which offers advanced spatial analysis and querying capabilities.
- Built‑in interactive widgets and controls from the ArcGIS ecosystem that provide a streamlined user experience.
- A different development approach that leverages Esri's extensive libraries, simplifying some aspects of the integration while providing powerful mapping and analysis tools.

## Comparison of Methods

The two projects illustrate different approaches to building interactive web maps:

- **Open Source (Hillsborough County):**  
  - Offers complete control over styling, data integration, and functionality.
  - Involves combining multiple open source libraries (Leaflet, MarkerCluster, Chart.js, etc.) to create a tailored solution.
  - Provides flexibility in customizing every aspect of the map and its interactivity.

- **ArcGIS API for JavaScript (Pasco County):**  
  - Leverages a comprehensive, ready-to-use mapping platform with high-quality basemaps and built‑in tools.
  - Simplifies complex tasks such as spatial analysis, data integration, and widget deployment.
  - Reduces development time by using Esri’s extensive libraries and services.

Both methods have their advantages. The open source approach allows for maximum customization and is ideal for projects that require a bespoke user experience, while the ArcGIS API offers a powerful, integrated environment that can speed up development and take advantage of Esri’s mapping expertise.

## Conclusion

The projects evolved from a basic mapping solution to comprehensive interactive visualizations. The final solutions include:
- A custom, switchable basemap.
- Clustered markers with custom icons for various service layers.
- An interactive legend for easy layer management.
- Dynamic pie and bar charts that update in real time.
- Additional controls such as a scale bar and a coordinate display.

These projects demonstrate the effective use of open source tools and the ArcGIS API to create rich, interactive mapping applications that provide valuable insights into community services.