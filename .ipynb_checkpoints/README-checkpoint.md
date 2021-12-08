#### TIME SERIES
#A historical Dollar-Yen exchange rate futures data was uploaded via a CSV file and applied to a time series analysis and modeling to determine whether there is any predictabale behavior. The Settle price was decomposed into trend and noise using a Hodrick-Prescott Filter. Returns were forecasted by using an ARMA model, in addition, to predictin the Settle Price. Volatility was forecasted using GARCH model. 






#### Linear Regression Forecasting

In this notebook, you will build a Scikit-Learn linear regression model to predict Yen futures ("settle") returns with *lagged* Yen futures returns and categorical calendar seasonal effects (e.g., day-of-week or week-of-year seasonal effects).

Follow the steps outlined in the regression_analysis starter notebook to complete the following:

1. Data Preparation (Creating Returns and Lagged Returns and splitting the data into training and testing data)
2. Fitting a Linear Regression Model.
3. Making predictions using the testing data.
4. Out-of-sample performance.
5. In-sample performance.
