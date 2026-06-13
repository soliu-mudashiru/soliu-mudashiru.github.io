---
title: "ML algorithms for groundwater sustainability in a data scarce region"
excerpt: "Study area <br/><img src='/images/portfolio/ml_gpot/1.PNG'>"
collection: portfolio
---
---
# Description
Published work, Ecological Frontiers (2026) [Link](https://www.sciencedirect.com/science/article/abs/pii/S2950509726000237) 

---
# Highlights 
- Fishnet approach have been used to derive data partitioning for the ML modelling.

- Multicollinarity detection was employed to select the most suitable remote sensing parameters.

- ML algorithms (SVM, RF, xGBoost, AdaBoost) have been utilized and compared with AHP model for their groundwater sustainability predictive abilities. 

- The result demonstrated the abilities of data driven approaches in partitioning groundwater locations for its sustainability even in data scarce region

---
# Abstract
Humanity's usage of water cannot be halted, as water is a necessary resource for existence and is highly valued in a wide variety of quotidian usages and initiatives. This study aimed to predict and define groundwater potential (GWP) zones in the Edo North region of Nigeria. This is achieved by combining machine learning (ML) models, such as random forest (RF), support vector machine (SVM), adaptive boosting (AdaBoost), and eXtreme gradient boost (XGB), with analytical hierarchy process (AHP)—multi-criteria decision analysis (MCDA). Multiple indices, including anthropological (normalized difference vegetation index), hydrogeological (geology and lineament density), hydrological (rainfall distribution and proximity to surface water bodies), and topographical factors (slope, aspect, drainage density, and topographic wetness index), were utilized as groundwater-influencing parameters. Prognostication competencies of these factors were established through the application of multicollinearity (MC) evaluation. The AHP approach was used to weight and scale these influencing variables and determine their impact on groundwater prospects. Given the constrained amount of data available, ‘CreateFishnet_management’ requires training the ML models with 100% borehole data. Every model's reliability was quantified using the area under the receiver-operating characteristic (AU-ROC) curve. The four (4) machine learning algorithms and AHP model divided the GWP zone into four distinct groups: high, moderate, low, and very low. The RF, AdaBoost, SVM, XGB, and AHP models show that the beneficial GWP zones encompass 41.59%, 36.42%, 45.93%, 25.30%, and 14.03% of the research region, respectively. The model dependability using measured AU-ROC curve metrics indicates that the RF model has the greatest rate of success (78.00%), preceding the AdaBoost (77.00%), SVM (73.00%), XGB (71.00%), and AHP (50.00%) models. This multi-approach promotes long-term groundwater governance in the study area
<figure>
  <img src= "/images/portfolio/ml_gpot/2.PNG" alt="Fishnet location template">
  <figcaption><em>Fishnet location used to extract values of influencing variables into the modelling. It was also adopted in selecting appropriate target points from the borehole yield map which served as the spatial representation of the target variable in the study region </em></figcaption>
</figure>
<figure>
  <img src= "/images/portfolio/ml_gpot/3.PNG" alt="Methodology flowchart">
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

---
# Future research direction

We trained our ML models using full training datasets and predicted their abilities using full pack of unseen datasets. Future research could employ cross validation to a single datasets for training and testing to ensure and check models generalizability. Furthermore, it still a major cause of debate whether target variable (in our case, borehole yield data) should be used in a continous manner rather than in a classified manner as we've done in our research. Future works could test these two approaches before modelling