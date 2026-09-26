# Insurance Medical Cost Prediction

A machine learning project that predicts medical insurance costs based on customer demographic and health-related features.

## Project Overview

This project uses data preprocessing, exploratory data analysis, feature engineering, feature selection, and Linear Regression to predict medical insurance charges.

## Dataset

The dataset contains information such as:

- Age
- Sex
- BMI
- Number of children
- Smoking status
- Region
- Medical insurance charges

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## Machine Learning Workflow

The project includes:

1. Data loading and understanding
2. Data cleaning
3. Exploratory Data Analysis (EDA)
4. Categorical feature encoding
5. Feature engineering
6. Feature scaling using StandardScaler
7. Feature selection using:
   - Pearson Correlation
   - Chi-Square
8. Train-test splitting
9. Linear Regression model training
10. Model evaluation using:
   - R² Score
   - Adjusted R² Score

## Model

**Linear Regression** is used to predict medical insurance charges based on the available features.

## Project Structure

```text
Insurance-Medical-Cost-Prediction/
│
├── insuranace_project(1).ipynb
├── insurance.csv
└── README.md
