# Algorithmic Option Straddle Trading with Machine Learning

## Project Overview
This project involves developing a predictive trading algorithm for option straddle trading using machine learning regression algorithms. The goal is to forecast the profitability of straddle trades based on various features and historical data.

## Project Duration
March 2024 – June 2024

## Objectives
- Develop a predictive model to identify profitable option straddle trades.
- Engineer relevant features to improve model accuracy.
- Experiment with multiple machine learning regression algorithms.
- Validate the model's performance through cross-validation and testing.

## Features Engineered
- **Relative Strike Price/Bid-Ask Spreads**: Normalized strike price and bid-ask spreads to account for differences in option pricing.
- **Historical Implied/Realized Volatility Metrics**: Used past volatility data to predict future price movements.
- **Greeks**: Incorporated Delta, Gamma, Theta, and Vega to capture the sensitivities of the option's price to various factors.

## Machine Learning Algorithms Tested
- Random Forest
- LightGBM
- K-Nearest Neighbors (KNN) Regression
- Support Vector Regression (SVR)
- Linear Regression
- Lasso Regression
- Ridge Regression

## Model Validation
- **Cross-Validation**: Performed 5-fold rolling cross-validation on data from 2020 to 2022 to ensure model robustness.
- **Testing**: Evaluated the model on a holdout set from 2023 to assess its predictive power.

## Tools and Libraries Used
- **Programming Language**: Python
- **Data Manipulation**: Pandas, NumPy
- **Machine Learning**: Scikit-Learn, LightGBM
- **Validation**: Scikit-Learn's cross-validation tools

## Project Workflow
1. **Data Collection**: Gathered historical options data.
2. **Feature Engineering**: Created and normalized features essential for predictive modeling.
3. **Model Training**: Trained multiple machine learning models to identify the best-performing algorithm.
4. **Model Validation**: Used cross-validation and a holdout test set to evaluate model performance.
5. **Results Analysis**: Analyzed the performance metrics to select the most accurate and robust model.

## Conclusion
This project successfully developed a machine learning-based predictive trading algorithm for option straddles. By experimenting with various regression models and validating them thoroughly, we ensured a robust and reliable trading strategy.
