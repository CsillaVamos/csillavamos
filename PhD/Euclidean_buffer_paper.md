---
layout: page
title: How Spatial Scale and Collinearity Influence Environmental Exposure Models
---

 ## Abstract
 Exposure research has primarily focused on effects of a single environmental factor or related environmental factors, as well as a single way of spatially measuring exposure. It has seldom been investigated how exposure variation is affected by different methodical choices across various types of environmental factors. In this study, we investigate to what extent exposure assessments are affected by the spatial measurement method (different Euclidean buffer sizes) and by how exposure is quantified across different groups of environmental factors. The co-variance of different measurements of exposure to different environmental factors (a total of 84) are studied, in particular, how sensitive correlations are with respect to varying buffer sizes and reasons why this could be. Results show that correlation (and multicollinearity) is heavily affected by the choice of factors and by how they were measured. Strong correlations were observed among key indicators like NO2, PM2.5, and Population density, emphasizing their influence on urban livability. This study highlights the importance of considering the size of the study area when analyzing correlations between environmental factors, as these choices significantly impact results.  Future research should account for spatial measurement methods, spatial phenomena such as  MAUP, as well as a ground-truth to better assess environmental exposure and multicollinearity in different urban contexts.



 ## Data
Open access data on various environmental factors including air pollution, green space, blue space, education level, crime, location of food facilities


## Methods
- GIS transformations and preparation of data, both for vector a raster datasets 
- Pearson correlation analysis

## Tools
- ArcGIS Pro
- R 

## Outcome
This study examined how correlations between environmental factors vary depending on spatial context definitions (varying Euclidean buffer sizes). In order to estimate effects of exposure of environmental factors, we first need to take into account the effects of spatial representations (how the environment is represented), and the spatial context definition (in this study, buffer size). Doing so allows us to separate the effects of methodical choices on exposure assessment. While notable findings regarding the change in correlation with the environmental factors were identified, the emphasis was on understanding _why_ certain correlation patterns occurred, in relation to environmental factor characteristics, dataset characteristics, spatial phenomena such as MAUP, and spatial measurement choices. 

The results showed that Euclidean buffer size substantially affected certain environmental factors and their correlations. Several environmental factors exhibited consistently high within-group correlations, indicating strong multicollinearity.  Some consistent cross-category relationships appeared (e.g., between the Physico-chemical and Built categories), while environmental factors in the Food categories showed weak associations with other categories. Spatial phenomena such as ecological fallacy, spatial resolution mismatches, and MAUP can contribute to misleading correlations and should be explicitly considered when interpreting exposure models. Additionally, it is worth examining whether results are due to spatial phenomena or characteristics in the environment.

Overall, this study demonstrates that exposure assessment is highly sensitive to choices in spatial representation of environmental factors and spatial context definition. Future work should develop guidelines that take into account characteristics of environmental factors, data spatial representation, and spatial context definition, ideally validated against ground-truth sources such as sensor-based measurements or health surveys. Careful consideration of these methodological factors is necessary to avoid misinterpretation of results and to improve the reliability of  exposure findings.

👉 [View Results →](Euclidean_buffer_paper_results.md)


## Results
![INSERTNAME](../assets/images/INSERTNAME.png)

