# 📊 Crypto XRP Analysis

A data-driven exploration of the XRP-USDT market using technical indicators, feature engineering, and machine learning workflows.

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

### 🧪 Modeling Preparation *(in progress)*
- ETL pipeline completed and clean dataset ready for training.
- Target variable setup and label encoding underway.

## 🚀 Next Steps
- Develop predictive models (Random Forest, XGBoost, LSTM)
- Evaluate model performance and metrics
- Build a dashboard for decision support using predictions

## 🧱 Project Structure

crypto-xrp-analysis/
├── 📂 data/

│   ├── 📁 raw/               # Original raw data files

│   ├── 📁 combined/          # Merged and aggregated data files
│   └── 📁 cleaned/           # ETL output and feature-engineered datasets
├── 📔 notebooks/
│   ├── 📘 [01_xrpusdt_data_etl.ipynb](notebooks/01_xrpusdt_data_etl.ipynb) — Data collection and ETL
│   ├── 📗 [02_exploratory_data_analysis.ipynb](notebooks/02_exploratory_data_analysis.ipynb) — Initial data exploration & visualization
│   └── 📙 [03_feature_engineering.ipynb](notebooks/03_feature_engineering.ipynb) — Technical indicators & dataset enrichment
├── 📄 .gitignore            # Git config to ignore unnecessary files
├── 📄 LICENSE               # License info for usage and distribution
└── 📝 README.md             # Project summary and progress tracker


## 🤝 Contributions

Pull requests are welcome! Feel free to contribute new indicators, modeling techniques, or visualizations.
