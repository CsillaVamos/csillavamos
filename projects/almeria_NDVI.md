---
layout: page
title: Change in greenness in Almería, Spain
---

# Change in greenness in Almería, Spain

*-	Made for the course Geo Scripting, Wageningen University and Research*

![Change in greenness in Almería, Spain](../assets/images/almeria_NDVI.png)

## Project description
Almería, Spain, consists of mainly desert, yet it is also one of the nation’s largest food producers. Therefore, it is important to monitor changes in vegetation in this area, and this interactive tool allows for this. 

By selecting different time periods in the GUI, one can see how vegetation has increased, decreased, or stayed constant throughout different years and seasons. The top and middle map shows the amount of vegetation for two separate time periods. The bottom map shows the change of vegetation between those two time periods. 

## Data
Landsat 5 and Landsat 8 satellite images. The same tile was selected for different seasons and years. This tile was then later cropped in R to only show the area of interest (a section of Almería, Spain).

## Methods
-This digital tool was created using LeafLet, which is used to build web mapping applications. 
-The maps and the graph were programed to successfully select and visualize change in greenness based on the user’s time period of interest. 
-Plotly, Shiny, and Raster packages were also used to construct this interactive tool. 
-The code was created in R, where the data folder is created in the script, then the NDVI (determines greenness) and crop (selects the study area) functions are called to implement and select appropriate data. 
-A data prep script is then also called, and finally, the App (in LeafLet) is called.


## Tools
- Leaflet
- R 

## Outcome
Interactive map showing changes in vegetation (NDVI) in Almería, Spain.
