# Coffee Price Analysis and Forecasting Report

## Executive Summary
This report analyzes and forecasts coffee prices using historical data and machine learning models, aimed at providing actionable insights for the coffee market's stakeholders.

## Introduction
This project focuses on the dynamic global coffee market, leveraging historical price data to predict future trends with machine learning techniques.

## Data Overview
The dataset, titled `coffee.csv`, comprises 5,746 entries, featuring columns like Date, Open, High, Low, Close, Volume, and Currency. The Date column has been formatted for time series analysis.

## Exploratory Data Analysis (EDA)
**Key Findings:**
- Price distributions vary over time.
- Strong correlations among Open, High, Low, and Close prices.
- Time series analysis reveals patterns in closing prices and price differences.

## Methodology
**Machine Learning Models:**
- Linear Regression
- Decision Tree Regressor
- Random Forest Regressor
- Gradient Boosting Regressor

**Data Preprocessing:**
- Lag feature creation for time series.
- Scaling and imputation for data normalization.

## Model Evaluation
Models were assessed using RMSE and MAE. Linear Regression exhibited the highest accuracy, with the lowest RMSE and MAE values.

## Results and Discussion
Linear Regression is identified as the optimal model for its accuracy and computational efficiency. It effectively captures the price trends, as indicated by its residuals and predictions.

## Recommendations
Based on our findings:
1. **Adopt Linear Regression** for short-term price forecasting.
2. **Integrate External Factors** such as geopolitical events and climate changes for more robust models.
3. **Regular Model Updates** with the latest data are crucial for maintaining prediction accuracy.

## Conclusion
The project demonstrates the effective use of machine learning in forecasting coffee prices, with Linear Regression as the standout model. However, it's crucial to keep refining the model in response to market changes.

## Appendices
- Supplementary charts and data tables.
- Detailed machine learning model outputs and code excerpts.

---

*This report was compiled using Python for data analysis and machine learning, with a focus on practical application in the coffee market.*

