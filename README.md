# Nvidia Stock Price Prediction 📈🔮
### 👤 Project Owner : Putanyn Manee 🇹🇭 🙇🏻‍♂️

This project aims to predict Nvidia stock prices using Long Short-Term Memory (LSTM) networks and Monte Carlo simulations.

## Overview 🔍

We use historical stock data for Nvidia (NVDA) to train our models and make future price predictions. The project compares two approaches:

1. LSTM Standalone Model
2. LSTM with Monte Carlo Simulations

## Data 📊

We get our stock data from Yahoo Finance, covering the period from 2000 to 2023.

## Methods 🧠

- Data Preprocessing: We clean and prepare the data for our models.
- LSTM Model: We use a neural network with LSTM layers to learn patterns in the stock prices.
- Monte Carlo Simulations: We run many simulations to account for uncertainty in our predictions.

## Results 📉

Our LSTM Standalone Model performed well, with:
- Mean Squared Error (MSE): 10.49
- Mean Absolute Error (MAE): 1.98
- Root Mean Squared Error (RMSE): 3.24
- Mean Absolute Percentage Error (MAPE): 7.79%
- R-squared (R²): 0.93

The LSTM with Monte Carlo Simulations did not perform as well.

## How to Use 🚀

1. Clone this repository
2. Install the required packages:
   ```
   Look at the import statements in the first code cell of 
   'stock_price_prediction_lstm_montecarlo.ipynb' for a list of required packages.
   Key libraries include pandas 🐼, numpy 🔢, matplotlib 📊, tensorflow 🧠, and yfinance 📈.
   ```
3. Run the Jupyter notebook: `stock_price_prediction_lstm_montecarlo.ipynb`

## Limitations ⚠️

Remember that stock prices are affected by many factors. This model is for educational purposes only and should not be used for real trading decisions.

## Future Work 🔮

- Try different model architectures
- Include more features like company financials or market trends
- Explore other prediction methods

## Project Context 🎓

This work was completed on 16 Mar 2024 as part of the learning in class 961742 - APP ANN and VAR, MSc in Data Science program at Chiangmai University, Thailand.

## License 📄

This project is free to use. No specific license is applied. Feel free to use, modify, and distribute the code as you see fit.
