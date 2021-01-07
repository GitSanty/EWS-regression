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



## To do:

- Make pie- and bar charts for the categorical features: LOC & Add_O2 for one patient;
- Find a way to check the mean #observations / day for one patient;
- Autocorrelation: time (x) and EWS_Total (y) for one or two days observations to make prediction for the next hour(s) (Is the relation linear or polynomial in time)?
- Find ways to validate this model (not only splitting dataset).
- Do autocorrelation for the different features (SBP, SpO2, etc)
- Write a function that takes the predicted values for the features (SBP, SpO2, etc) and calculates the EWS_Total based upon the predicted actual values.