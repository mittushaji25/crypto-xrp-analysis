# 📊 XRP Crypto Analysis

Welcome to Crypto XRP Analysis — a project aimed at uncovering meaningful insights about the XRP cryptocurrency through data-driven techniques. This repository contains tools and notebooks that help analyze XRP price trends, correlations, and performance using Python.

## 🧠 Work Completed

### ✅ Data Acquisition
- Collected historical XRP-USDT price data from Binance via `ccxt` and `yfinance`.
- Cleaned and formatted time-series data for analysis.

### 🛠 Feature Engineering
- Generated a comprehensive set of technical indicators:
  - RSI, MACD, Bollinger Bands, Moving Averages
  - Price momentum, volatility, and volume metrics
- Saved feature enginered dataset as: `xrpusdt_features.csv`

### 📈 Exploratory Data Analysis (EDA)
- Visualized feature distributions and market behavior.
- Explored volatility patterns and price trends.
- Plotted indicator overlays on candlestick charts.

### 🧪 Modeling Preparation
- ETL pipeline completed and clean dataset ready for training.
- Target variable setup and label encoding underway.

### Forecasting and Prediction
- Develop predictive models (Random Forest, XGBoost, LSTM)
- Evaluate model performance and metrics (In progress)

## 🚀 Next Steps
- Build a dashboard for decision support using predictions

## 🧱 Project Structure

crypto-xrp-analysis/</br>
├── 📂 data/</br>
│   ├── 📁 raw/ — Original raw data files</br>
│   ├── 📁 combined/ — Merged and aggregated data files</br>
│   └── 📁 cleaned/ — ETL output and feature-engineered datasets</br>
├── 📔 notebooks/</br>
│   ├──  [01_xrpusdt_data_etl.ipynb](notebooks/01_xrpusdt_data_etl.ipynb) — Data collection and ETL</br>
│   ├──  [02_exploratory_data_analysis.ipynb](notebooks/02_exploratory_data_analysis.ipynb) — Initial data exploration & visualization</br>
|   ├──  [03_feature_engineering.ipynb](notebooks/03_feature_engineering.ipynb) — Technical indicators & dataset enrichment</br>
│   └──  [04_forecasting_and_prediction_models.ipynb](notebooks/04_forecasting_and_prediction_models.ipynb) — Predictive modelling, model evaluation & visualizations </br>
├── 📄 .gitignore — Git config to ignore unnecessary files</br>
├── 📄 LICENSE — License info for usage and distribution</br>
└── 📝 README.md — Project summary and progress tracker</br>

## 🤝 Contributions

Pull requests are welcome! Feel free to contribute new indicators, modeling techniques, or visualizations.
