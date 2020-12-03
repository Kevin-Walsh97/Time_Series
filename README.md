# Time_Series

## Time Series Analysis - Conclusions

### Buy or Sell?

Based on the time series analysis above, I would not buy the yen now. When looking at the ARMA model, we do see that the daily return for the yen is expected to fall precipitously before stabilizing. However, when looking at the ARIMA model, we can see that the settle price of the yen is forecasted to rise continuously over the same time period. This difference in signaling can be confusing, but of course, it would be more clear if we only were looking at one model. When comparing the AIC/BIC figures for the ARMA and ARIMA model, we can see that the ARMA model outperformed. Knowing this, we can come to the conclusion that the daily returns for the yen will decline in the coming days and should, therefore, be avoided.

### Future Volatility

Using the GARCH model, the volatility, or the risk, is expected to rise for the yen heading into the future.

### Model Performance

After looking at the evaluation for the GARCH model, I would not be confident using it to perform trades. This is because it has a very low (0.000) R-squared value, which means that the volatility in the price of the yen is not, according to this model, at all explainable based on previous volatility and fluctuations in the underline asset price. 

I would, however, feel comfortable and confident using the ARMA and ARIMA models to enhance my trading decisions. This is because these two models use previous pricing information to predict future outcomes. As we can see from the plotting of the yen settle price and the trend data, there is a strong correlation between the two. Therefore, I would be more confident using the ARMA/ARIMA in the decision making process than the GARCH model.

## Regression Analysis - Conclusion

The model performed worse for out-of-sample (testing) data when compared to in-sample (training) data, as illustrated by the difference in the root mean squared error (RMSE) of the two data types. Because the training data outperformed the testing data, we can assume that there is some underfitting occuring. To remedy this, perhaps more data is required. This will allow for more accurate predictions of outcomes.