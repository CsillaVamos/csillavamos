---
layout: page
title: PhD overview
---


### Title:  Environmental exposure estimation: How spatial data and measurement methods impact quantifications

**Human Geography and Spatial Planning, Institute of Risk Assessment Sciences; Utrecht University, The Netherlands**  
*In collaboration with the **Exposome NL** project*
*03/2021 – Present*


## Brief Introduction
The environment impacts our health directly and indirectly in countless ways. Examples include air pollution associated with asthma [1–3], traffic noise affecting the ability to concentrate [4–6], crime potentially leading to injuries [7–9], lack of green space associated with poor mental health [10–12], and a lack of grocery stores near residences potentially leading to an unhealthy diet [13–15]. These elements of the environment constitute environmental factors of health. Exposure to such factors over time and in space increases the risk of effects on an individual’s health. The idea of measuring all the possible exposures to such environmental factors an individual experiences in a lifetime, and how those exposures affect health, is called the exposome, a term coined by Wild in [16]. This term was created to complement the genome, to acknowledge that not only do genes, but also the broader non-genetic environment, contribute to health. Wild also recognised the need for methodological developments in exposure assessments, acknowledging that measurement is difficult due to the complex nature of the environment, yet there is a necessity for addressing methodological gaps and improving exposure assessment in epidemiological studies [16]. Methodological investigations of environmental exposure assessments require collaboration between multiple fields, including epidemiologists and specialists for representing and measuring the built environment. Among the latter are geographers as well as geoinformation scientists [17–19]. While epidemiologists are increasingly pursuing studies to understand how the built environment impacts health, understanding the underlying spatial concepts and investigating whether spatial measurements are appropriate for the underlying purpose is done less often, and if so, often not in a systematic manner. In particular, the relationship between concepts of an epidemiological study, their representation in spatial datasets, and possible spatial context measurement methods that are used to quantify exposure has not been investigated comprehensively in terms of their appropriateness for the purposes of measuring the exposome. Researchers tend to adopt standard methods used by previous research instead of exploring different ways to represent the environment [20, 21]. For this reason, it remains to a large extent unknown how the use of different spatial representations and geocomputational methods influences the quality of exposome models.

## Brief Discussion
In environmental epidemiology, the relationships between people, the environment, and exposure have long been recognised. However, few studies have systematically examined the impact of geographic context and spatial methods on these relationships and, ultimately, on epidemiological inference. A key reason for this is the limited interdisciplinary integration between epidemiology and geoinformation science. As a result, it has remained difficult to systematically compare different spatial context measurement methods and spatial representations in terms of their influence on exposure measurements for epidemiological investigations. In this thesis, I proposed an ontology of passive and active exposure that clarifies the different ways in which spatial representations of the environment, activities and exposed persons can be related to each other, based on whether environments are conceptualised as direct or indirect causes of exposure. I also investigated the influence of spatial representations and geocomputational methods on the quality of spatial exposure models. These gaps were addressed by examining and specifying essential concepts (environmental exposure concepts, spatial information concepts, and spatial context measurement methods) and by examining their relationships to each other and how they can be used to model exposure to environmental factors of interest. A diagram showing these essential concepts and how they connect to each other is shown in Figure 6.1. Based on this general model, I designed various geocomputational analyses to test the effects of different spatial representations as well as context measurements over a large range of commonly used environmental factors in epidemiology and exposome research. While these studies were mostly co-variation studies that quantified these effects in terms of correlations between various environmental factors, in the last study (Chapter  5), I also assessed the quality of specific methodological choices regarding spatial context measurement for the purpose of epidemiological studies
using ground truth data on perceived green-blue space. This contributes to a better understanding of the relevance of the combination of spatial representations and spatial context measurements.
Results underscore the importance of considering the type of geospatial representation, spatial context measurement methods, as well as their relationships to epidemiological concepts such as activities, person, location, and the way exposure is quantified.

![overall_thesis_relations](/assets/images/PhD_images/overall_thesis_relations.png)


