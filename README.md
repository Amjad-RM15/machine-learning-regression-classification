# Machine Learning Project: Regression and Classification

## Overview

This repository contains a university team project that applies machine learning techniques to two different problems:

1. Predicting vehicle CO₂ emissions using regression models.
2. Predicting loan approval status using classification models.

The project covers data exploration, visualization, preprocessing, model training, evaluation, and validation.

## CO₂ Emissions Analysis and Regression

The first part analyzes a vehicle dataset containing information about engine size, cylinders, fuel consumption, fuel type, and CO₂ emissions.

The main tasks include:

- Exploratory Data Analysis
- Data visualization using scatter plots, pair plots, and correlation heatmaps
- Multiple Linear Regression
- Forward Feature Selection
- Random Forest Regression
- Model evaluation using Mean Squared Error and R² score

The analysis shows that fuel consumption, engine size, and the number of cylinders are strongly related to CO₂ emissions.

## Loan Approval Classification

The second part uses loan application data to predict whether a loan will be approved or rejected.

The following classification models were implemented:

- Decision Tree
- Logistic Regression
- Naive Bayes
- Random Forest
- Support Vector Machine

The models were evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- Classification Reports
- Confusion Matrices
- Hold-out Validation
- 10-Fold Cross-Validation

Random Forest was selected as the final classification model, achieving approximately 99% accuracy in the project results.

## Technologies

- Python
- Jupyter Notebook
- pandas
- NumPy
- Matplotlib
- Seaborn
- scikit-learn
- Statsmodels

## Repository Files

- [`ML_Project.ipynb`](./ML_Project.ipynb) — Complete code, data preprocessing, visualizations, regression models, forward feature selection, classification models, and saved outputs.
- [`CO2 Emissions4.csv`](./CO2%20Emissions4.csv) — Vehicle specifications, fuel consumption, and CO₂ emissions dataset.
- [`loan_approval_dataset4.csv`](./loan_approval_dataset4.csv) — Loan application and approval classification dataset.

## Academic Context

This project was developed as a university team project for a Machine Learning course.
