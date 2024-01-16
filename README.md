# Coffee Price Analysis and Forecasting Report

## Executive Summary
This report analyzes and forecasts coffee prices using historical data and machine learning models, aimed at providing actionable insights for the coffee market's stakeholders.

## Introduction
This project focuses on the dynamic global coffee market, leveraging historical price data to predict future trends with machine learning techniques.

## Data Overview
The dataset, titled `coffee.csv`, comprises 5,746 entries, featuring columns like Date, Open, High, Low, Close, Volume, and Currency. The Date column has been formatted for time series analysis.

## Exploratory Data Analysis (EDA)
The analysis is based on a dataset containing 5,746 entries of daily coffee prices. Here is a brief overview of the data attributes:

- **Date**: Ranges from [start_date] to [end_date]
- **Open**: Average opening price is 127.27 with a standard deviation of 50.57
- **High**: Average highest price is 128.85 with a standard deviation of 51.16
- **Low**: Average lowest price is 125.78 with a standard deviation of 49.85
- **Close**: Average closing price is 127.22 with a standard deviation of 50.51
- **Volume**: Average traded volume is 8,807 units with a standard deviation of 9,613

**Histograms**: We plotted histograms for Open, High, Low, Close, and Volume to understand the distribution of the data.
![EDA 2](https://github.com/pranav2chill/Coffee-Pricing-Project/assets/124155951/7d4ad0c9-89f1-4f9b-8cd5-9985bf615387)
![EDA 1](https://github.com/pranav2chill/Coffee-Pricing-Project/assets/124155951/6a2a8eec-b40d-4d8b-ad4d-e64d67ca72cc)
![EDA 5](https://github.com/pranav2chill/Coffee-Pricing-Project/assets/124155951/78ec735a-f102-4612-9bed-7a312d6b7f69)
![EDA 4](https://github.com/pranav2chill/Coffee-Pricing-Project/assets/124155951/92d7762b-87b8-497c-85c5-9bde6bb43e4a)
![EDA 3](https://github.com/pranav2chill/Coffee-Pricing-Project/assets/124155951/41fdfa22-edff-46d0-95ee-988f1126b9dd)


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

