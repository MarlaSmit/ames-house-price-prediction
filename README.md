# 🏡 Ames Housing Price Prediction

## Project Overview

This project develops a **multiple linear regression model** to predict residential house sale prices using the Ames Housing dataset. The analysis follows a complete data analysis workflow, including data exploration, feature selection, model development, evaluation, and residual analysis.

The goal was to investigate how **above-ground living area** and **garage area** influence house prices and evaluate how well these variables can predict property values.

---

## Dataset

The project uses the **Ames Housing dataset**, which contains detailed information on residential properties in Ames, Iowa. This dataset is widely used for regression modelling because it includes numerous housing characteristics alongside property sale prices.

---

## Objectives

* Explore and understand the housing dataset.
* Perform data cleaning and preprocessing.
* Analyse relationships between housing characteristics and sale price.
* Build a multiple linear regression model.
* Evaluate model performance using standard regression metrics.
* Assess model assumptions through residual analysis.

---

## Technologies Used

* Python
* pandas
* NumPy
* Matplotlib
* seaborn
* scikit-learn
* Jupyter Notebook

---

## Project Workflow

1. Load and inspect the dataset
2. Clean and prepare the data
3. Perform exploratory data analysis (EDA)
4. Select predictor variables
5. Split the data into training and testing sets
6. Train a multiple linear regression model
7. Evaluate model performance
8. Analyse residuals and interpret results

---

## Model Performance

The model was evaluated using several regression metrics:

* **Mean Absolute Error (MAE):** $33,476.85
* **Mean Squared Error (MSE):** 2,634,371,879.69
* **Root Mean Squared Error (RMSE):** $51,326.13
* **R² Score:** 0.639

The model explains approximately **63.9%** of the variation in house sale prices using **above-ground living area** and **garage area** as predictor variables.

---

## Key Findings

* Both above-ground living area and garage area show positive relationships with house sale price.
* Above-ground living area is the stronger predictor of the two features.
* The model provides reasonably accurate predictions but performs less well for higher-priced homes.
* Residual analysis suggests increasing prediction error for more expensive properties, indicating that additional explanatory variables could improve model performance.

---

## Future Improvements

Potential enhancements include:

* Applying a logarithmic transformation to the target variable.
* Including additional housing features such as neighbourhood and overall quality.
* Investigating influential outliers.
* Comparing alternative regression models such as Ridge and Lasso Regression.
* Applying cross-validation to improve model robustness.

---
