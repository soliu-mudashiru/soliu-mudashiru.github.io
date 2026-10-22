---
title: "Catastrophe theory (CT) outperformed AHP model in landslide susceptibility mapping"
excerpt: "Study area map <br/><img src='/images/portfolio/catastrophe_landslide/1.png'>"
collection: portfolio
author_profile: false
---
---
# Description
_Published work - Discover Geosciences (2026). [Link](https://link.springer.com/article/10.1007/s44288-026-00770-5)_

---
# Highlights 
- A combination of surface and subsurface geodata, including geoelectrical, geological, and remote sensing datasets, is compiled to develop the landslide susceptibility models.
- Employs Catastrophe Theory (CT) and Analytical Hierarchy Process (AHP) frameworks to generate spatial susceptibility maps from nine conditioning factors.
- Spatial mapping reveals zones of moderate to very high susceptibility that align with documented landslide locations in the Okemesi–Ekiti area, southwestern Nigeria.
- Validation using landslide inventory and AUC analysis demonstrates higher predictive accuracy for the CT model (74%) compared to the AHP model (63%).
- The CT–based model is recommended as a robust and less subjective approach for landslide hazard assessment, supporting targeted mitigation and land-use planning.

---
# Abstract
Landslides are among the most destructive natural hazards in mountainous and structurally complex terrains, posing significant threats to lives, infrastructure, and sustainable development. Accurate Landslide Susceptibility Mapping (LSM)  is therefore essential for hazard mitigation and land-use planning. This study develops a Catastrophe Theory (CT)-based Landslide Susceptibility Mapping Index 
(LSMI) that integrates surface and subsurface conditioning factors derived from geological, geomorphological, geophysical, and climatic datasets. Unlike conventional approaches that rely primarily on expert judgment or data-intensive machine learning algorithms, the proposed framework employs Catastrophe Theory and fuzzy membership transformation to derive factor weights through catastrophe normalization functions, thereby reducing subjectivity in the weighting process. Nine landslide conditioning factors, including slope, elevation, lithology, rainfall, lineament density, drainage density, transverse resistance, coefficient of anisotropy, and bedrock topography, were integrated within a GIS environment to generate a CT-based susceptibility model and compared with an Analytical Hierarchy Process (AHP)-based model. The results revealed distinct factor-ranking patterns between the two approaches, reflecting their different weighting philosophies. While AHP emphasized surface geomorphological controls, particularly slope, CT assigned the highest weight to transverse resistance, highlighting the influence of subsurface weathering, groundwater conditions, and rock competence on slope instability. The resulting susceptibility maps were classified into five categories and validated using 
landslide inventory data and Receiver Operating Characteristic (ROC) analysis. The CT model achieved an Area Under the Curve (AUC) value of 0.74, outperforming the AHP model (AUC = 0.63). These findings demonstrate that integrating subsurface geophysical information with Catastrophe Theory provides a promising complementary framework for landslide susceptibility assessment in structurally complex Basement Complex terrains, although further validation in different geological settings is recommended.

---
# Methodology
Landlslide conditioning factors (LCFs) were sourced from remotely sensed and geophysical information. These factors were harmonized within ArcGIS environment to ensure spatial compatibility and coherence prior to moodelling. On one arm, catastrophe theory that integrated fuzzy membership transformation was utilized to compute objective weight of these factors and used to produce the landslide map of the study area. On the other arm, AHP model which is a subjective–driven data mining model and largely driven by experts response based on Saaty scale, 5–point calibration (1–3-5–7-9) was also deployede to model landslide occurrence. The results of these two models were independently validated using landslide occurrence record of Oke-Imesi, Ekiti State, Nigeria. Area under the curve of receiver operating characteristics (AUC-ROC) of the validation was plotted to comparatively assess the modelling abilities of these models viz-a-viz to highlight the better performing model. 
  
<figure>
  <img src= "/images/portfolio/catastrophe_landslide/2.png" alt="Methodology flowchart">
  <figcaption><em>Methodology Flowchart</em></figcaption>
</figure>

<figure>
  <img src= "/images/portfolio/catastrophe_landslide/3.png" alt="Ground truth data acquisition map">
  <figcaption><em>Ground truth data acquisition map</em></figcaption>
</figure>

<figure>
  <img src= "/images/portfolio/catastrophe_landslide/4.png" alt="Obervation points employed for model computations">
  <figcaption><em>Obervation points employed for model computations</em></figcaption>
</figure>

<figure>
  <img src= "/images/portfolio/catastrophe_landslide/5.png" alt="Information about the data sources">
  <figcaption><em>Information about the data sources</em></figcaption>
</figure>

---
# Findings 

## CT elaborated transverse resistance (TR) as the highly weighted factor whereas AHP model identified slope as the predominant indicator

<figure>
  <img src= "/images/portfolio/catastrophe_landslide/6.png" alt="Transverse resistance map">
  <figcaption><em>Transverse resistance map</em></figcaption>
</figure>

<figure>
  <img src= "/images/portfolio/catastrophe_landslide/7.png" alt="Slope map">
  <figcaption><em>Slope map</em></figcaption>
</figure>

## CT and AHP based models showed spatial occurrence of landslide susceptibility in the study area
While CT partitioned 47.28% (4.18 km-sq) of the study area into very and low susceptibility regions, AHP showed a combined percentage of 35.1% (4.10 km-sq). In addition, CT as well as AHP models partitioned approximately 28.87% (4.64 km-sq) and 36.7% (4.28 km-sq) into the combined high and very high regions. The two models elaborated that, 23.85% (2.85 km-sq) and 28.2% (3.29 km-sq) fall within the moderate landslide susceptibility region. By overlaying landslide inventory on the two spatial maps, it has been revealed that, both models gave appropriate insights into the landslide occurrence of the study area

<figure>
  <img src= "/images/portfolio/catastrophe_landslide/8.png" alt="CT based landslide susceptibility map">
  <figcaption><em>CT based landslide susceptibility map</em></figcaption>
</figure>

<figure>
  <img src= "/images/portfolio/catastrophe_landslide/9.png" alt="AHP based landslide susceptibility map">
  <figcaption><em>AHP based landslide susceptibility map</em></figcaption>
</figure>

<figure>
  <img src= "/images/portfolio/catastrophe_landslide/10.JPG" alt="Visualization of the area coverage">
  <figcaption><em>Visualization of the area coverage</em></figcaption>
</figure>

## AUC-ROC validation showed CT outperformed AHP model in landslide modelling

<figure>
  <img src= "/images/portfolio/catastrophe_landslide/11.png" alt="AUC-ROC of the catastrophe landslide model">
  <figcaption><em>AUC-ROC validation of the catastrophe landslide model</em></figcaption>
</figure>

<figure>
  <img src= "/images/portfolio/catastrophe_landslide/12.png" alt="AUC-ROC of the AHP landslide model">
  <figcaption><em>AUC-ROC validation of the AHP landslide model</em></figcaption>
</figure>