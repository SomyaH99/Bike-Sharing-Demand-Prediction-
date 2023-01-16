# Bike-Sharing-Demand-Prediction-
Problem Statement :
I tried to predict the demand for rental Bikes in the city of Seoul.
The goal of the project is to accurately forecast the demand for rental bikes so that we can optimize the distribution and maintenance of bikes throughout the city. I have also explored other insights which can help in better decision-making


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
