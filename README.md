# A Tale Of Two Cities

**Objective** : The goal of this project is to gain insights on important factors that influence the rental values of homes and apartments in Phoenix and Tampa. 

**Measurement of success** : The performance of our model will be tested using mean squared error. 

**Questions to answer** :
- What are the similarities and differences in the rental markets in Phoenix and Tampa?
- How accurately can the model from one city predict rental values in the other?
- How important are historical rental values to predict future ones?
- What factors drive the prediction of rental values in each market?
- What actionable insights can be derived from our analysis? For example, can we increase the rental prices in certain zipcodes if historical data tends to underestimate the rental value.

**Data Sources**
- **Zillow Historical ZRI Data Multi Family Homes**
   Historical ZRI data from 10/2010 - 1/2021
- **Google Bigquery**
  Data from geo_us_boundaries
  Data from ACS
  
**Data Aggregation** : By zipcodes for cities Phoenix and Tampa

**Target variable** : Zillow Rental Index (ZRI) 

**Tools** : Google BigQuery, Jupyter Notebook

**Analysis/Machine Learning** 
- Missingness/Imputation, 
- Feature Selection, 
- Feature Engineering, 
- Ridge/Lasso regression, 
- Tree ensembles, 
- Boosting, 
- Statistical Analysis,
- Residual Analysis

**Our Team**

- [Chitra Sharathchandra](https://github.com/sharathc10): Software developer
- [Gabriela Huelgas Morales](https://github.com/ghuelgas): PhD in biomedical sciences
- [Juan Vasquez](https://github.com/hello-juan): Operations professional
- [Yukti Kathuria](https://github.com/Yukti-K): MS in Aerospace Engineering
- [Guillermo Ruiz](https://github.com/GuilleRuizC): MS in Economics

**Folder breakdown in repository**

- Chitra: SQL Exercise rough code, Phoenix feature extraction and analysis, EDA, Cluster analysis
- Gabriela: SQL Exercise rough code, Modeling nationwide ACS/ZRI data, Phoenix EDA and residual modeling
- Juan: EDA on ACS zipcode data, some preliminary SQL test code, Phoenix Rent growth rate 
- Yukti: EDA on ACS zipcode data, some preliminary SQL test code, Feature engineering for Phoenix,
- Guille: EDA code on ACS zipcode data, Modeling and Statistical Analysis for Phoenix
- SQL_exercises: Final code for SQL task
