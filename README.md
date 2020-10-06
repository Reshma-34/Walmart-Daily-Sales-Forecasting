### Forecasts Walmart's daily department sales

#### Problem Statement:
Forecast daily department sales of Walmart retail stores for 28 days across California, Wisconsin and Texas in the United States. The accurate forecasting will help in setting up appropriate inventory levels, reduce forecasting risk, minimize waste and also help to understand sales pattern to drive demand generation.


#### Datasets:
Main dataset: 30,490 hierarchical time series
States: 3 California (CA), Texas (TX), and Wisconsin (WI)
Departments: 7 Food (3), Hobbies (2), Household (2)
Stores : 10 CA(4), TX (3), WI(3)
Items: 3049

Additional Dataset
Weekly sales price of an item
Calendar with events such as national holidays, valentine day, superbowls etc..
Snap food stamps: Supplemental Nutrition Assistance Program (SNAP)

Timeframe
2011/01/29 to 2016/04/26 (1913 days)

#### Modelling:
Univariate Models:
1.SNaïve
2.Holt Winters
3.Exponential Smoothing
4.SARIMA

Multivariate Models:
1.ARIMA + Fourier
2.SARIMAX
3.Hybrid Model (SARIMAX + LSTM) (G. Peter Zhang Time series forecasting using a hybrid ARIMA and neural network model, 2001, Elsevier Science

Data Split:
1.By State (3)
2.By Category (3)
3.By Department (7)

#### Metric:
RMSE : The Root Mean Squared Error is defined as the square root of the average squared error.

MASE : It is the mean absolute error of the forecast values, divided by the mean absolute error of the in sample one step naive forecast.
