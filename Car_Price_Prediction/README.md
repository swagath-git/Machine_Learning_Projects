# Stock Price Prediction

## Project Overview

This project focuses on predicting stock prices using a Long Short-Term Memory (LSTM) neural network built with TensorFlow.

The project uses historical stock market data containing daily Open, High, Low, Close, Volume, and Company Name information. Exploratory Data Analysis (EDA) was performed on multiple companies, followed by detailed analysis and prediction of Apple (AAPL) stock prices.

The main objective is to understand historical stock price patterns and use time-series data to predict future closing prices.

---

## Objectives
- Analyze historical stock market data.
- Explore stock price trends across multiple companies.
- Perform Exploratory Data Analysis using visualizations.
- Analyze Apple's historical stock closing prices.
- Prepare time-series data for machine learning.
- Build an LSTM neural network using TensorFlow.
- Predict Apple's stock closing prices.
- Evaluate model performance using MSE and RMSE.
- Compare actual and predicted stock prices visually.

---

## Dataset
The **dataset** used in this project is **not included** in this repository **because** of GitHub file **size limitations**. It was obtained from the **kaggle**.

The project notebook contains the complete data preprocessing, analysis, and model-building steps.
The dataset contains historical stock market data with the following columns:

- `date`
- `open`
- `high`
- `low`
- `close`
- `volume`
- `Name`

The dataset contains **619,040 records** covering multiple companies.
For the prediction task, the analysis focuses on **Apple (AAPL)** stock data from approximately 2013 to 2018.

---

## Exploratory Data Analysis
EDA was performed to understand stock price behavior across companies such as:

- Apple (AAPL)
- AMD
- Facebook (FB)
- Google (GOOGL)
- Amazon (AMZN)
- NVIDIA (NVDA)
- eBay (EBAY)
- Cisco (CSCO)
- IBM

The analysis included visualization of:
- Opening stock prices
- Closing stock prices
- Historical price trends
- Company-wise stock price movements

---

## Data Preprocessing
The following preprocessing steps were performed:

1. Converted the `date` column into DateTime format.
2. Filtered the dataset for Apple (`AAPL`).
3. Selected the `close` price for prediction.
4. Used **MinMaxScaler** to normalize the closing price between 0 and 1.
5. Split the data into training and testing sets.
6. Created time-series sequences using the previous **60 days** of stock prices.

---

## LSTM Model
A Long Short-Term Memory (LSTM) neural network was built using TensorFlow/Keras.

### Model Architecture
- LSTM layer with 64 units
- LSTM layer with 64 units
- Dense layer with 32 units
- Dropout layer with 0.5 dropout rate
- Output Dense layer with 1 unit

The model was compiled using:
- **Optimizer:** Adam
- **Loss Function:** Mean Squared Error
- **Epochs:** 10

---

## Model Evaluation
The trained model was evaluated on the test dataset using:
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)

### Results

| Metric | Result |
|---|---:|
| MSE | 20.28 |
| RMSE | 4.50 |

The actual and predicted Apple closing prices were also visualized to compare the model's predictions with the test data.

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- TensorFlow
- Keras
- Scikit-learn
- Jupyter Notebook

---
> **Note:** This project is for educational and learning purposes. Stock market predictions are not guaranteed to accurately represent future market prices and should not be considered financial advice
