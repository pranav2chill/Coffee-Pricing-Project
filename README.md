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
  ![EDA 1](https://github.com/pranav2chill/Coffee-Pricing-Project/assets/124155951/d1daa834-d204-458c-8e36-046a698bdae6)

- **High**: Average highest price is 128.85 with a standard deviation of 51.16
  ![EDA 2](https://github.com/pranav2chill/Coffee-Pricing-Project/assets/124155951/40c08a39-8e40-4aee-9df1-d91de958272a)

- **Low**: Average lowest price is 125.78 with a standard deviation of 49.85
  ![EDA 3](https://github.com/pranav2chill/Coffee-Pricing-Project/assets/124155951/59ca4029-2e56-4bc3-aa52-559363f2ee0b)

- **Close**: Average closing price is 127.22 with a standard deviation of 50.51
  ![EDA 4](https://github.com/pranav2chill/Coffee-Pricing-Project/assets/124155951/200ea87b-4c47-47c9-ba39-5e87c94adf84)

- **Volume**: Average traded volume is 8,807 units with a standard deviation of 9,613
  ![EDA 5](https://github.com/pranav2chill/Coffee-Pricing-Project/assets/124155951/1f5e4b95-a707-4123-b1e3-fbc517e6a647)


**Histograms**: We plotted histograms for Open, High, Low, Close, and Volume to understand the distribution of the data.



**Key Findings:**
- Price distributions vary over time.
- Strong correlations among Open, High, Low, and Close prices.
 ![coorelation heatmap](https://github.com/pranav2chill/Coffee-Pricing-Project/assets/124155951/dbc31f17-6dc1-45c9-85c0-72663cede8a0)
- Time series analysis reveals patterns in closing prices and price differences.
![Time series closing price](https://github.com/pranav2chill/Coffee-Pricing-Project/assets/124155951/8f51591a-3072-4948-9437-727263861fd1)
![time series price doff](https://github.com/pranav2chill/Coffee-Pricing-Project/assets/124155951/ee08dbbc-8943-4626-8a5f-1dd5fc8ecedd)

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
- **Linear Regression**: Achieved an RMSE of 0.0646 and an MAE of 0.0456.
  ![time series forcasting lin reg](https://github.com/pranav2chill/Coffee-Pricing-Project/assets/124155951/6795473f-760f-44ef-aaaf-194b1564fc0b)

- **Decision Tree Regressor**: Yielded an RMSE of 0.0840 and an MAE of 0.0605.
  ![Time Series Forcasting Decision Tree](https://github.com/pranav2chill/Coffee-Pricing-Project/assets/124155951/9fb5d663-eaed-484b-9498-a4bbe6bb481d)

- **Random Forest Regressor**: Resulted in an RMSE of 0.0762 and an MAE of 0.0550.
  ![time series forcasting random forests](https://github.com/pranav2chill/Coffee-Pricing-Project/assets/124155951/7152fb91-d091-4a84-9bcb-954338b3a6f0)

- **Gradient Boosting Regressor**: Obtained an RMSE of 0.0681 and an MAE of 0.0482.
  ![time series forcasting gradient boosting](https://github.com/pranav2chill/Coffee-Pricing-Project/assets/124155951/1d552443-d806-42c9-8ebf-1bf9081789c7)

- **Model Comparison**:![Model Comparison MAE](https://github.com/pranav2chill/Coffee-Pricing-Project/assets/124155951/b1c43584-d8ed-4795-a0ab-8d721a66cf3e)
![model comparison RMSE](https://github.com/pranav2chill/Coffee-Pricing-Project/assets/124155951/ca4730db-06c6-4cc3-b1ef-137ef8ff7bbe)

## Comparative Analysis
- Comparing the model evaluation metrics, Linear Regression has the lowest RMSE and MAE, suggesting it has the best performance among the four.
Decision Tree has the highest RMSE and MAE, indicating it might not be the best model for this particular forecasting task.
In summary, if we prioritize accuracy and generalization, Linear Regression and Gradient Boosting appear to be the most suitable models, with Gradient Boosting having a slight edge in capturing complex patterns in the data. The Decision Tree model, while inherently interpretable, may not capture the nuances in the data as well as the other models. The Random Forest model offers a balance between the simplicity of Linear Regression and the complexity handled by Gradient Boosting, but still doesn't outperform Linear Regression in this instance.

- The choice of the model could depend on the specific use case: if interpretability is key, Decision Tree might be chosen despite its lower accuracy, whereas for pure prediction performance, Linear Regression or Gradient Boosting would be preferred. It's also worth noting that the performance could potentially be improved by tuning the hyperparameters, adding more features, or even ensemble methods to combine the strengths of multiple models.

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

