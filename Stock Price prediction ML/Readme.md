# 6. Stock Price Prediction using LSTM

## Overview :-
This project aims to predict Apple (AAPL) stock prices using Deep Learning techniques. The project uses historical stock market data and an LSTM (Long Short-Term Memory) model to learn patterns in stock prices and generate predictions.

## Dataset :-
The dataset used in this project is provided as a CSV file named "stocks_5yr.csv". It contains historical stock market information including date, open price, close price, high price, low price, volume, and company name.
**NOTE** : The dataset is too large and exceeds GitHub’s file size limit, so I couldn’t upload it.


## The following tools and technologies were used in this project:
* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* TensorFlow
* Keras
* Jupyter Notebook

## Preprocessing :-
* Loading the Dataset: Read and explore the stock market dataset using pandas.
* Exploratory Data Analysis: Analyze stock prices, trading volume, and price trends.
* Data Selection: Select Apple (AAPL) stock data for prediction.
* Feature Scaling: Scale the closing price using MinMaxScaler.
* Sequence Creation: Create sequences using the previous 60 days of stock prices.
* Splitting the Data: Split the data into training and testing sets.

## Model Selection :-
An LSTM model is built using TensorFlow and Keras for stock price prediction. The model consists of LSTM layers followed by Dense and Dropout layers. The model is compiled using the Adam optimizer and Mean Squared Error loss function. The model is trained on historical stock price sequences and evaluated using MSE and RMSE.


# Note :-
This projects was developed primarily to improve my practical experience and build strong hands-on expertise in Machine Learning tools and workflows.


