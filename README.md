# Stock Market Movement Prediction using ML/DL

This project predicts the **directional movement (up/down)** of next-day stock prices for NIFTY 100 stocks using Machine Learning and Deep Learning techniques.

## 🔍 Overview
- 📈 Models used: LSTM, XGBoost, Random Forest, CatBoost
- 🧠 Features: EMA, RSI, MACD, ATR, ADX, Bollinger Bands, Lag returns
- 📊 Evaluation: RMSE, MAPE, Hit-Ratio (Threshold-based directional accuracy)
- 📅 Data span: 20 years (2005–2025)

## 🗂️ Project Structure
- `data/`: Contains stock data like `ABB.NS_data.csv`
- `notebooks/`: Jupyter Notebooks for feature engineering and training
- `models/`: (Optional) Save trained models here
- `requirements.txt`: List of Python dependencies

## ⚙️ Requirements
```bash
pip install -r requirements.txt
