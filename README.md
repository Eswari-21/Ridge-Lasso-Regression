

# Ridge & Lasso Regression Analysis (DS_Task_10)

This repository contains a Jupyter notebook (`DS_Task_10.ipynb`) demonstrating the application of Ridge and Lasso regression techniques for predictive modeling.

## 📊 Project Overview

- **Objective**: Compare Ridge (L2) and Lasso (L1) regression methods, including hyperparameter tuning and performance evaluation.
- **Dataset**: [Explain your dataset source—e.g., "Housing prices", "Simulated data", or "Internal CSV"].
- **Tools**: Python, `pandas`, `numpy`, `scikit-learn`, `matplotlib` / `seaborn`.

## 🧠 Analysis Workflow

1. **Data Loading & Exploration**  
   – Load data, inspect columns, data types, null values.  
   – Visualize distributions, check correlations.

2. **Data Preprocessing**  
   – Handle missing values and outliers.  
   – Encode categorical variables (if any).  
   – Split into train/test sets.

3. **Feature Scaling**  
   – Scale features using `StandardScaler`.

4. **Baseline Model: Linear Regression**  
   – Train and evaluate performance using metrics like R² and RMSE.

5. **Ridge Regression**  
   – Use `Ridge()` with `GridSearchCV` to tune `alpha`.  
   – Analyze model coefficients and evaluation metrics.

6. **Lasso Regression**  
   – Use `Lasso()` with `GridSearchCV` to tune `alpha`.  
   – Investigate how some coefficients shrink to zero (feature selection).

7. **Comparison & Insights**  
   – Compare R², RMSE, selected features.  
   – Discuss situations where Ridge vs Lasso performs better.



