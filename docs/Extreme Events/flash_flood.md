---
layout: default
title: Flash Flood
parent: Extreme Events
nav_order: 1
---

# Flash Flood forecast

__[A review of advances in flash flood forecasting](https://onlinelibrary.wiley.com/doi/full/10.1002/hyp.8040)__

<p align="center">
<img src="https://onlinelibrary.wiley.com/cms/asset/cdb674c2-9b70-4266-a698-ef801f99f8f7/mfig005.jpg">
</p>

__[Comments on “Flash Flood Verification: Pondering Precipitation Proxies”](https://journals.ametsoc.org/view/journals/hydr/22/3/JHM-D-20-0215.1.xml)__

By JJ and Humberto who compared four threshold-based system for flash flood forecast accuracy: 1) MRMS dual-pol, radar-only QPEs; 2) ARIs of rainfall; 3) ratios of QPE to FFG; and 4) unit streamflow from the Sacramento Soil Moisture Accounting (SAC-SMA) mode.

It was found that the relative ETS values increased with the sophistication of the flash flooding products.

<p align="center">
<img src="https://journals.ametsoc.org/view/journals/hydr/22/3/full-JHM-D-20-0215.1-f6.jpg">
</p>

## Flash Flood guidance

__[The Flash Flood Guidance System Implementation Worldwide: A Successful Multidecadal Research-to-Operations Effort](https://journals.ametsoc.org/view/journals/bams/103/3/BAMS-D-20-0241.1.xml)__

* The Flash Flood Guidance System (FFGS) provides real-time assessment and guidance products to more than 60 countries, serving nearly 3 billion people.
* The FFGS combines meteorology and hydrology data and concepts to support product utility for flash flood disaster mitigation on very large scales with high spatial and temporal resolution.
* The FFGS integrates remotely sensed data of land surface precipitation and of land surface properties from geostationary and polar-orbiting satellite platforms, reflectivity data from a variety of weather radar systems, and asynchronous precipitation data from ground-based automated precipitation gauges in order to produce assessments and short-term forecasts that support forecasters and disaster managers in real time.
* For each region, it also integrates mesoscale meteorological model forecasts with land surface model response to produce longer-term guidance products.
* The FFGS contains components and interfaces that allow real-time forecaster adjustments to products based on local last-minute field information and relevant forecaster experience.
* The article exemplifies the process of realization and evolution of the Flash Flood Guidance System (FFGS) from research in interdisciplinary fields to operations in diverse environments, and discusses lessons learned.

# Flash Flood Index

__[The development of a flash flood severity index](https://www.sciencedirect.com/science/article/pii/S002216941630186X)__

A meta analysis of a workshop regarding how to determine flash flood severity index. They tentatively a quanlitative method to describe it. 

|Category|Impact|
|--------|------|
|1-Minor flood|River/creek overflowing; cropland/yard/basement flooding|
|2-Moderate flood|	Street/road flooding; road closures|
|3=Serious flood|Vehicles, homes and/or buildings inundated with water; road/bridge damage|
|4-Severe flood|Vehicles and/or mobile homes swept away|
|5-Catastropic flood|Buildings/Large infrastructures submerged; permanent homes swept away|

__[Assessment of Vulnerability to Extreme Flash Floods in Design Storms](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3155336/)__

In this article, the authors quantified the flash flood index by taking three terms into account: Rising Curve Gradient, Peak Discharge Magnitude, and Flood Response time. They also mapped Flashiness Index - Intensity - Duration - Frequency curves based on flood hydrograph but the shape is not similar to rainfall IDF curve.

$$RF=\frac{RK+RM+RT}{3}*100%$$

<p align="center">
  <img src="https://www.ncbi.nlm.nih.gov/corecgi/tileshop/tileshop.fcgi?p=PMC3&id=660144&s=26&r=1&c=5">
</p>

__Zeng, Z., et al. (2016). "A cascading flash flood guidance system: development and application in Yunnan Province, China." Natural Hazards 84(3): 2071-2093.__

In this paper, the author proposed a framework which integrates data from precipitation, DEM, GPD etc. With these information, they take advantage of information entropy approach to assign different weights to each category. After that, they came up with an index map covering Yunnan province in China to assess the susceptibility of flash flood.



<img src="../../src/flashflood_Framework.png"> 

__[Mapping Flash Flood Severity in the United States](https://journals.ametsoc.org/view/journals/hydr/18/2/jhm-d-16-0082_1.xml)__

First study to derive the flashiness index over the continetnal US by utlizing machine learning trained on stream gauges.

<p align="center">
  <img src="https://journals.ametsoc.org/view/journals/hydr/18/2/images/full-jhm-d-16-0082_1-f7.jpg">
</p>


__[On the Impact of Rainfall Spatial Variability, Geomorphology, and Climatology on Flash Floods - WRR](https://agupubs.onlinelibrary.wiley.com/doi/10.1029/2020WR029124)__

The author compared modelled flashiness indices to simulated flashiness indices and performed metrics analyzing the first-order dependence with rainfall variablity climatology and basin property.

__[The Flashiest Watersheds in the Contiguous United States](https://journals.ametsoc.org/view/journals/hydr/16/6/jhm-d-14-0217_1.xml#bib20)__

This article is titled “The Flashiest Watersheds in the Contiguous United States” and was written by Brianne K. Smith and James A. Smith. It was published in the Journal of Hydrometeorology. Key points:

1. The authors identify the flashiest watersheds in the contiguous United States based on frequency of discharge peaks exceeding 1 m3 s−1 km−2.
2. They used the entire digitized record of USGS instantaneous discharge data for all stream gauging stations with over 10 years of data.
3. The flashiest basins in the contiguous United States are located in urban areas along a swath of states from the south-central United States to the mid-Atlantic and in mountainous areas of the West Coast, especially the Pacific Northwest.
4. The authors focus on small watersheds to identify the flashiest cities and states across the country and find Tulsa, Oklahoma; Baltimore, Maryland; and St. Louis, Missouri, to be the flashiest cities in the contiguous United States.
5. Thunderstorms are major agents for peak-over-threshold flood events east of the Rocky Mountains, and tropical cyclones play a secondary role, especially in Southeast. West Coast flood events are associated with winter storms.

<p align="center">
  <img src="https://journals.ametsoc.org/view/journals/hydr/16/6/images/full-jhm-d-14-0217_1-f2.jpg">
</p>


__Ombadi, M., et al. (2018). "Developing Intensity-Duration-Frequency (IDF) Curves from Satellite-based Precipitation: Methodology and Evaluation" Water Resources Research__

In this paper, the author tried to develop IDF curve through 3 steps: 1. bias adjustment, 2. Point-to-Area transformation, 3. develop IDF curve with IR satellite data PERSIANN-CDR. The results are compared with NOAA Atlas 14.

The adjustment of bias is related to altitude because the author found the bias is increasing with elevation for IR satellite precipitation products.

__Maddox, R. A. Chappell, C. F. and Hoxit, L. R. (1979). "Synoptic and Meso-$\alpha$ Scale Aspects of Flash Flood Events." Foucs on Forecasting.__

Author analyzed synoptic and mesoscale flash flood occuring in the US from 1973 to 77. He found that places frequently having flash flooding share the same features:
1. Heavy rains were produced by convective storms. (from W to E, convective storms are more dominant)
2. Surface dewpoint temperatures were very high.
3. Large moisture contents were present through a deep trpospheric layer.
4. Vertical wind shear was weak to moderate through the cloud depth.

__Dowswell III, C. A., H.E. Brooks, R.A. Maddox (1996). "Flash Flood Forecasting: An Ingredients-Based Methodology." Weather and Forecast(11): 560-581.__

Key ingredients that affect flash floods:
1. The heaviest precipitation occurs where the rainfall rate is highest for longest time.
2. precipitation efficiency is important: the ratio of the mass of water falling as precipitation to the influx of water vapor loss into the cloud.
3. Heavy rain rates are most often occur with deep convection - the atmosphere must be conditionally unstable and significant lift must occur to lift the airmass through the level of free convection (LFC).
4. The heavy precipitation must remain quasi-stationary.

__[Leveraging machine learning for predicting flash flood damage in the Southeast US](https://iopscience.iop.org/article/10.1088/1748-9326/ab6edd/meta)__

Environmental Research Letters


The author attempted to train an ensemble ML models to predict the flash flood damages among which they also used ANN to fill the gaps of median household values for the U.S. citizens. They eventually achieved reasonably good result for their models. But I had some insights of it:
1. For the binary classification, the author presented a ROC curve to demonstrate the accuracy but as they didn't mention the distribution of the data sample, meaning that it could be biased because of the sample distribution;
2. For the regression model, I'm wondering if train the network based upon the result of classfication would be better because it is a way to reduce trainable data and also people are not aware of which no damage caused in the event;

  


__[Flash Flood Risk Assessment in the Context of Economic Change Scenarios](https://journals.ametsoc.org/view/journals/wcas/15/1/WCAS-D-21-0141.1.xml)__


The authors used a flood inundation model to retrospectively analyze one flash flood event and associate it with economic losses. They used GDP by different CMIP models to project future economic losses by a similar event.


__[The Paroxysmal Precipitation of the Desert: Flash Floods in the Southwestern United States WRR](https://agupubs.onlinelibrary.wiley.com/doi/full/10.1029/2019WR025480)__

* The article discusses a deadly flash flood event that occurred on September 14th, 2015 in Hildale, Utah. This event resulted in 20 fatalities and is considered the most deadly natural disaster in Utah’s history.
* The flood was caused by a hailstorm that intensified as it interacted with complex terrain and moved rapidly from southwest to northeast.
* The storm exhibited striking temporal variability and produced extreme precipitation over Maxwell Canyon tributary of Short Creek and a small portion of the East Fork Virgin River basin.
* Polarimetric radar observations were used to analyze the rainfall characteristics of the storm. Periods of extreme rainfall rates were characterized by KDP signatures of extreme rainfall in polarimetric radar measurements.
* The climatology of monsoon thunderstorms that produce flash floods exhibits striking spatial heterogeneities in storm occurrence and motion.


# Flash Flood Warning and Communication

__[Rebecca Morss at NCAR](https://scholar.google.com.sg/citations?user=v1D1YdsAAAAJ&hl=en&oi=ao)__ who wrote a lot of papers about extreme weather risk communications through surveys and mental models, below listed are two:

1. __[How do people perceive, understand, and anticipate responding to flash flood risks and warnings? Results from a public survey in Boulder, Colorado, USA](https://www.sciencedirect.com/science/article/pii/S0022169415009348)__
2. __[“Know What to Do If You Encounter a Flash Flood”: Mental Models Analysis for Improving Flash Flood Risk Communication and Public Decision Making](https://onlinelibrary.wiley.com/doi/full/10.1111/risa.12480)__
3. __[Flood Risk, Uncertainty, and Scientific Information for Decision Making: Lessons from an Interdisciplinary Project](https://journals.ametsoc.org/view/journals/bams/86/11/bams-86-11-1593.xml)__
