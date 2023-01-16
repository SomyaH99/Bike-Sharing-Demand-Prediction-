# Bike-Sharing-Demand-Prediction-
Problem Statement :
Currently Rental bikes are introduced in many urban cities for the enhancement of mobility comfort. It is important to make the rental bike available and accessible to the public at the right time as it lessens the waiting time. Eventually, providing the city with a stable supply of rental bikes becomes a major concern. The crucial part is the prediction of bike count required at each hour for the stable supply of rental bikes.



Approach used:
1. Importing libraries

2. Exploratory Data Analysis

* Extracting features from date

* Model Building

* LINEAR REGRESION

* LASSO REGRESSION

* RIDGE REGRESSION

* ELASTIC NET REGRESSOR

* Polynomial Regression

* DECISION TREE

* GRADIENT BOOSTING

* RANDOM FORREST

* XGBOOST

3. Model Evaluation


Overview:

The provided data is first cleaned and transformed using Feature Engineering. We then split the data into Train set (for Hyperparameter tuning) and Test set (for Model Evaluation). Using R sq and adjusted R sq as our evaluation metric, we compare various models and select the regression algorithm based on the highest value  on the Test data. The final model used for submission is then obtained by again training the selected Regression Algorithm on the entire Input Data set. 
