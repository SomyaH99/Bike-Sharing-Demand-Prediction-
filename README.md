# Bike-Sharing-Demand-Prediction-
1. Problem Statement:
Currently Rental bikes are introduced in many urban cities for the enhancement of mobility comfort. It is important to make the rental bike available and accessible to the public at the right time as it lessens the waiting time. Eventually, providing the city with a stable supply of rental bikes becomes a major concern. The crucial part is the prediction of bike count required at each hour for the stable supply of rental bikes.

2. Dataset information:
Dataset used in this project is the Seoul Bike Share program data.This dataset contains information about the total count of rented bikes at each hour,
as well as the date of observation and meteorological information (Humidity, Snowfall, Rainfall, Temperature Season, and so on) for that hour.

The Seoul Bike Dataset contains the following information:
* Date - The date of each observation in the format 'year-month-day'
* Hour - Hour of the day
* Temperature - Temperature recorded in the city in Celsius (°C).
* Humidity - Relative humidity in %
* Wind speed - Speed of the wind in m/s
* Visibility - measure of distance at which object or light can be clearly discerned in units of 10m
* Dew point temperature - Temperature recorded in the beginning of the day in Celsius(°C).
* Solar radiation - Intensity of sunlight in MJ/m^2
* Rainfall - Amount of rainfall received in mm
* Snowfall - Amount of snowfall received in cm
* Seasons - Season of the year (Winter, Spring, Summer, Autumn)
* Holiday - Whether the day is a Holiday or not (Holiday/No holiday)
* Functional Day -Whether the rental service is available (Yes-Functional hours) or not (No-Non functional hours)
* Rented Bike count - Count of bikes rented at each hour (target variable)

 3. Tools and Technologies used:
 The programming language used in this project is Python . The following libraries were used for data analysis and data visualization and to build a classifier to   predict the price range of mobile phones.

* Pandas : For loading the dataset and performing data wrangling
* Matplotlib: For data visualization.
* Seaborn: For data visualization.
* NumPy: For some math operations in predictions.
* Statsmodels: For statistical computations
* sklearn - For the purpose of analysis,prediction and evaluation.

4. Steps involved:
* Data Preprocessing : Checked for outliers, incorrect values, missing values, duplicates and performed data type correction.
* Feature Extraction : Created new columns such as Day, Month, Year, Days_of_week and Weekend from Date column .
* Exploratory Data Analysis : Performed Univariate, Bivariate, and Multivariate analysis with various graphs and plots to better understand the distribution of features and their relationships.
* Feature Selection : Checked the VIF value (measure of multicollinearity) and dropped Dew point Temperature and Year which were highly correlated with other independent features.
* Feature encoding : The categorical features present in the dataset Seasons, Holiday, Weekend, Functioning Day were dummified.
* Feature Scaling : Brought features to a similar range using MinmaxScaler.
* Implementation of Regression models
* Hyperparameter tuning

5. Comparison of models
💻 Algorithms used
* Linear Regression
* Polynomial Regression
* Decision Tree
* Random Forest
* XGBoost
* Gradient Boosting




  
 



