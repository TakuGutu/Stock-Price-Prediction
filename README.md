# Stock-Market-Price-Prediction
A machine learning project exploring different approaches to predicting days when a stock’s price will go up.  
The goal is to predict future stock prices. On days that the stock price goes up, can it be predicted that it will go up?

## Project Contents
- **Historical data model.ipynb**  
  Uses raw historical stock prices downloaded from Yahoo Finance using the `yfinance` API.  
  A Random Forest Classifier is trained to predict whether the stock price will go up on the following day.  
  Precision is used as the primary evaluation metric.   
  The Notebook documents the full workflow: data collection, data cleaning, preprocessing, model design, testing and evaluation.

- **Moving_averages_model.ipynb**  
  Builds on the same prediction task but incorporates moving averages as features.   
  The Random Forest Classifier is again applied, with precision as the key metric.  
  The Notebook details how moving averages were engineered and integrated into the model.


## Disclaimer
No part of this project is financial advice.
