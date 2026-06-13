---
title: "Hybrid objective model (IDOCRIW-CoCoSo) optimizes groundwater potential"
excerpt: "Graphical abstract <br/><img src='/images/portfolio/Idocriw_cocoso/1.PNG'>"
collection: portfolio
---
---
# Description
Published work, Cleaner Water (2026) [Link](https://www.sciencedirect.com/science/article/pii/S2950263226000694) 

---
# Highlights 
- Applied Integrated Determination of Objective Criteria Weights-Combined Compromise Solution (IDOCRIW-CoCoSo) multi-criteria decision-making approach.

- Utilized remote sensing and geophysical conditioning datasets for the modelling.

- Used other objective models (CRITIC-CoCoSo, and Mean Weighted CoCoSo) as comparative tools. 

---
# Abstract
Groundwater is a valuable asset in both urban and rural areas, where the demand for alternate water sources is increasing—a vital resource for agriculture, industry, and domestic. Assessment of this resource becomes paramount globally and especially in areas where fresh water demand is rising despite falling within a multi-faceted geologic environment—rendering its sustainable management a pressing concern. To address this issue, an Integrated Determination of Objective CRIteria weights–Combined Compromise Solution (IDOCRIW-CoCoSo) was developed by integrating five groundwater potential influencing factors sourced from remote sensing and geophysical datasets. This will increase the prospect of finding productive aquifers and maximize the choice of drilling sites. The results were contrasted with two other hybrid objective modelling approaches, including CRiteria Importance Through Intercriteria Correlation–Combined Compromise Solution (CRITIC-CoCoSo), and Mean Weighted (MW) - CoCoSo. The groundwater potential map produced, classified into five classes, showed that 6% (113 km²), 26% (486 km²), 32% (603 km²), 26% (473 km²), and 10% (192 km²) fall into very low, low, medium, medium high, and high potentiality, respectively. The obtained results were confirmed using the receiver operating characteristic (ROC) curve and sensitivity analysis. According to the area under the ROC curve, the IDOCRIW-CoCoSo had a success rate of 83%, compared to MW- CoCoSo with an area under the curve (AUC) of 75% and CRITIC-CoCoSo (69%). The findings demonstrate IDOCRIW-CoCoSo's higher accuracy in predicting groundwater potential zones. For the sustained development and management of water-scarce areas, this study offers scientific perspective into the sustainability, distribution and governance of groundwater assets.

---
# Methodology
Conditioning factors maps have been generated using ArcGIS 10.8.2 software. Python programming coded objective models were applied to the groundwater potential decision matrix gotten through fishnet points extraction of pixel values from the factors maps. Interpolation technique was used to create groundwater potential maps of the study area taking groundwater potential indices from models as input. Several reliability and comparative analysis iincluding sensitivity analysis as well as multicollinearity testing were adopted.

<figure>
  <img src= "/images/portfolio/Idocriw_cocoso/5.PNG" alt="Methodology Flowchart">
  <figcaption><em>Methodology Flowchart</em></figcaption>
</figure>

---
# Findings 

## The produced groundwater potential map (IDOCRIW-CoCoSo) is advantageous in meeting SDG 6.1 goals in the study area
<figure>
  <img src= "/images/portfolio/Idocriw_cocoso/9.jpg" alt="Study area location map">
  <figcaption><em>Study area map</em></figcaption>
</figure>

<figure>
  <img src= "/images/portfolio/Idocriw_cocoso/2.jpg" alt="Groundwater potential map (IDOCRIW-CoCoSo">
  <figcaption><em>Groundwater Potential Map (IDOCRIW-CoCoSo)</em></figcaption>
</figure>

## IDOCRIW-CoCoSo showed impressive AUC-score compared to CRITIC and Mean Weighted CoCoSo
<figure>
  <img src= "/images/portfolio/Idocriw_cocoso/10.jpg" alt="ROC-Curve for IDOCRIW-CoCoSo">
  <figcaption><em>ROC-Curve for IDOCRIW-CoCoSo</em></figcaption>
</figure>

<figure>
  <img src= "/images/portfolio/Idocriw_cocoso/11.jpg" alt="ROC-Curve for CRITIC-CoCoSo">
  <figcaption><em>ROC-Curve for CRITIC-CoCoSo</em></figcaption>
</figure>

<figure>
  <img src= "/images/portfolio/Idocriw_cocoso/12.jpg" alt="ROC-Curve for Mean Weighted-CoCoSo">
  <figcaption><em>ROC-Curve for Mean Weighted-CoCoSo</em></figcaption>
</figure>

## Comparative and hydrogeological analysis further elaborated the supremacy and efficacy of IDOCRIW-CoCoSo model for groundwater potential mapping

<figure>
  <img src= "/images/portfolio/Idocriw_cocoso/3.png" alt="Bootstrapped AUC result of the models">
  <figcaption><em>Bootstrapped AUC result used as a form of computational efficiency assessment of the models</em></figcaption>
</figure>

<figure>
  <img src= "/images/portfolio/Idocriw_cocoso/7.PNG" alt="Sensitivity analysis of IDOCRIW-CoCoSo">
  <figcaption><em>Sensitivity analysis of IDOCRIW-CoCoSo</em></figcaption>
</figure>

<figure>
  <img src= "/images/portfolio/Idocriw_cocoso/8.png" alt="Heatmap of IDOCRIW-CoCoSo model">
  <figcaption><em></em>Heatmap of IDOCRIW-CoCoSo model demonstrating the stability of its outputs across the fishnet locations during scenario analysis</figcaption>
</figure>

<figure>
  <img src= "/images/portfolio/Idocriw_cocoso/13.jpg" alt="IDOCRIW-CoCoSo groundwater potential map indicating correlating regions with overburden thickness map">
  <figcaption><em></em>IDOCRIW-CoCoSo groundwater potential map indicating correlating regions (black circle) with overburden thickness map</figcaption>
</figure>

<figure>
  <img src= "/images/portfolio/Idocriw_cocoso/14.jpg" alt="Overburden thickness map showing correlating regions with IDOCRIW-CoCoSo groundwater potential map ">
  <figcaption><em></em>Overburden thickness map showing correlating regions (black circles) with IDOCRIW-CoCoSo groundwater potential map</figcaption>
</figure>