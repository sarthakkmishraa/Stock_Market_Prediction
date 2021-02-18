# Stock_Market_Prediction

## Dataset

The dataset consists of stock market prices of the company "Apple", the date and time variables and timestamps. The data has been collected through Tiingo API using pandas datareader library in Python.  It consists of 14 attributes(columns) and 1257 rows in total. 

Some of the important attributes in the dataset are as follows :

Date - specifies trading date

Open - opening price

High - maximum price during the day

Low - minimum price during the day

Close - close price adjusted for splits

Adj Close - adjusted close price adjusted for both dividends and splits.

Volume - the number of shares that changed hands during a given day


## Aim of the Project

The aim of this data science and machine learning project is to visualise the stock market data, clean the irrelevant features, split tha data into train and test dataset and then apply **Long Short Term Memory(LSTM)** algorithm which is a type of **Recurrent Neural Network(RNN)** to the train data. Finally we make prediction on the test data and compute the accuracy using **Mean Squared Error(MSE)** as the evaluation metric. Finally, we also predict the stock price for future 30 days using previously trained data.  
