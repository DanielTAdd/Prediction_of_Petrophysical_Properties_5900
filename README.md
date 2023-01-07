# Development of a Data-driven Model for Estimation of Resrvoir Properties (shale Volume, Porosity and Fluid Saturations) Using Well Logs: A Case Study of the Vove Field: Norwegian North Sea

## Introduction 
Well logging is the discrete or continuous recording of measurements within a wellbore with a well logging tool or a probe (Hearst and Nelson, 1985). The logging tools are usually placed at the end of a wireline tool and lowered into a petroleum well to measure rock and fluid properties. Standard well logs in the oil and gas industry include resistivity, density, sonic, gamma-ray, caliper, and neutron porosity logs. Well logs provide essential information about geologic formations, which are used in the analysis of geophysical properties of wells, evaluation of formation rock characteristics, estimation of hydrocarbons initially in place, investigation of reservoir pressures, and estimation of in-situ petrophysical, geomechanical and geochemical reservoir properties which is essential for reservoir modeling and production forecasting amongst others (Mondol, 2015).
Despite the numerous advantages of using well logs, well logging tools do not directly measure these properties. On the contrary, these properties are obtained by processing, interpreting, and calibrating the well logs and thus are associated with several uncertainties that may affect the overall outcome (Moore et al., 2011). Furthermore, petroleum engineers and geophysicists use statistical and empirical methods together with well logs to build three-dimensional reservoir models for reserve estimation and improvement of production. However, the process is usually costly, cumbersome, and associated with human errors (Wang et al., 2021).
Data-driven models have recently been a better alternative in reservoir property estimation and characterization using well logs (Fajana et al., 2018; Saproetti et al., 2018). Machine learning has tremendous potential in predicting reservoir properties better than conventional methods using the large volumes of well log data presently available in the oil and gas industry. It is a less cumbersome approach and can be done at a minimal cost.

## Project Objectives
1. The primary objective of this project is to develop a machine learning data-driven model to estimate reservoir properties, including shale volume, porosity, and fluid saturation, based on a standard set of well logs, including gamma-ray, bulk density, neutron porosity, resistivity, and sonic.
2. A secondary objective is to cluster well logs from the training data into various electrofacies (i.e., clusters showing rock intervals with specific characteristics). These electrofacies would be depth-matched and compared with lithological plots obtained from the original database as an extra step in validating the performance of the clustering algorithm.

## Data Source and Aquisition
***Field Description***: The Volve is a Norwegian offshore petroleum field discovered in 1993. The field is located about 5 km from the north Sleipner Ost field, where the water depth is about 85m deep. The Hugin sandstone formation was the main producer from the field, with a permeability of about 2913 millidarcy. The field has a porosity of about 0.226 and showed a peak oil production of 56,000 barrels per day with an overall production of about 63 million barrels (Sen et al., 2019). The data was made available for public consumption in 2018.

***Data Acquisition***: Microsoft Azure Storage Explorer was used to acquire data from the Equinor official website (https://www.equinor.com/energy/volve-data-sharing.
Available data include, Well log, reservoir modeling, seismic, production, and geophysical data, amongst others. For this work, data of interest include well logs, lithology and reservoir properties, field maps, and geological maps.

![image](https://user-images.githubusercontent.com/96665362/211133064-0cf8c480-a52b-49d2-a6ea-0e27661a49a6.png)

*** Volve Filed Data on Microsoft Azure Storage Explorer***


![image](https://user-images.githubusercontent.com/96665362/211133077-5b1b1aaa-baf0-418d-906b-dcec3c4db3f3.png)

*** The Volve Field: North Sea***



## Highlights 

![image](https://user-images.githubusercontent.com/96665362/211133137-17851122-5cd0-4701-a3c4-6b1a8c140704.png)

Summary of Model Results

![image](https://user-images.githubusercontent.com/96665362/211133171-96de4429-d323-41b1-b102-f83379682721.png)

Clustering results summary

### WorkFlow
1. The Cross-Industry Standard Process for Data Mining was used in addressing this problem. 
2. EDA, Feature Engineering, Model Development, Model Diagnostics and Evaluation of model metrics were all conducted with Python. 
3. Major packages used include Numpy, Pandas, Matplotlib, Sklearn, lasio, seaborn and Math amongst others

*** Please refer to final report and presentation for more details ***
