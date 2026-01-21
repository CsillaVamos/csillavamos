---
layout: page
title: Suitable Locations for Weather Stations in the Amazonía Region of Ecuador
---

*Made for the course Advanced Geo-information Science for Earth and Environment, Wageningen University and Research*


![Suitable Locations for Weather Stations in the Amazonía Region of Ecuador](../assets/images/weather_station_suitability.png)


## Project description
The objective was to determine suitable locations for weather stations, taking into account accessibility and representation of different climate conditions. 

In this region only seven weather stations currently exist and are located along the border of the region. Because the Amazonía Region mainly consists of rainforest, several factors were taken into account to determine optimal areas. Proximity to roads, rivers, settlements, steepness of slopes, and land use types were all considered when determining accessibility. Stations are placed throughout the entire region so that they are representative of the different climate conditions of the Amazonía region. Accessibility is taken into account.  


## Data
-seasonal precipitation sum, precipitation zones
-NDVI
-atmospheric water vapour
-soil humidity 
-average cloud fraction, monthly average cloud temperature
-vector maps of roads, rivers, and settlements


## Methods
-To determine areas that are most accessible, various operations on appropriate datasets (shapefiles and a DEM) were performed using model builder in ArcGIS. 
-To determine which of the suitable areas are representative of regional climates, conditional Latin Hypercube sampling (cLHS, a sampling method that preserves as much input data variability as possible) was used. 
-Within ArcGIS, tools were used to combine datasets, classify, determine color schemes, and determine map design. 


## Tools
- ArcGIS
- 

## Outcome
Identifies suitable locations to build new weather stations, taking into account accessibility and representation of different climate conditions. 
