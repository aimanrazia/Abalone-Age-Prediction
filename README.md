# Abalone Age Prediction
A machine learning project for predicting the age of abalones.

## Overview

This project aims to predict the age of abalones using machine learning techniques.  
By analyzing abalone characteristics such as physical measurements and gender, the model leverages Random Forest Regression to deliver accurate predictions.  
Additionally, various regression models are evaluated to determine the best-performing algorithm for precise age estimation.

The project evaluates its performance using metrics like **Root Mean Squared Error (RMSE)**, **Mean Squared Error (MSE)**, **Mean Absolute Error (MAE)**, and **R-squared (R²)**.

---

## Features
- Predict abalone age using regression models.
- Evaluate different machine learning models such as Random Forest, Ridge Regression, Gradient Boosting, and Support Vector Regression.
- Visualize insights through data distribution, correlations, and feature relationships.
- Analyze feature importance to identify the most impactful predictors of age.
- Scale and preprocess data to ensure optimal model performance.

---

## Technologies Used
- **Programming Language**: Python  
- **Libraries**:
  - `sklearn` for machine learning models and evaluation metrics
  - `numpy` and `pandas` for data manipulation
  - `matplotlib` and `seaborn` for visualization

---

## Dataset
The dataset contains measurements of abalones with features such as:

- **Sex** (categorical: Male, Female, Infant)  
- **Length** (longest shell measurement in mm)  
- **Diameter** (perpendicular to length in mm)  
- **Height** (with the meat inside the shell in mm)  
- **Whole weight** (weight of the whole abalone in grams)  
- **Shucked weight** (weight of the meat in grams)  
- **Viscera weight** (gut weight in grams)  
- **Shell weight** (after being dried in grams)  

**Target Variable**:  
- **Age**: Calculated as `Rings + 1.5`.

The dataset is preprocessed to handle categorical features, scale numerical data, and fill missing values (if any).

---

## Key Results
**Regression Metrics (Random Forest Regressor)**:
- **RMSE**: 1.56  
- **MSE**: 2.43  
- **MAE**: 1.23  
- **R-squared**: 0.89  

**Feature Importance (Top Predictors)**:
1. Shell weight  
2. Diameter  
3. Whole weight  

---

## Visualizations
- **Correlation Heatmap**: Displays the relationship between numerical features and age.  
- **Feature Distributions**: Visualized using histograms and density plots.  
- **True vs Predicted Age**: Scatter plot to evaluate model performance visually.  
- **Feature Importance**: Highlighted by the Random Forest model.

---

This project delivers a robust framework for age prediction, leveraging advanced regression techniques and thorough evaluation to ensure accuracy and reliability.
