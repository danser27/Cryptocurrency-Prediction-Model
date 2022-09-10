# Cryptocurrency-Prediction-Model

In this notebook an analysis on BTC crypto currency is done.

Data:  
- Collected in form of daily OHLC.
- Span from 25 Sep 2019 to 10 Sep 2022. 
- Provider is 'cryptowat' API.

The input data are set in a way to be easily adjusted to let the user experiment and running the same analysis, with other crypto currencies too.

In the eploratory data section, functions are created in such a way to be easily manipulated accordingly to the user willingness to explore and change such parameters to facilitate technical analysis.

An overview on more classical econometric model is also performed (ARIMA) before exploring more recent machine learning algorithms like: Linear Regression, RidgeCV, LassoCV, Stochastic Gradient Descendent. 

After hyperpameters tuning LassoCV has been selected as the best model and saved.
