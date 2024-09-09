# Project Title: Airline Passengers Forecasting

Problem Statement: Read and analyse the number of passengers travelling via a particular airline over the given period of time and implement statistical models like ARIMA and SARIMA to forecast the passengers count. Also, compare the both models's performance.

# Code Files Description:
1. Data_Preprocessing.ipynb:
Given Data is imported, read, undertood, analysed and prepared for model implementation.
Learnings: Data Normalisation, how to nullify trend, volatility and seasonal component.

2. Dickey–Fuller-Test.ipynb:
Explained Dickey–Fuller test implementation for both seasonal and non-seasonal data.

3. ARIMA_SARIMA_Implementation.ipynb: 
Implemented ARIMA and SARIMA models. Also, implemented ACF-PACF plots and how to decide AR and MA component for both models.

# Dataset Description:
File Name: airline-passengers.csv
It contains two columns; 
    column 1: Month (date) 
    column 2: Passengers (number of passengers travelled using particular airline during Jan. 1949 till Dec. 1960)

# Necessary Theory/Documentation:
1. What is Time Series Forecasting: [https://www.kaggle.com/code/freespirit08/time-series-for-beginners-with-arima/notebook]

2. Removing trend and stationarity: [https://machinelearningmastery.com/remove-trends-seasonality-difference-transform-python/]

3. ARIMA and SARIMA Implementation: [https://towardsdatascience.com/time-series-forecasting-with-arima-sarima-and-sarimax-ee61099e78f6]

Additional:
4. YouTube Playlist: Time Series Analysis by Ritvikmath [https://www.youtube.com/playlist?list=PLvcbYUQ5t0UHOLnBzl46_Q6QKtFgfMGc3]
