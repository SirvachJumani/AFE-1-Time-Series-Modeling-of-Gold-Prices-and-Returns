# Applied-Financial-Economertics-Assignment-1
Time Series Modeling of Gold Prices and Returns

The following task done in the Assignment1

1. Obtain weekly historical data (\xts") of gold price (\LBMA/GOLD") for the maximum available time period. Take USD as the base currency for your entire analysis.

2. Create a conventional data frame containing the day, price and log-return variables. What is the convenience of the multiplication by 100 in the latter case?

3. Familiarize yourself with the two time series variables. Plot them, test for normality and compute a histogram thereof.

4. Locate the dates when both variables have had the highest and the lowest values, What inconveniences does weekly time series frequency typically cause?

5. First, convert the weekly time series into monthly. Why is caution advised when it comes to interpretation in this case? Then, convert the dataset into a modern time
series object. Next, declare the time variable as yearmonth(). Finally, get rid of the missing values.

6. Graphically check the log-return variable for autocorrelation. What can be inferred?

7. Check the variable for the existence of a trend. Explain.

8. Estimate ARIMA(0,0,0)􀀀ARIMA(4,0,4) models and choose the one that minimizes the information criteria (IC). Why do we set d=0?

9. Take the model recommended by the Akaike IC and perform a test for residual autocorrelation with up to 20 lags. Interpret the results.

10. Forecast the log-return for the period of May 2020􀀀May 2021. Measure the accuracy formally and graphically. Comment on the results.
