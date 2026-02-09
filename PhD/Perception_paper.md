---
layout: page
title: Perceived Green and Blue Space, Spatial Scale, and Health. A Comparative Assessment of Exposure Metrics
---

 ## Abstract
 Green and blue spaces are known to influence health, yet determining which objec-tive spatial measurements best reflect subjective perceptions remains a methodological challenge. This study systematically evaluates multiple spatial context exposure metrics to assess how well they correspond with perceived green-blue space in residential environments and with self-reported general health. Using data from the Dutch AMIGO cohort (n =3,922), we compared Euclidean buffer models, view-shed analysis, street view imagery, neighbourhood-level aggregations, and distance-to-nearest metrics across multiple green and blue space datasets. Model performance was evaluated using McFadden’s pseudo R² for perceived green-blue space and ordinal regression for general health. Overall, correlations between objective metrics and perceived green-blue space were low to moderate, indicating that commonly used spatial exposure measures capture only a limited share of perceptual variance. Euclidean buffer and viewshed models at 50 m showed the strongest correspondence with perception, while generalized vegetation metrics such as NDVI and aggregated green-blue space con- sistently outperformed categorical land-use datasets. Street view imagery and distance-based measures were least predictive. Associations with general health were strongest for green-blue space metrics within buffer distances of approximately 50–150 m, with models that included blue space showing slight improved performance.



 ## Data
- data on various green space environmental factors including NDVI, parks, land-use areas categorized as green space
- blue space data
- survey answers on green-blue space perception in local surroundings
- street view images

## Methods
- GIS transformations and preparation of data, both for vector a raster datasets 
- Spearman correlation analysis

## Tools
- ArcGIS Pro
- R 

## Outcome
This study evaluated how different spatial representations and measurement methods of green and blue space correspond to perceived environmental quality and general health. Overall, objective spatial metrics explained only a limited proportion of the variance in reported green-blue space perception, indicating that perception cannot be fully captured by commonly used GIS-based exposure models. Nevertheless, consistent patterns emerged across models.

Measures based on generalized vegetation, particularly NDVI and undifferentiated green space, performed better than categorical land-use datasets in approximating perception, especially when combined with blue space. Spatial context mattered: models representing immediate surroundings, most notably Euclidean buffers of approximately 50 m, showed the strongest correspondence with perceived green-blue space, while slightly larger buffers (around 150 m) were more relevant for general health. These findings suggest that commonly applied buffer sizes in exposure research may be too large when the outcome of interest is perception.

The inclusion of blue space systematically improved model performance, highlighting its relevance for both perceived environmental quality and health and underscoring the need to integrate blue space alongside green space in future exposure assessments. At the same time, the modest explanatory power across all models emphasizes that important perceptual dimensions remain unmeasured, whether due to limitations in spatial representations, survey-based perception measures, or both.

By systematically comparing multiple spatial measurement approaches within a single framework, this study clarifies how methodological choices, such as dataset type, spatial scale, and inclusion of blue space, directly influence modelled exposure and its association with perception and health. Future research should focus on refining spatial representations at perceptually relevant scales, incorporating more detailed green and blue space classifications, and integrating contextual information on residential environments. Together, these steps can support the development of more accurate, human-centred, and health-relevant models of green-blue space exposure for research and urban planning.



👉 [View Results →](Perception_paper_results.md)
