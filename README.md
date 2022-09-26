# Bike-Sharing-Demand-Prediction-
Problem Statement :
To predict the count of rental bike at each hour of the day

Overview:
The provided data is first cleaned and transformed using Feature Engineering. We then split the data into Train set (for Hyperparameter tuning) and Test set (for Model Evaluation). Using R sq and adjusted R sq as our evaluation metric, we compare various models and select the regression algorithm based on the highest value  on the Test data. The final model used for submission is then obtained by again training the selected Regression Algorithm on the entire Input Data set. 
