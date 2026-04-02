# Ecommerce Customers Analysis and Modeling

## Overview

This project applies data analysis and machine learning techniques to the Ecommerce Customers dataset. The main objective is to explore the dataset, perform data preprocessing, and build a predictive model to estimate customers’ yearly spending.

## Dataset

The dataset contains information about customers such as session duration, time spent on the mobile app and website, length of membership, and yearly amount spent.

## Steps Performed

### 1. Data Loading

The dataset was loaded into a DataFrame using Pandas to enable further analysis and processing.

### 2. Data Exploration

Initial exploration was conducted using methods such as:

* Viewing sample rows
* Checking data types and structure
* Generating summary statistics
* Identifying missing values

### 3. Data Cleaning

* Missing values were checked and handled if present
* Non-numeric columns (Email, Address, Avatar) were removed as they are not useful for modeling

### 4. Feature Engineering

The dataset required minimal feature engineering since all relevant features were already in numerical format.

### 5. Data Preparation

* Features (X) and target variable (y) were defined
* The dataset was split into training and testing sets (70% training, 30% testing)

### 6. Model Training

A Linear Regression model was used to train on the dataset and learn the relationship between input features and yearly spending.

### 7. Prediction

The trained model was used to predict the target values for the test dataset.

### 8. Model Evaluation

The model performance was evaluated using:

* Mean Absolute Error (MAE)
* Mean Squared Error (MSE)
* Root Mean Squared Error (RMSE)

### 9. Visualization

A scatter plot was generated to compare actual vs predicted values, providing a visual representation of the model’s performance.
 Scikit-learn

## Conclusion

The Linear Regression model demonstrated a good ability to predict customer yearly spending based on the available features. Further improvements could include trying different models or adding new features.
