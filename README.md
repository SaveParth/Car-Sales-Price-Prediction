Car Sales Price Prediction & Titanic Survival Prediction - README

Project Overview

This repository contains:

Car Sales Price Prediction - Predicting the price of used cars based on various features.

 project follows a structured approach involving data preprocessing, model selection, and performance evaluation.

1. Car Sales Price Prediction

Dataset

The dataset consists of used car sales data with features like brand, year, mileage, engine size, fuel type, etc.

Target variable: Car Price

Data Preprocessing

Handling missing values using imputation techniques.

Encoding categorical variables using One-Hot Encoding.

Feature scaling using StandardScaler or MinMaxScaler.

Splitting data into training and testing sets.

Model Selection

Various regression models were tested, including:

Decision Tree
Random Forest
XGBoost
Linear Regression
Support Vector Regression
K-Nearest Neighbors

Tuned models and ensemble techniques:

Random Forest Regressor (Tuned): R-squared = 0.5686

K-Nearest Neighbors (Tuned): R-squared = 0.5246

Ridge Regression (Tuned): R-squared = 0.6078

Stacking Ensemble: R-squared = 0.6153

Hyperparameter tuning was performed using GridSearchCV to optimize model performance.

Performance Analysis

Model evaluation metrics used:

Mean Squared Error (MSE)

R-squared Score (R²)

The best-performing model was the Stacking Ensemble, achieving an R-squared score of 0.6153.
