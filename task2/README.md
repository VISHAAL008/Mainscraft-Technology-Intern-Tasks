# House Price Prediction — Model Comparison

A machine learning project developed as part of the **Maincrafts Technology AI & Machine Learning Internship**.

## Overview

This project builds on Task 1 by comparing multiple regression models to predict California house prices using the California Housing Dataset, with feature scaling and structured performance evaluation.

## Features

- Data preprocessing
- Exploratory Data Analysis (EDA)
- Feature Scaling (StandardScaler)
- Multiple model training — Linear Regression, Ridge Regression, Decision Tree Regressor
- Model evaluation (MAE, RMSE, R² Score)
- Model comparison table
- Best model selected based on performance

## Tech Stack

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn

## Results

| Model | MAE | RMSE | R² Score |
|--------------------         |---|---|---|
| Linear Regression           | 0.533 | 0.746 | 0.576 |
| Ridge Regression            | 0.533 | 0.746 | 0.576 |
| **Decision Tree Regressor** | **0.522** | **0.724** | **0.600** |

**Decision Tree Regressor** performed best and was selected as the final model.

## Files

- `AI_ML_Task2_Model_Comparison.ipynb`
- `Task2_Report_VishaalJ.docx`
- `requirements.txt`

## Author

**Vishaal J**
