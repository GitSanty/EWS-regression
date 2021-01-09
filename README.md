# EWS-regression

## Day 1: 4th of Jan 2021

- Data preprocessing + narrow down dataframe on patient level (with the most observations)
- Basic visualization on patient level 
- Multiple linear regression on patient level

## Day 2: 5th of Jan 2021

- Played around with regression

## Day 3: 6th of Jan 2021

- Make time series one patient for the whole period against NEWS chart
- Make time series trend one patient for 2 months with rolling averages
- Autocorrelation plots on one patient
- Persistance model on one patient for several types of measurements.
- Autoregression model on one patient for several types of measurements.

## Day 4: 7th of Jan 2021

- Basic visuals: pie chart and bar chart on categorical variables
- Split datetime object into date and time to find mean amount of observations/day
- Continue with smoothing moving averages to make predictions
- Get to know ARIMA model

## Day 5: 8th of Jan 2021

- How to train autoregression model and use it to make short-term and rolling forecasts
- About the MA approach to develop an autoregression model to residual error
- How to develop and evaluate a model of residual error to predict forecast error
- how to use the predictions of force error to correct predictions and improve the model skill
- ARIMA model, how it can be configured, and assumptions made by the model
- perform time series analysis using ARIMA model
- use ARIMA model to forecast out of sample predictions
- Difference and intuition for interpreting ACF and PACF plots

## Weekend

- Grid search ARIMA parameters for time series
- Finding p-, d-, q- values with auto.arima
- Compare both findings (grid search vs. auto.arima)
- Forecasting on grid search and on auto.arima
- R2
