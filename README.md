# Cryptocurrency Price Prediction and Sentiment Analysis

This Python script allows you to predict cryptocurrency prices using a Long Short-Term Memory (LSTM) model and perform sentiment analysis on related news articles.

## Prerequisites

Before running the script, make sure you have the following libraries and tools installed:

- Python 3.x
- pip (Python package manager)

You can install the required Python libraries by running:

```bash
pip install requests csv nltk pandas numpy keras scikit-learn ipywidgets yfinance
Usage
Clone this repository to your local machine or download the files as a ZIP archive.

Open the Jupyter Notebook Cryptocurrency_Price_Prediction_Tool.ipynb using Jupyter Notebook or Jupyter Lab.

Run the code cells in the notebook to execute the cryptocurrency price predictions.

Choose the prediction mode:

Single Crypto Prediction: Predict the price of a single cryptocurrency on a specific date.
Multi Crypto Prediction: Predict the prices of multiple cryptocurrencies on a specific date.
Follow the instructions in the notebook to input the necessary information, such as the target cryptocurrency and target date.

The predictions will be displayed, including the predicted prices and risk scores for each cryptocurrency.

Available Cryptocurrencies
The tool uses historical price data for the following cryptocurrencies:

Bitcoin (BTC)
Ethereum (ETH)
Ripple (XRP)
[Add more cryptocurrencies to this list]
Notes
The prediction results are not financial advice and should be used for informational purposes only.

The tool uses historical data for prediction and may not accurately reflect future cryptocurrency prices.

The risk score is a relative measure that indicates the potential risk associated with a predicted price change.

This tool uses LSTM neural networks, which are commonly used for sequence prediction tasks like time series forecasting.

The tool fetches historical price data from Yahoo Finance. However, there might be instances where some cryptocurrencies have insufficient data for prediction.

For multiple cryptocurrency predictions, the tool will display the top 5 cryptocurrencies with the highest risk scores, medium risk scores, and lowest risk scores.

The highest profit prediction will show the cryptocurrencies that have the highest predicted prices on the target date.

Please replace [Add more cryptocurrencies to this list] with the actual list of available cryptocurrencies in your tickers list. Additionally, ensure that you have the correct libraries installed before running the code.
