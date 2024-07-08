# House Price Prediction

## Overview
This project aims to predict house prices based on various features, using machine learning techniques. It involves data cleaning and preprocessing, feature engineering, model selection and training and evaluation to achieve the best predictive performance.

## Dataset
The dataset used is the California Housing Prices dataset from Kaggle. It contains information about various houses in California, including features like:

longitude  
latitude  
housing_median_age  
total_rooms  
total_bedrooms  
population  
households  
median_income  
median_house_value  
ocean_proximity  

## Steps Involved

### 1. Data Preprocessing
Handling Missing Values: Removed rows with missing values to ensure data integrity.  
Encoding Categorical Variables: Used one-hot encoding for the ocean_proximity feature.  
Feature Engineering: Created new features eg bedroom_ratio and household_room.  
Data Scaling: Scaled the features for better model performance.  

### 2. Model Training
Linear Regression: Trained a simple Linear Regression model, achieving a score of 0.66.
Random Forest Regressor: Trained a more complex Random Forest model, achieving a score of 0.76.
Hyperparameter Tuning: Used GridSearchCV to tune the Random Forest model, confirming the best parameters and maintaining the score at 0.77.

### 3. Model Evaluation
Evaluated the models using the test set to compare their performance. The evaluation metric used was the model score.

## Results
Linear Regression: Score of 0.66
Random Forest Regressor: Score of 0.76
Optimized Random Forest: Best parameters (n_estimators=3, max_features=4) with a score of 0.77

## Visualizations
Correlation Matrix: Visualized the correlation between different features.
Scatter Plot: Plotted latitude vs longitude with house prices.

## Conclusion
This project provided valuable insights into the importance of data preprocessing, feature engineering, and model optimization in machine learning. The Random Forest model showed significant improvement over Linear Regression, and hyperparameter tuning further enhanced the model’s performance.
