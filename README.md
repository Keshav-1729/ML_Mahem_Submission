# ML Mahem Submission
##### by Keshav Mishra (112121025)
## Problem Statement:
Given the dataset containing hourly average ambient variables 
(Temperature, Ambient Pressure, Relative Humidity, and Exhaust 
Vacuum), our task is to predict the net hourly electrical energy 
output (PE) of a Combined Cycle Power Plant (CCPP). This 
prediction can assist in optimizing the plant's operation, 
scheduling maintenance, and improving energy efficiency.
## Step 1:
Loaded Important Libraries to use for modelling and data cleaning.
## Step 2:
Checked the Correlation between features.
## Step 3:
Visualized data to know about the outliers, data distribution and the scale of data.
## Step 4:
Removed all the outliers and checked for feature importance using random forest.
## Step 5:
Used 4 models- XGBoost, LightGBM , Decision Tree and Random Forest for regression task where XGBoost performed the best by generalizing over the whole dataset.
## Step 6:
Furthur Boosted the XGBBoost model by running Hyper prameter tuning on the model using randomized search to decrease computation time for tuning.
