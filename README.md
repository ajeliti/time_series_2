# Practice: Time Series for Products sold in a store

The dataset contains simulated time series data covering 10 years (2010-2019). The features include date, store id, product id and number sold. The train.csv covers the years 2010-2018 and the test.csv covers 2019 only. The are 7 unique stores and 10 unique products. The are no null values. The objective is to predict the number sold feature in the test.csv

For this project, we try to predict the number of products sold in store 0 and specifically product 0. To do our predictions, we try to perform modeling using Arima, then prophet and finally pycaret(which combines different models and chooses the best fit).

After modeling and evaluating our results using RMSE, prophet performs the best with and RMSE of 12.03, compared to Arima with 16.53, and pycaret( chose AutoArima) with 36.87.
