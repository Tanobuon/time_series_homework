# time_series_homework

## Findings
* Utilizing the Hodrick-Prescott Filter we got a better view of trends and pattern.
* Utilizing the ARMA model and setting AR value to 2 and MA to 1 we received a good fit result with 2 p-values lower than 0.05.
* Utilizing the ARIMA model with setting 5,1,1 we received bad results with p-values higher than 0.05, 2,1,1 would have been a better fit.
* Utilizing the GARCH model with p=2 and q=1 we forecasted volatility with better results (with lower p values) compared to ARMA and ARIMA, the forecast shows an increase in volatility in the next five days.
* On the regression_analysis notebook we organized the data creating Returns and Lagged Returns columns, then we splitted the data for testing and training.
* Utilizing the linear regression models out-of-sample performance and in-sample perfomance we made returns prediction and then compared the two results to see which one was more reliable. In this case the out-of sample model outperfomed in-sample model with a lower rmse.
