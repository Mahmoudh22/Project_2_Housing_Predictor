# Kings County Prediction Model 

This repository contains a real estate price prediction model developed for a housing company in King's County, Washington. The model is based on a multi-linear regression approach, aiming to predict housing prices using various features. The goal of this project is not only to provide accurate price predictions but also to explore and identify the factors that contribute to higher house prices in the area.

## Dataset
The dataset used for this model is specific to the King's County housing market in Washington. It includes various features related to houses, such as the number of bedrooms, bathrooms, square footage, location attributes, and more. The dataset is stored in the file named kc_house_data.csv, which is located in the Business and Data Understanding directory.

## Model Development
The model development process involved several steps, starting from data preprocessing and exploration to model selection and evaluation. Here is an overview of the major steps:

### 1. Data Preprocessing: The dataset was carefully inspected for missing values, outliers, and inconsistent data. Any necessary data cleaning and formatting steps were performed to ensure the quality and integrity of the data.

### 2. Feature Engineering: Additional features were created or derived from the existing dataset to capture more meaningful information. For example, the feature engineering process involved extracting information from dates, combining relevant attributes, and transforming categorical variables into numerical representations(Waterfront, Greenbelt, and other columns).

### 3.Exploratory Data Analysis: A comprehensive analysis of the dataset was conducted to gain insights into the relationships between different features and the target variable (housing prices). This analysis helped in understanding the data distribution, identifying correlations, and detecting any outliers or anomalies.

### 4.Model Selection: Based on the nature of the problem and the available dataset, a multi-linear regression model was chosen as the primary predictive model. This model assumes a linear relationship between the independent variables and the target variable.

### 5. Model Training and Evaluation: The dataset was split into training and testing sets to train and evaluate the multi-linear regression model. The model was trained on the training set and evaluated using various metrics, including R-squared, variance score, and root mean square error (RMSE).

## Model Performance
The trained multi-linear regression model achieved an R-squared (variance) score of 0.7514, indicating that approximately 75.14% of the variance in housing prices can be explained by the selected features. The root mean square error (RMSE) of the model is approximately $318,585.92, representing the average prediction error in dollars.


## Key Insights
During the model development process, it was discovered that zip codes had the most significant impact on predicting housing prices in King's County, Washington. Other features such as the number of bedrooms, bathrooms, and square footage also contributed to the predictive power of the model but to a lesser extent. It is important to note that the significance and impact of different features on housing prices can vary depending on the location and characteristics of the housing market.

