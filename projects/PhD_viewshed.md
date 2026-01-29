---
layout: page
title: View-shed analysis of NDVI values around points of interest using a 150 meter buffer
---
*Made for PhD thesis, Utrecht University*
  

![View-shed analysis of NDVI values around points of interest using a 150 meter buffer](../assets/images/PhD_viewshed.png)


## Project description
Perception of green space around a residential area is known to influence health. The view-shed analysis consisted of calculating visible areas within a 150 meter radius for residential addresses throughout the Netherlands. NDVI (greenness) levels within this visible part of the area were then calculated. To determine accuracy of the analysis, results were compared to answers from a survey where participants from the same locations were asked about their perception of greenness in the local surroundings. All buffer centers originated from the street next to a residential address, using a height of 1.7 m, the average height of a person. 


## Data
- residential addresses point dataset
- NDVI raster layers
- elevation raster layer
  

## Methods
Processing methods included snapping each residential address point to the nearest street (as no data was available on orientation of windows in residential addresses). Buffers (radii) of 150 meters were then created around each snapped point. A viewshed analysis for each buffer was performed. Average NDVI values using the view-shed as a mask were then calculated for each buffer. Later analysis compared results to survey answers on local green space perception. 


## Tools
- ArcGIS
- model builder
- R

## Outcome
This view-shed analysis indicted levels of greenery within visible parts from a point of interest.
