# Stock_prediction
We are using time-series forecasting techniques here on a dataset of APPLE's stock-market data.

**MODELS used :**
1. ARIMA
2. SARIMA
3. SARIMAX

**Steps:**

As part of EDA we make sure that all target variable data is numerical, time-series formatting is proper, there is no missing data, time stamps are continuous and in ascending order and overall time-series is stationery.

While cleaning and sorting the data, it's important to make sure all Business holidays are taken care of.

Since there is seasonality in the data, we decompose and find the frequency.

Determine the series is stationery using Augmented Dickey Fuller test

Do a train test split

Apply the models and find the best fit for data.

*Data-set and code are supplied as part of Learnbay's Master's program and this is a hands-on representation of same https://www.learnbay.co/*
