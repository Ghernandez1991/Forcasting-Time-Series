# Forecasting-Time-Series


Quick example of using python to forecast values when the data consists of a time series.

We use an autoregression model (similar to linear regression) although with key differences such as lag variables. 

Assumptions that are made prior to working with data and an autoregression model. 


-The previous time steps are useful in predicting the value at the next time step. (there is a dependence between values)


-Your data is stationary. A stationary time series will have a mean that is constant over time. There are other factors but this is usually the fastest. 


-Libraries used
Pandas
Matplotlib
pd.plotting
Statsmodels seasonal_decompose

statsmodels AR model--auto selects our lag value
sklean.metrics r2_score- used to determine the proportion of vairance in the dependent variable that can be predicted from the independent variable(s). 


