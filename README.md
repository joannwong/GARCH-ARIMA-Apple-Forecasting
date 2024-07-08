# ARIMA-GARCH-Apple-Forecasting

I analysed the Apple stock and used GARCH & ARIMA models to forecast stock prices. 
- Achieved stationarity through seasonal & non-sesaonal differencing; verified using KPSS & ADF tests
- Analysed the data by looking at serial correlation & Q-Q plot
- Fitted data to candidate GARCH models by analysing EACF & ACF plots; goodness-of-fit testing using Ljung-Box test & Jarque Bera test
- Fitted data to ARIMA-GARCH model; goodness-of-fit testing using Ljung-Box test & Jarque Bera test
- Forecasted stock price using best training model; evaluated against test set using RMSE as a metric 
