# IUPUI-H516-GroupProject

Project Title:  Predicting Ozone Levels Based on the presence of CO, Pb, NO2, and SO2 in Marion County 
Team Members: Aafaz Ilahi, Haseeb Ahmed Khan, Robert Quick, and Srinivas Yerragola, 
Problem Statement: The Environmental Protection Agency publishes data from sensors in Marion County. We will compare the level of pollutants in found by these sensors to Ozone readings. This project will attempt to find a relationship between the amount of CO, Pb, NO2, and SO2 measured by sensors to the reported Ozone levels. This analysis can help to provide an idea of which pollutants affect the air quality in the Indianapolis area and which ones have the most impact on ozone levels. The data and analysis will be done across academic and/or commercial cloud service providers. We will also provide an interface for future users to compare additional timeframes, locations, and pollutants.   
Description of the Data set: 
Dataset for this problem will come from the EPA daily download interface[1] which provides air sensor readings for CO, Pb, NO2, Ozone, and SO2. We will concentrate on Marion County during the year of 2019 but make the service flexible enough for users to look at other locations and timeframes. We will also train a data model with 2019 measurements to predict 2020 air quality.   
The data is measured daily and managed by the US EPA. Metadata is well documented and detailed. It includes time, geospatial, and pollutant measurement data.   
Expected Outcomes / Results: 
The expected outcomes of this project are to determine significant relationship between pollutants and ozone and to design a predictive model which would learn and train itself on the historical data and predict future air quality.  
In this project we intend to design a complete end to end solution to deploy a linear regression analysis  based machine learning model to predict air quality.  
Mentioned below are the technology stack we intend to use in this project: 
1. Python, Numpy, Pandas and Scikit Learn- For linear regression and Spark MLLib for predictive modeling  2. AWS Sagemaker or Openstack – Cloud Infrastructure to deploy model  3. Spark – Data Preprocessing, Cluster Computing and Stream Processing 4. Computation and Hosting – AWS or Jetstream[2]  
References: 
EPA Daily Data: https://www.epa.gov/outdoor-air-quality-data/download-daily-data  
Jetstream: https://jetstream-cloud.org/  
 
