# XRP Crypto Analysis

Welcome to Crypto XRP Analysis — a project aimed at uncovering meaningful insights about the XRP cryptocurrency through data-driven techniques. This repository contains tools and notebooks that help analyze XRP price trends, correlations, and performance using Python.

## Work Completed

### Data Acquisition
- Collected historical XRP-USDT price data from Binance via `ccxt` and `yfinance`.
- Cleaned and formatted time-series data for analysis.

### Feature Engineering
- Generated a comprehensive set of technical indicators:
  - RSI, MACD, Bollinger Bands, Moving Averages
  - Price momentum, volatility, and volume metrics
- Saved feature enginered dataset as: `xrpusdt_features.csv`

### Exploratory Data Analysis (EDA)
- Visualized feature distributions and market behavior.
- Explored volatility patterns and price trends.
- Plotted indicator overlays on candlestick charts.

### Modeling Preparation
- ETL pipeline completed and clean dataset ready for training.
- Target variable setup and label encoding underway.

### Forecasting and Prediction
- Develop predictive models (Random Forest, XGBoost, LSTM)
- Evaluate model performance and metrics (In progress)

## Next Steps
- Build a dashboard for decision support using predictions

## Project Structure

### 📁 `data/`
- `raw/` – Original raw data files.
- `combined/` – Aggregated files after merge.
- `cleaned/` – ETL output & features ready for modeling.

### 📁 `notebooks/`
- [`01_xrpusdt_data_etl.ipynb`](notebooks/01_xrpusdt_data_etl.ipynb) – Data collection & ETL process.
- [`02_exploratory_data_analysis.ipynb`](notebooks/02_exploratory_data_analysis.ipynb) – Initial exploration.
- [`03_feature_engineering.ipynb`](notebooks/03_feature_engineering.ipynb) – Technical indicators enrichment.
- [`04_forecasting_and_prediction_models.ipynb`](notebooks/04_forecasting_and_prediction_models.ipynb) – Modeling & evaluation.

### 📄 Configuration & Metadata
- `.gitignore` – Ignore patterns for version control.
- `LICENSE` – Usage and redistribution terms.
- `README.md` – Summary and project log.

## Contributions

Pull requests are welcome! Feel free to contribute new indicators, modeling techniques, or visualizations.
