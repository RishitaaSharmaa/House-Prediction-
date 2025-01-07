# House Price Prediction Model

This repository contains a project that predicts house prices using a linear regression model and compares its performance with other machine learning models. The project emphasizes real-world data cleaning and preprocessing techniques to ensure robust and logical predictions.

## Features
- **Data Cleaning and Preprocessing:** Handles missing values, categorical encoding, and outlier detection, ensuring the data is ready for modeling.
- **Linear Regression Model:** Serves as the baseline model for predicting house prices.
- **Model Comparison:** Compares the performance of linear regression with other models such as Lasso and Decision Tree Regressors.
- **Hyperparameter Tuning:** Optimizes model parameters to improve accuracy.

---

## Table of Contents
1. [Workflow](#workflow)
2. [Results](#results)

---

## Workflow

1. **Data Cleaning:**
   - Handle missing values using logical imputation methods.
   - Remove or replace outliers based on domain knowledge.
   - Encode categorical variables (e.g., one-hot encoding for location).

2. **Data Preprocessing:**
   - Scale numerical features using StandardScaler.
   - Split the dataset into training and testing sets.

3. **Model Development:**
   - Train a linear regression model as the baseline.
   - Evaluate the performance of Lasso and Decision Tree Regressors.

4. **Model Evaluation:**
   - Compare models using metrics such as Mean Squared Error (MSE) and R-squared.
   - Select the best-performing model.

5. **Prediction:**
   - Use the final model to predict house prices on new data.

---

## Results

- **Baseline Model:**
  Linear regression achieved an R-squared value of `X.XX` on the test set.

- **Best Model:**
  The Decision Tree Regressor achieved the highest R-squared value of `Y.YY`.

- **Conclusion:**
  The comparison highlights that advanced models with optimized hyperparameters can outperform simpler models like linear regression.