## Conclusion
This thesis has demonstrated that data characteristics, geospatial concepts, and spatial context measurement methods fundamentally shape exposure modelling in environmental epidemiology. By combining onto-
logical specification of exposure models with systematic empirical analyses, this thesis revealed how variations in spatial data representations and methodological choices of context measurements can substantially
influence exposure estimates. The results emphasise that understanding and explicitly accounting for GIS-related phenomena such as MAUP is essential to achieving reliable exposure assessments. Furthermore, this thesis suggests a conceptual and methodological start for bridging the gap between epidemiology and geoinformation science, underscoring the importance of interdisciplinary integration for advancing exposome research. Ultimately, this work highlights that improved awareness of spatial concepts and their methodological implications leads to more accurate, transparent, and meaningful exposure assessment in environmental epidemiology.


## View papers
👉 [How Spatial Scale and Collinearity Influence Environmental Exposure Models](PhD/Euclidean_buffer_paper.md)

👉 [The role of spatial context definitions for environmental factors](PhD/Network_buffer_paper.md)

👉 [Modelling the perception of green and blue space using different definitions of spatial context](PhD/Perception_paper.md)




## References
1] J. Gasana, D. Dillikar, A. Mendy, E. Forno, and E. Ramos Vieira, “Traffic-related air pollution and asthma in children: a meta-analysis,” Environmental Health, vol. 11, no. 1, p. 31, 2012. https://doi.org/10.1186/1476-069X-11-31.

[2] H. D. Hosgood, Y.-F. Wei, W. Fan, et al., “Outdoor and indoor air pollution and asthma: An update to the literature,” International Journal of Environmental Research and Public Health, vol. 14, no. 11, p. 1284, 2017. https://doi.org/10.3390/ijerph14111284.

[3] J. A. Hutchinson, J. Lepeule, E. A. MacIntyre, et al., “Ambient air pollution exposure and adult asthma incidence: a systematic review and meta-analysis of longitudinal studies,” Environment International, vol. 186, p. 108154, 2024. https://doi.org/10.1016/j.envint.2024.108154.

[4] M. Kaur, S. Kaur, K. Kaur, and M. Kaur, “Effect of road traffic noise on human cognitive performance: an experimental study,” Noise & Health, vol. 17, no. 74, pp. 227–231, 2015. https://doi.org/10.4103/1463-1741.165057.

[5] F. K¨arrholm-Fauser, D. Hjortebjerg, J. Gyllenborg, M. Ketzel, C. Backalarz, O. Raaschou-Nielsen, S. S. Jensen, and M. Sorensen, “Road traffic noise and children’s inattention,” Environmental Health, vol. 16, no. 1, pp. 1–9, 2017. https://doi.org/10.1186/s12940-017-0273-x.

[6] L. P´erez-Crespo, P. Dadvand, D. Donaire-Gonz´alez, M. Cirach, X. Basaga˜na, M. Nieuwenhuijsen, and J. Forns, “Residential exposure to traffic noise is associated
with reduced concentration in adolescents: a 1-year follow-up study,” Environmental Research, vol. 244, p. 117660, 2024. https://doi.org/10.1016/j.envres.2024.117660.

[7] R. M. Lynn, D. M. MacGregor, L. Condon, T. O’Neill, and J. R. Sibert, “Household and neighbourhood risks for injury to 5–14 year old children,” Archives of Disease in Childhood, vol. 88, no. 6, pp. 510–516, 2003. https://doi.org/10.1136/adc.88.6.510.

[8] A. Curtis, B. Cave, D. Versel, and D. Smith, “Assault injury rates, social capital, and fear of neighborhood crime,” Journal of Urban Health, vol. 84, no. 3, pp. 379–388, 2007. https://doi.org/10.1007/s11524-007-9183-5.

[9] B. B. Walker, N. Schuurman, S. M. Hameed, and J. Lecker, “A multilevel analysis of the socio-spatial pattern of assault injuries in greater vancouver, bc,” Health & Place, vol. 15, no. 3, pp. 718–730, 2009. https://doi.org/10.1016/j.healthplace.2008.11.005.

