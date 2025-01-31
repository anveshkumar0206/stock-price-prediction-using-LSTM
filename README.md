# stock-price-prediction-using-LSTM

Project Overview
It's a project on the use of the long short-term memory neural network with PyTorch to predict stock prices. The project involves:

Importing the stock price data from a .csv file
Preprocessing the dataset for LSTM training
Dividing the dataset into an 80-20 ratio of training and testing, respectively
Building and training an LSTM model with PyTorch
Model performance evaluation with visualization.

Installation
Ensure that you have the required dependencies installed before running the notebook:
install numpy pandas matplotlib scikit-learn torch

Dataset
The project uses Google stock price data, loaded from a .csv file. 

The dataset includes:
Date: Timestamp of the stock price,
Open: Opening price of the stock,
High/Low/Close: Prices at different points of the trading day,
Volume: Number of shares traded

LSTM Model Workflow
1.Data Preprocessing
Normalize stock prices using MinMax scaling to improve model performance.
Convert the dataset into sequential time series data.
2.Train-Test Split
The dataset is divided into 80% training data and 20% testing data.
3.LSTM Model Training with PyTorch
The LSTM model is implemented through PyTorch's nn.LSTM layer.
Model training is based on MSE Loss and an Adam optimizer.
4.Evaluation
Stock price is predicted using a trained model.
Visualization of loss values and predictions using Matplotlib.

Results
The model’s predictions are compared with actual stock prices.
Evaluation metrics such as Root Mean Squared Error (RMSE) are used to measure accuracy.
