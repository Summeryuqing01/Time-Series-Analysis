# Ground Ozone Data Time Series Analysis/
final project for PSTAT 274/
This report observes the monthly average of ground-level ozone in Los Angeles, California from 2000 - 2020. Using data transformation and differencing, I find out that the original time series does not need transformation, and it has a seasonal pattern but no significant trend. I identified some models to fit by looking at the ACF anf PACF of differentiated time series, the best model with the lowest AICc for the time series is a seasonal ARIMA model with (p, d, q)×(P, D, Q) = (1, 0, 1)×(1, 1, 2).The best model past all the diagnostic checking so it is my final model for the time series. Finally, I forecast my model and compare my forecast with the testing set. The test data points shows that my model is good for predicting at least five time units, we will need to constantly update the data to make accurate predictions./
Programing language: R/
Source of data: Kaggle
