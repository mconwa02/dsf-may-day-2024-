# dsf-may-day-2024-
MLOPS in Financial Services.  Data Science Festival 2024

## Statsmodels Example

An example of how you can use the statsmodels library in Python to 
build an ARIMA (AutoRegressive Integrated Moving Average) model for 
time series forecasting:
 
Make sure to replace 'your_data.csv' with the path to your actual data file. 
Adjust the values of p, d, and q according to your data and model requirements.
Also, consider whether differencing is necessary to make your data stationary,
and modify the code accordingly.

## Sktime Example

To build an ARIMA (AutoRegressive Integrated Moving Average) model using the 
sktime library in Python, you can use the `ARIMA` estimator provided by sktime.
In this example:

1. We load the Airline dataset, which is a univariate time series dataset included in sktime.
2. We split the dataset into training and testing sets.
3. We fit an ARIMA model to the training data using `ARIMA` estimator. You can specify the order of the ARIMA model using the `order` parameter.
4. We use the fitted model to make predictions for the testing set.
5. Finally, we plot the original data, the testing set, and the forecasted values.

This example demonstrates how to use sktime to build and evaluate an ARIMA 
model for time series forecasting. You can adjust the order of the ARIMA model
and other parameters according to your specific dataset and requirements.

## Darts example:

Darts (Data Analytics and Regression Testing Suite) is a library specifically designed for time series forecasting and analysis. It provides a convenient interface for building various forecasting models, including ARIMA (AutoRegressive Integrated Moving Average). Here's how you can use Darts to build an ARIMA model:

1. We load the time series data into a pandas DataFrame and convert it into a Darts TimeSeries object.
2. We split the series into training and testing sets.
3. We fit an ARIMA model to the training data using the `ARIMA` class provided by Darts.
4. We use the fitted model to make predictions for the testing set.
5. Finally, we plot the original data and the forecasted values.

You can adjust the hyperparameters of the ARIMA model and other settings according to your specific dataset and requirements.
