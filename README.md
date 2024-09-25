# Stock Price Prediction and Forecasting Using LSTM
## 📋 Table of Contents
- Introduction
- Technologies Used
- Dataset
- Model Architecture
- Usage
- Results

## 📖 Introduction
This project focuses on predicting and forecasting stock prices using **Long Short-Term Memory (LSTM) neural networks**. LSTM is a type of Recurrent Neural Network (RNN) that is well-suited for time series prediction due to its ability to capture long-term dependencies in sequential data.

The goal is to use historical stock prices to forecast future prices, allowing us to analyze trends and potential investment opportunities.

## 🛠 Technologies Used
- **Python:** Core programming language.
- **TensorFlow / Keras:** For building and training the LSTM model.
- **Pandas:** Data manipulation and preprocessing.
- **NumPy:** For numerical computations.
- **Matplotlib / Seaborn:** Data visualization.
- **Scikit-learn:** For data scaling and evaluation metrics.

## 📊 Dataset
The dataset used in this project consists of historical stock prices from TATAGLOBAL, including Open, High, Low, Close prices, Turnover and Total Trade Quantity for various dates.
You can use datasets from sources like Yahoo Finance, Alpha Vantage, or any publicly available stock price data.
Ensure the dataset is formatted as a CSV file, with relevant columns like Date, Open, Close, High, Low, and Volume.

## 🧠 Model Architecture
We use LSTM (Long Short-Term Memory), a variant of RNNs that is ideal for time series forecasting due to its capability to remember long-term dependencies in the data. The LSTM model predicts the stock price based on historical price movements.

- **Input Layer:** Sequential stock price data.
- **Hidden Layers:** One or more LSTM layers with dropout for regularization.
- **Output Layer:** A dense layer predicting the next day's stock price.

# 📈 Results


**Model Performance:** Orange and green indicate the Predicted stock prices and blue indicate the actual stock prices.

![image](https://github.com/user-attachments/assets/53344e9f-08da-49ca-bc4f-beed0531332a)

**Evaluation Metrics:** The Root Mean Squared Error (RMSE) of the actual data is 161 whereas the RMSE score of the predicted data is 107 . As the RMSE score has reduced the models performance is good.
