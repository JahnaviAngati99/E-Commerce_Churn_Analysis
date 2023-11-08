# E-commerce Customer Churn Prediction

## Project Overview
This repository presents a comprehensive analysis aimed at predicting customer churn for an e-commerce platform. The project leverages machine learning algorithms to identify patterns that indicate a likelihood of churn, thereby enabling the implementation of targeted customer retention strategies.

## Data Cleaning
The project commenced with rigorous data cleaning procedures, addressing missing values and outliers. Special consideration was given to key features such as tenure, days since last order, cashback amount, and distance to warehouse, where outliers were identified through statistical methods and retained due to the robustness of tree-based models to such anomalies.

## Exploratory Data Analysis (EDA)
An in-depth EDA was conducted, revealing an average churn rate of 16.84%. Visualization techniques were employed to understand feature distributions and interdependencies, which informed the subsequent feature engineering phase.

## Methodology / Technical Approach
- **Feature Engineering**: Created new features that encapsulate customer behavior and interaction with the platform, enhancing the predictive power of the models.
- **Model Selection**: Focused on tree-based models, specifically the Random Forest and Gradient Boosting Machines (GBM), due to their effectiveness in handling categorical data and capturing complex relationships.
- **Hyperparameter Tuning**: Employed grid search and cross-validation to find the optimal hyperparameters for each model, ensuring the best possible performance.
- **Model Evaluation**: Assessed models using accuracy, precision, recall, and F1 score. Additionally, ROC-AUC was used to evaluate the trade-off between true positive rate and false positive rate.
