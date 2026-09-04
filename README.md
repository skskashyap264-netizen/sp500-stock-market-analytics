# S&P 500 Stock Market Analytics

## 📌 Project Overview

This project analyzes historical S&P 500 stock market data to identify trends, relationships, volatility patterns, and factors influencing stock prices and returns.

The project combines exploratory data analysis, feature engineering, statistical analysis, machine learning, and time-series forecasting to generate meaningful insights from financial market data.

## 📊 Dataset

- Approximately 497K stock records
- Approximately 505 companies
- Historical stock price data from 2014–2017
- Key market variables include Open, High, Low, Close, and trading volume

## 🛠️ Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Statsmodels
- Jupyter Notebook

## 🔍 Analysis Performed

### Data Preparation
- Data cleaning and preprocessing
- Missing value and duplicate checks
- OHLC data validation
- Data quality assessment

### Exploratory Data Analysis
- Stock price trends
- Daily returns
- Volatility analysis
- Moving averages
- Correlation and covariance analysis
- Outlier detection
- Data visualizations

### Machine Learning

The project evaluates multiple regression models:

- Linear Regression
- Decision Tree
- Random Forest
- Gradient Boosting

Model performance was evaluated using:

- MAE
- MSE
- RMSE
- R²
- MAPE

Feature importance was also analyzed to understand which variables contributed most to model predictions.

### Time-Series Forecasting

ARIMA was used for time-series analysis and forecasting.

A chronological train-validation-test approach was followed to avoid using future observations when evaluating historical market data.

## 📈 Key Outcomes

The analysis provides insights into:

- Stock price and return behavior
- Market volatility
- Relationships between financial variables
- Important predictive features
- Performance differences across machine learning models
- Time-series patterns and forecasting behavior

## 💡 Business & Analytical Insights

The project demonstrates how financial market data can be used to support:

- Market trend analysis
- Risk and volatility assessment
- Comparative stock analysis
- Predictive modeling
- Data-driven investment research

## 📁 Project Structure

```text
sp500-stock-market-analytics/
│
├── S&P_500_Stock_Market_Analytics.ipynb
├── S&P 500 Stock Prices 2014-2017.xlsx
├── requirements.txt
└── README.md

## 🚀 How to Run

1. Download or clone this repository.
2. Install the required Python libraries using `requirements.txt`.
3. Open `S&P_500_Stock_Market_Analytics.ipynb` in Jupyter Notebook.
4. Run the notebook cells sequentially.
