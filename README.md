California Housing Price Prediction using Regression Models
Project Overview

This project focuses on predicting house prices using the California Housing dataset from Scikit-learn. Different regression algorithms were implemented and compared to identify the best-performing model.

The project includes:

Data loading and preprocessing
Handling missing values
Feature scaling
Model training and evaluation
Comparison of regression algorithms
Dataset Used

Dataset: California Housing Dataset
Library: sklearn.datasets

The dataset contains information such as:

Median Income
House Age
Average Rooms
Population
Latitude and Longitude
Median House Value (Target)
Technologies Used
Python
Pandas
NumPy
Matplotlib
Scikit-learn
Jupyter Notebook
Preprocessing Steps

The following preprocessing steps were performed:

Converted dataset into Pandas DataFrame
Checked and handled missing values
Performed feature scaling using:
StandardScaler
MinMaxScaler
Split dataset into training and testing data
Regression Models Implemented
1. Linear Regression

A simple regression algorithm that predicts values using a linear relationship between features and target.

2. Decision Tree Regressor

Uses tree-based conditions to predict house prices.

3. Random Forest Regressor

Combines multiple decision trees to improve prediction accuracy.

4. Gradient Boosting Regressor

Builds models step-by-step by correcting previous prediction errors.

5. Support Vector Regressor (SVR)

Uses support vectors to predict continuous values.

Model Evaluation

The models were evaluated using:

Mean Squared Error (MSE)
R² Score
Results
Random Forest Regressor achieved the best performance with the highest R² score of 0.80.
Linear Regression showed the lowest R² score among all models.
Conclusion

Random Forest Regressor was identified as the best model for the California Housing dataset because it handled complex and non-linear relationships effectively.

Linear Regression performed poorly compared to other models because it assumes a simple linear relationship between input features and target values.
