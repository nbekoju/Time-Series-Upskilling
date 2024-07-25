# Time Series Upskilling

## **Time Series Kaggle Course**

### Day 1

1. Linear Regression with Time series
    1. Major components of time series are **trends, seasons, and cycle**
    2. Tow unique features to time series are **time-step features** and **lag features**
2. Trend
    1. To visualize a trend, we take an average over a period longer that any seasonal period in the series.
3. Seasonality
    1. Two seasonality features are 
        1. **indicator features:** best for the season with few observations. Example: week season with daily observations
        2.  **fourier feature :**  best for the season with many observations. Example: annual season with hourly observations.

### Day 2

1. Time series as Features
    1. Cycles are the pattern of growth and decay in a time series; associated with how th values in a seires at one time depends on values at previous time steps.
2. Hybrid Models
    1. Combine the strength of two models: Linear regression and XGBoost
3. Forecasting With Machine Learning
    1. **Multistep forecasting strategy**
        1. Multioutput model
        2. Direct Strategy
        3. Recursive Strategy
        4. DirRec Strategy