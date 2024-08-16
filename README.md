
# Profit Estimation Linear Regression Model

## Overview

This repository contains a machine learning model designed to predict profits based on various input features using linear regression. The model is intended to assist in understanding how different factors contribute to profit estimation and can be applied to forecast future profits.

## Dataset

The dataset used for training and evaluating the model is `Profit_estimation.csv`, which includes the following features:

1. **R&D Spend:** The amount spent on research and development.
2. **Administration Spend:** The amount spent on administrative tasks.
3. **Marketing Spend:** The amount spent on marketing activities.
4. **State:** The state where the company operates (e.g., New York, California, Florida).
5. **Profit:** The target variable representing the profit earned by the company.

## Feature Encoding

To handle the categorical variable 'State', the model uses:
- **Label Encoding:** Converts categorical 'State' values into numeric representations.
- **One-Hot Encoding:** Creates binary columns for each state to integrate categorical data into the model.

## Model Details

- **Model Type:** Linear Regression
- **Input Features:** R&D Spend, Administration Spend, Marketing Spend, and State
- **Output:** Profit

## Model Training and Evaluation

The model is trained on a portion of the data and tested on a separate set to evaluate its performance. The key performance metric used is the R² score, which measures the proportion of the variance in the target variable (Profit) that is predictable from the input features.

## Results

- **Coefficients:** The model’s coefficients indicate the impact of each feature on the predicted profit.
- **Intercept:** The constant term in the regression equation.
- **R² Score:** A measure of how well the model explains the variability of the profit. An R² score of approximately 0.91 was achieved, indicating a strong fit.
