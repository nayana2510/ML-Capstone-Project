# Regression Track – Appliances Energy Prediction

## Overview

This project focuses on predicting household appliance energy consumption using machine learning regression techniques.

## Dataset

**Dataset:** Appliances Energy Prediction  
**File:** `energydata_complete.csv`  
**Target:** `Appliances`

The dataset contains household energy, temperature, humidity, weather, lighting, and time-related features.

## Preprocessing

- Checked missing values and duplicates
- Removed `rv1` and `rv2`
- Extracted time-based features from `date`
- Detected and treated outliers using IQR
- Performed train-test split and feature scaling

## Models

10 regression algorithms were implemented:

- Linear Regression
- Ridge
- Lasso
- ElasticNet
- Polynomial Regression
- Decision Tree
- Random Forest
- Gradient Boosting
- SVR
- KNN

## Evaluation

Models were evaluated using **R², RMSE, and MAE**.  
Hyperparameter tuning using **GridSearchCV** and 5-fold cross-validation were also performed.

## Tools

Python, Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, Jupyter Notebook

## Project Structure

```text
Regression/
├── Appliances_Energy_Prediction.ipynb
├── energydata_complete.csv
└── README.md
