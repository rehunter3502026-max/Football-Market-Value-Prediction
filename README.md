# ⚽ Football Market Value Prediction

https://colab.research.google.com/drive/1l--Cj6fAOkMoC3sro6_LG7TO0E6gWAFt?usp=sharing


## Overview

This project predicts the market value of professional football players using machine learning regression models. It leverages player attributes, performance statistics, contract information, and market-related factors to estimate realistic transfer values.

## Features

* Data preprocessing and cleaning
* Exploratory Data Analysis (EDA)
* One-Hot Encoding for categorical features
* Train-test split
* Multiple regression models:

  * Linear Regression
  * Random Forest Regressor
  * Gradient Boosting Regressor
  * Extra Trees Regressor
* Model performance evaluation using:

  * MAE
  * RMSE
  * R² Score
* Feature importance analysis
* Market value prediction for new players
* Model serialization using Joblib

## Dataset

The project uses a synthetic dataset containing **3,000 football players** with features such as:

* Age
* Position
* Nationality
* League
* Club
* Overall Rating
* Potential Rating
* Technical Attributes
* Contract Information
* Weekly Wage
* Goals
* Assists
* Minutes Played
* Marketability Score
* Injury History
* Release Clause
* Market Value (Target)

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Joblib

## Machine Learning Workflow

1. Import libraries
2. Load dataset
3. Exploratory Data Analysis
4. Data preprocessing
5. Feature encoding
6. Train-test split
7. Model training
8. Model evaluation
9. Feature importance visualization
10. Market value prediction
11. Save and load trained model

## Results

The project compares multiple regression algorithms and selects the best-performing model based on evaluation metrics such as R² Score, MAE, and RMSE.

## Future Improvements

* Hyperparameter tuning
* XGBoost, LightGBM, and CatBoost integration
* Cross-validation
* Deployment with Streamlit or Flask
* Real-world football transfer datasets
