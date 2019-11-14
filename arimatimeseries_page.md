## Time Series and ARIMA Modelling and Analysis of Rolls Royce ($RR) Share Data

**Project description:** In order to fit an ARIMA model that would aim to forecast the future share prices for Rolls Royce Holding PLC, previous monthly data must be collected. 50 data points were collected via Investing.com from the time period of March 2013 to April 2017. The closing value of the share on the first day of each month was used.

### 1. Identifying Which ARIMA Model To Utilise

Using MATLAB, an Autocorrelation Function and a Partial Autocorrelation Function for my collected $RR data was created. Using the rules of identifying ARIMA models, it could be seen that the ACF plot had positive autocorrelations out to a high number of lags and the PACF plot had a sharp lag at 1. This meant that a higer order of differencing would be used as per the ACF plot, and that this time series was an AR(1) time series, thus needing a (1,1,0) ARIMA model to forecast the data effectively.

<img src="images/dummy_thumbnailACFPACF.jpg?raw=true"/>

### 2. Forecast Data With ARIMA Model


### 3. Conclusion

<img src="images/dummy_thumbnail.jpg?raw=true"/>


