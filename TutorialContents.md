## Tutorials on Building-level Data Analytics

**Prepared by [Manisa Pipattanasomporn](https://mpipatta.github.io)**

During the past several years, I have been involved in smart building research. I would like to create this set of tutorials to share the knowledge that I learned, related to building-level data analytics, building-level load forecasting and more.

This page was created in December 2019, and contents will be added as they become available!

* [Work with CU-BEMS Data: Chamchuri 5 building:](https://nbviewer.jupyter.org/github/mpipatta/mpipatta.github.io/blob/master/CHAM5.ipynb) This notebook explores the CU-BEMS dataset of Chamchuri 5 building. Chamchuri 5 is a seven-story academic office building located at Chulalongkorn University, Thailand. Recorded data are: power consumption (kW) of individual AC units, lighting and plug loads in each zone, on each floor of the building, together with corresponding indoor temperature (deg C), humidity (%) and illuminance (lux) in each zone. 

* [Working with time-series data](https://nbviewer.jupyter.org/github/mpipatta/mpipatta.github.io/blob/master/tutorials/Day1(a)_ReviewBasicPython.ipynb) Python is powerful to handle time series data. In this tutorial, we will learn: how to import time-series data, how to deal with missing time-series data, how to filter a selected time range, how to visualize time-series data and how to resample time-series data.

* [Load forecasting: Lookback forecasting:](https://nbviewer.jupyter.org/github/mpipatta/mpipatta.github.io/blob/master/tutorials/Day2(a)_LookbackForecasting.ipynb) This is the simplest method for load forecasting. Let's see what are the resulting error metrics (RMSE, MAPE) using this method. 

* [Load forecasting: Multiple linear regression (MLR):](https://nbviewer.jupyter.org/github/mpipatta/mpipatta.github.io/blob/master/tutorials/Day2(b)-MLR.ipynb) One of the most basic ML is multiple linear regression. In this tutorial, we will use MLR to perform hour-ahead load forecasting when Lt-1, t_outdoor and others are inputs to the forecasting model. The LinearRegression model from sklearn.linear_model was used.

* [Load forecasting: Autoregression model (AR):](https://nbviewer.jupyter.org/github/mpipatta/mpipatta.github.io/blob/master/tutorials/Day2(c)_Autoregression.ipynb) Autoregression is a linear regression model that uses lagged variables as inputs to predict the value at the next time step. This tutorial uses AR model from statsmodels.tsa.ar_model to automatically chooses optimal lag values for the model.

* [Load forecasting: Artifical Neural Network (ANN):](https://nbviewer.jupyter.org/github/mpipatta/mpipatta.github.io/blob/master/tutorials/Day2(d)-ANN.ipynb) We will use ANN model (keras library) to perform hour-ahead load forecasting.

* [Load forecasting: LSTM](https://nbviewer.jupyter.org/github/mpipatta/mpipatta.github.io/blob/master/tutorials/Day2(e)-LSTM.ipynb) and [BiLSTM](https://nbviewer.jupyter.org/github/mpipatta/mpipatta.github.io/blob/master/tutorials/Day2(f)-BiLSTM.ipynb): We will use LSTM and BiLSTM (keras library) for hour-ahead load forecasting.

For those who would like to review commonly used Python codes/libraries for data analytics, please refer to [ReviewBasicPython.ipynb](https://nbviewer.jupyter.org/github/mpipatta/mpipatta.github.io/blob/master/tutorials/Day1(a)_ReviewBasicPython.ipynb). 
