# Graduate Salary Prediction using Machine Learning

## Overview

This project develops machine learning regression models to predict engineering graduate salaries using academic performance, aptitude assessments, educational background, and personality traits.

The objective is to identify the factors that influence graduate compensation and evaluate the effectiveness of different regression techniques for salary forecasting.

## Business Problem

Employers, universities, and career advisory teams often require insights into the factors influencing graduate salaries.

This project aims to support data-driven decision-making by forecasting salary outcomes based on student profiles and educational achievements.

## Dataset Features

- Academic performance (10th, 12th, GPA)
- Degree and specialization
- Aptitude test scores
- Personality assessment scores
- College characteristics
- Graduation information

Target Variable:

- Salary

## Experiments

### Experiment 0
- Exploratory Data Analysis
- Data Cleaning
- Feature Engineering
- Baseline Model Development

### Experiment 1
- Multiple Linear Regression
- Hyperparameter: fit_intercept

### Experiment 2
- Ridge Regression
- Hyperparameter: alpha

### Experiment 3
- Lasso Regression
- Hyperparameter: alpha

## Evaluation Metric

Models were evaluated using:

- Root Mean Squared Error (RMSE)

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Jupyter Notebook

## Key Findings

- Academic performance and aptitude assessments contributed significantly to salary prediction.
- Regularized regression models improved generalization performance.
- Feature selection reduced overfitting while maintaining predictive accuracy.

## Future Improvements

- Explore ensemble-based regression methods.
- Incorporate additional employment and industry features.
- Deploy the model through an interactive web application.