[10] K. M. Beyer, A. Kaltenbach, A. Szabo, S. Bogar, F. J. Nieto, and K. M. Malecki, “Exposure to neighborhood green space and mental health: Evidence from the survey of the health of wisconsin,” International Journal of Environmental Research and Public Health, vol. 11, no. 3, pp. 3453–3472, 2014. https://doi.org/10.3390/ijerph110303453.183

[11] K. Engemann, C. B. Pedersen, L. Arge, C. Tsirogiannis, P. B. Mortensen, and J.-C. Svenning, “Residential green space in childhood is associated with lower risk of psychiatric disorders from adolescence into adulthood,” Proceedings of the National Academy of Sciences, vol. 116, no. 11, pp. 5188–5193, 2019. https://doi.org/10.1073/pnas.1813050116.

[12] X. Zhu, M. Fu, Y. Liu, Y. Wang, H. Liu, and Y. Yao, “Green space exposure on depression and anxiety outcomes: A meta-analysis of observational studies,” Environmental Research, vol. 220, p. 115144, 2023. https://doi.org/10.1016/j.envres.2022.115144.

[13] K. Morland, S. Wing, A. Diez Roux, and C. Poole, “The contextual effect of the local food environment on residents’ diets: the atherosclerosis risk in communities study,” American Journal of Public Health, vol. 92, no. 11, pp. 1761–1768, 2002. https://doi.org/10.2105/AJPH.92.11.1761.

[14] L. M. Powell, S. Slater, D. Mirtcheva, Y. Bao, and F. J. Chaloupka, “Food store availability and neighborhood characteristics in the united states,” Preventive Medicine, vol. 44, no. 3, pp. 189–195, 2007. https://doi.org/10.1016/j.ypmed.2006.08.008.

[15] B. Ghosh-Dastidar, D. A. Cohen, G. Hunter, S. Zenk, C. Huang, R. Beckman, and T. Dubowitz, “Distance to store, food prices, and obesity in urban food deserts,” American Journal of Preventive Medicine, vol. 47, no. 5, pp. 587–595, 2014. https://doi.org/10.1016/j.amepre.2014.05.007.

[16] C. P. Wild, “Complementing the genome with an “exposome”: the outstanding challenge of environmental exposure measurement in molecular epidemiology,” Cancer Epidemiology Biomarkers & Prevention, vol. 14, no. 8, pp. 1847–1850, 2005. https://doi.org/10.1158/1055-9965.EPI-05-0456.

[17] R. C. Sadler and K. Larsen, “Mapping the way to good health: The interdisciplinary challenges of geographers in medical research,” International Journal of Environmental Research and Public Health, vol. 19, no. 19, p. 12419, 2022. https://doi.org/10.3390/ijerph191912419.

[18] M. F. Vine, D. Degnan, and C. Hanchette, “Geographic information systems: their use in environmental epidemiologic research.,” Environmental health perspectives, vol. 105, no. 6, pp. 598–605, 1997. https://doi.org/10.1289/ehp.97105598.

[19] P. Jia, J. Lakerveld, J. Wu, A. Stein, E. D. Root, C. E. Sabel, R. Vermeulen, J. V. Remais, X. Chen, R. C. Brownson, et al., “Top 10 research priorities in spatial life course epidemiology,” Environmental health perspectives, vol. 127, no. 7, p. 074501, 2019. https://doi.org/10.1289/EHP4868.

[20] M.-P. Kwan, “The uncertain geographic context problem,” Annals of the Association of American Geographers, vol. 102, no. 5, pp. 958–968, 2012. https://doi.org/10.1080/00045608.2012.687349.

[21] P. James, D. Berrigan, J. E. Hart, J. A. Hipp, C. M. Hoehner, J. Kerr, J. M. Major, M. Oka, and F. Laden, “Effects of buffer size and shape on associations between the built environment and energy balance,” Health & place, vol. 27, pp. 162–170, 2014. https://doi.org/10.1016/j.healthplace.2014.02.003.

