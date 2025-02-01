# Machine Learning Project: Health Insurance Premium Prediction

## Overview

This project aims to predict health insurance premiums based on various factors such as age, BMI, smoking status, and medical history. The dataset consists of 50,000 records, and machine learning techniques have been applied to analyze and model the data effectively.

## Dataset

The dataset contains 50,000 records with key features including:

- Age
- BMI
- Smoking status
- Medical history
- Employment status
- Annual income
- Insurance plan

## Technologies Used

- Python
- Pandas, NumPy
- Scikit-learn
- XGBoost
- Matplotlib, Seaborn (for visualization)
- Streamlit (for deployment)
- Statsmodels

## Project Workflow

### 1. Data Preprocessing

- Handling missing values
- Encoding categorical variables
- Feature scaling / normalization
- Feature engineering

### 2. Exploratory Data Analysis (EDA)

- Visualizing feature distributions
- Identifying correlations
- Outlier detection and treatment
- Risk analysis

### 3. Model Training & Evaluation

- Splitting dataset into training and test sets
- Dividing dataset into two parts:
  - **Above 25 years**: Trained using **Linear Regression**
  - **Below 25 years**: Trained using **XGBoost**
- Hyperparameter tuning using **RandomizedSearchCV**
- Model evaluation using metrics:
  - R-squared score (R²)
  - Mean Squared Error (MSE)
  - Mean Absolute Error (MAE)

### 4. Model Deployment

- Deployed using **Streamlit** for interactive user experience
- Hosted for real-time premium prediction

## Results

- The model performed well for users **above 25 years old** with **Linear Regression**
- For users **below 25 years old**, **XGBoost** provided better predictions
- Effective feature engineering improved model accuracy

##
