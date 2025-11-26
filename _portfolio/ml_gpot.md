---
title: "ML algorithms for groundwater sustainability in a data scarce region"
excerpt: "Study area <br/><img src='/images/portfolio/ml_gpot/1.PNG'>"
collection: portfolio
---

**Description** Excerpt from under review work (2025). 

### Highlights 
- Fishnet approach have been used to derive data partitioning for the ML modelling.

- Multicollinarity detection was employed to select the most suitable remote sensing parameters.

- ML algorithms (SVM, RF, xGBoost, AdaBoost) have been utilized and compared with AHP model for their groundwater sustainability predictive abilities. 

- The result demonstrated the abilities of data driven approaches in partitioning groundwater locations for its sustainability even in data scarce region

<figure>
  <img src= "/images/portfolio/ml_gpot/2.PNG" alt="Fishnet location template">
  <figcaption><em>Fishnet location used to extract values of influencing variables into the modelling. It was also adopted in selecting appropriate target points from the borehole yield map which served as the spatial representation of the target variable in the study region </em></figcaption>
</figure>
<figure>
  <img src= "/images/portfolio/ml_got/3.PNG" alt="Methodology flowchart">
  <figcaption><em>Flowchart detailing the whole workflow involved in the data driven ML approach applied to the assessment of groundwater sustainability in the area </em></figcaption>
</figure>
<figure>
  <img src= "/images/portfolio/ml_gpot/4.PNG" alt="Groundwater potential maps (SVM and xGBoost)">
  <figcaption><em>Groundwater potential maps of SVM and xGBoost models showing how the area have been classified into different groundwater potential classes</em></figcaption>
</figure> 

<figure>
  <img src= "/images/portfolio/ml_gpot/5.PNG" alt="Groundwater potential maps (RF and AdaBoost)">
  <figcaption><em>Groundwater potential maps of RF and AdaBoost models showing how the area have been partitioned into different groundwater potential domains</em></figcaption>
</figure>

<figure>
  <img src= "/images/portfolio/ml_gpot/6.PNG" alt="Groundwater potential map (AHP)">
  <figcaption><em>AHP based Groundwater potential map of the study area</em></figcaption>
</figure>

<figure>
  <img src= "/images/portfolio/ml_gpot/7.PNG" alt="AUC-ROC comparison of the models">
  <figcaption><em>AUC-ROC curve showing the predictive abilities of the models and ultimately showing that, all ML models outperform the AHP model</em></figcaption>
</figure>

### Perceived limitations and future research direction

We trained our ML models using full training datasets and predicted their abilities using full pack of unseen datasets. Future research could employ cross validation to a single datasets for training and testing to ensure and check models generalizability. Furthermore, it still a major cause of debate whether target variable (in our case, borehole yield data) should be used in a continous manner rather than in a classified manner as we've done in our research. Future works could test these two approaches before modelling!