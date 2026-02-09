---
layout: page
title: The role of spatial context definitions for environmental factors
---

 ## Abstract
Various aspects of our environment, such as air pollution and green space, must be quantified to assess their impact on health. For instance, air pollution contributes to chronic diseases like asthma, while physical activity reduces cardiovascular risk. To capture interactions between individuals and their environment, researchers define spatial contexts for both passive (e.g., air pollution, safety) and active exposures (e.g., walkability). While epidemiologists have examined health impacts of such exposures, less attention has been given to how the definition of spatial context, including data models, resolution, and measurement methods such as network or Euclidean buffers may influence results. We investigate how correlations within and between 84 environmental factors (EFs) among individuals at residential addresses vary by spatial context definition. Specifically, we compare Euclidean and network buffers with radii of 100, 250, 500, and 1000 meters. Results show that Pearson correlation values differed by 0.3 or more for many of the 3,486 variable pairs across buffer sizes. Moreover, several EF correlations exhibited large significant effect differences (greater than 0.3 or less than –0.3) in 10 or more cases. These findings demonstrate that the choice of spatial context definition alone can substantially alter correlation structures, affecting variable selection, clustering, and mixture analyses in epidemiology. Additionally, spatial context measurement models and their resolution play a critical role, underscoring the importance of methodological choices in environmental health research, regardless of location.


 ## Data
Open access data on various environmental factors including air pollution, green space, blue space, education level, crime, location of food facilities


## Methods
- GIS transformations and preparation of data, both for vector a raster datasets 
- Pearson correlation analysis

## Tools
- ArcGIS Pro
- R 

## Outcome
This study highlighted the importance of distinguishing the effects of spatial context measurement methods from the effects of the phenomenon being measured when assessing EFs, with a focus on distinguishing between network and Euclidean context definitions under various representations of the environment.  Some EFs exhibited significant changes in correlation based on the chosen measurement method, due to data characteristics (spatial type, resolution). These findings underscore the significance of selecting appropriate models and demonstrate how data characteristics can influence results. Variations in Pearson correlation values emphasized the impact of a quantification approach on exposure assessment, demonstrating the importance of careful consideration of EF characteristics during exposure assessment method selection. The impact of changes in correlation structures in discovery-based epidemiological analyses can be substantial. For example, in multi-variable approaches for variable selection (e.g., lasso regression), cluster analyses (e.g., partial least squares), or mixture analyses (e.g., Bayesian Kernel Machine Regression), penalization and optimization are dependent on these structures. Consequently, the outcomes of such analyses could be significantly affected by the choice of environmental context measures and data characteristics. This study sheds light on this issue, and demonstrates how different results can be based on data and model characteristics, suggesting careful consideration of spatial data and models for environmental epidemiological exposure analysis.


👉 [View Results →](Network_buffer_paper_results.md)

