# Time_Series

## Time Series Analysis - Conclusions

### Buy or Sell?

Based on the time series analysis above I would not buy the yen now. When looking at the ARMA model, we do see that the daily return for the yen is expected to fall precipitously before stabilizing. However, when looking at the ARIMA model, we can see that the settle price of the yen is forecasted to rise continuously over the same time period. This start difference in signaling can be confusing, but of course, it would be clearly if we only were looking at one model. When comparing the AIC/BIC figures for the ARMA and ARIMA model, we can see that the ARMA model outperformed. Knowing this, we can come to the conclusion that the daily returns for the yen will decline in the coming days and should, therefore, be avoided.

### Future Volatility

Using the GARCH model, the volatility, or the risk, is expected to rise for the yen heading into the future.

### Model Performance



## Regression Analysis - Conclusion

The model performed worse for out-of-sample (testing) data when compared to in-sample (training) data when we compare the root mean squared error (RMSE) of the two data types. Because the training data outperformed the testing data we can assume that there is some underfitting occuring and perhaps more data is required to more accurately predicted outcomes.