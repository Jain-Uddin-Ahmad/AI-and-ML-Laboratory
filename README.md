# Stock Market Prediction with Sentiment Analysis

Final project for **EEE 402: Artificial Intelligence and Machine Learning Laboratory** (BUET, January 2025). Group project, Section G2, Group 02.

The project predicts next-day stock closing prices by combining historical price data, technical indicators and the sentiment of daily news headlines.

## What's inside

| Path | Description |
|---|---|
| `notebooks/Sentiment_Analysis.ipynb` | Cleans Reddit world-news headlines and scores their sentiment with TextBlob |
| `notebooks/Model_Comparison.ipynb` | Compares Linear Regression, Random Forest, XGBoost, LSTM, GRU and a Transformer encoder |
| `notebooks/Final_EEE402_Project.ipynb` | Final LSTM models with technical indicators (RSI, MA7, MA20, MACD, Bollinger bands, EMA) and sentiment features, plus Random Forest and Linear Regression baselines |
| `notebooks/Prediction_with_interface.ipynb` | Interactive widget that predicts tomorrow's closing price |
| `data/RedditNews.csv` | Daily news headlines used for sentiment scores |
| `report/EEE402_Project_Report_group2.pdf` | Full project report |

## Tools

Python, pandas, scikit-learn, XGBoost, TensorFlow/Keras, TextBlob, yfinance, ipywidgets. The notebooks were developed in Google Colab.

## How to run

Open any notebook in Google Colab or Jupyter and run the cells from top to bottom.
