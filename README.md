# Bacterial Growth Prediction

## Overview
This project uses machine learning to predict bacterial growth parameters from experimental conditions, such as CO₂ availability, light intensity and sucrose production. It compares four regression algorithms to understand their predictive performance.

## Objectives
- Explore experimental variables, patterns and relationships.
- Prepare the features for machine learning.
- Build and compare different regression models.
- Tune hyperparameters and evaluate predictions.

## Prediction Targets
- **a:** Maximum bacteria count
- **mu:** Bacterial growth rate
- **tau:** Time delay before growth begins
- **a0:** Initial bacteria level

## Models
- Ridge Regression
- Decision Tree Regression
- Random Forest Regression
- Support Vector Regression (SVR)

## Project Workflow
1. **Exploratory Data Analysis:** Explore distributions, correlations, missing values and outliers.
2. **Preprocessing:** Select input features and apply normalisation inside model pipelines.
3. **Training:** Split the data into training, validation and test sets, then tune models using cross-validation.
4. **Evaluation:** Compare results using Mean Squared Error (MSE) and R² scores.
5. **Visualisation:** Plot regression model comparisons.

## Technologies Used
Python, Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn and Jupyter Notebook.

## Key Findings
In the original experiment, **Random Forest** performed best overall across the four target variables. The notebook has since been organised as a standalone project with improved preprocessing and model selection. Updated performance results have not yet been rerun and verified.

