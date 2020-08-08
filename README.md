# Predict Future Sales
* This is repository is for the Kaggle Competition Predict Future Sales for the next month. 
* We cleaned the data and Data Analysis and Feature Engineering from different perspectives to know in-detail about the sales
* Then we dealed with the outliers in item_cnt_day and item_price.
* Then for the Time Series Analysis we did the tests to check the stationary, for this we used Dickey-Fuller test.
* For our model building we used are  ARIMA model and also with LSTM.


## Resources We Used
* Jupyter Notebook
* We used pandas, numpy, sklearn, matplotlib, seaborn, statsmodels.
* Kaggle Dataset: https://www.kaggle.com/c/competitive-data-science-predict-future-sales/overview


## Data Cleaning and Data Analysis
* We analyzed and cleaned this dataset so it can be usable for our model.
* And in Data Analysis part, we simplified our data and also analyzed with graphs
* We did Time Series Analysis with different perspectives.

## Model Building
* With ARIMA Model we predict sales for the next 6 months
* And with LSTM model we predict sales for the next month only (which was required)
* We got **mean_squared_error: 6.1309** from LSTM
