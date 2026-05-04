---
layout: page
title: Perceived Green and Blue Space, Spatial Scale, and Health. A Comparative Assessment of Exposure Metrics
---

 ## Abstract
Green and blue spaces are known to influence health, yet determining which objective spatial measurements best reflect subjective perceptions remains a methodological challenge. This study systematically assessed the extent to which different spatial exposure measures correspond with perceived green-blue space and self-reported general health.

We used data from 3,922 participants in the Dutch AMIGO cohort to compare a range of exposure modelling approaches, including Euclidean buffers, view-shed analysis, street-view image metrics, neighbourhood-level aggregation, and distance-to-nearest measures, across multiple green and blue space datasets. Associations between objective green-blue space exposure metrics and perceived green-blue space were assessed using partial Spearman correlations, while associations with self-reported general health were evaluated using proportional odds regression models.  

Objective exposure metrics showed only low to moderate correspondence with perceived green-blue space, with partial Spearman correlations reaching a maximum of 0.49, suggesting that standard GIS-based measures incompletely capture lived environmental experience. The strongest correspondence was observed for Euclidean 50 m buffers and distance-to-the-nearest measures, particularly when using generalized vegetation indicators such as NDVI and all green areas combined with blue space, which consistently outperformed categorical land-use classifications. Associations with general health were modest, with the strongest and most consistent effects observed for \textit{NDVI with blue space} within 50–150 m Euclidean buffers, with the best model fit at 150 m.  

Our findings suggest that small-scale, generalized vegetation-based metrics combined with blue space provide the most useful approximation of perceived green-blue exposure. They underscore the importance of selecting spatial representations and buffer distances that are aligned with perceptual processes when assessing environmental exposure in both environmental health research and urban planning.



 ## Data
- data on various green space environmental factors including NDVI, parks, land-use areas categorized as green space
- blue space data
- street view images
- survey answers on green-blue space perception in local surroundings

## Methods
- GIS transformations and preparation of data, both for vector and raster datasets 
- Partial Spearman correlation analysis
- Proportional odds regression models

## Tools
- ArcGIS Pro
- R 

## Outcome
This study shows that commonly used GIS-based exposure metrics only partially capture perceived green-blue space, highlighting a persistent gap between objective measurement and lived environmental experience. Generalized vegetation metrics, particularly NDVI and undifferentiated green space, consistently outperformed categorical land-use datasets in approximating perceived green-blue space, especially when combined with blue space. Spatial scale was critical: exposure metrics based on immediate surroundings (approximately 50 m Euclidean buffers or distance-to-the-nearest) showed the strongest correspondence with perception, whereas slightly larger buffers (around 150 m) were more relevant for general health.

These findings demonstrate that exposure assessment is highly sensitive to both spatial representation and scale, and that commonly used buffer sizes may not always be appropriate when the outcome of interest is perceived green-blue space.

Based on these findings, several recommendations can be made for future green-blue space exposure research. First, researchers should be aware that information can be lost when transforming between vector and raster formats, and should therefore use high-resolution datasets wherever possible. Second, when studying perceived green-blue space, generalized vegetation datasets appear to be more suitable than categorical land-use classifications. Third, Euclidean buffer models around 50 m appear most appropriate for perceived green-blue space, whereas slightly larger buffers (around 150 m) may be more relevant for general health. Finally, clearer conceptualization of spatial contexts such as “street” and “neighbourhood” is needed, as these may not correspond consistently to how individuals perceive their local environment.

By systematically comparing multiple spatial measurement approaches within a single framework, this study shows that methodological choices directly influence estimated exposure and its observed associations with perceived green-blue space and general health. Similar comparative work is needed for other health outcomes, as the most relevant spatial context may differ depending on the underlying exposure pathway and may not necessarily be driven by perception. In addition, because this study was conducted in the Dutch context, the extent to which these findings generalize to other geographical, environmental, and cultural settings remains to be established. Future research should therefore focus on refining spatial representations, incorporating more detailed blue space classifications, and integrating contextual information on residential environments. Such improvements can support more accurate and human-centred exposure assessment in both environmental health research and urban planning.





👉 [View Results →](Perception_paper_results.md)
