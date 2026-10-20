# Microsoft Stock Data Analysis

An exploratory data analysis (EDA) of historical daily stock data for **Microsoft (MSFT)**. The goal is to understand price trends, performance and volatility, and to pull out insights that can feed later modelling.

## Objectives

- Analyse price trends with time series plots
- Examine relationships between features with correlation heatmaps
- Smooth noise and spot momentum with **10-day and 50-day moving averages**
- Compute and visualise **daily returns** to measure risk and volatility
- Study the distribution of returns with histograms to check behaviour and outliers

## Dataset

Source file: `MSFT_daily_data.csv`

| Field | Description |
|-------|-------------|
| Date | Trading day |
| Open, High, Low, Close | Daily price range |
| Volume | Shares traded |

## Insights

- MSFT shows clear upward trends with periods of high volatility.
- Price variables are strongly correlated, while volume behaves independently.
- Moving averages help show trend shifts and possible support and resistance levels.
- Daily returns are mostly stable with occasional extreme spikes.
- The return distribution is centred around zero but shows fat tails, a sign of tail risk.

This analysis is a foundation for trading strategies, risk models or forecasting work built on historical price behaviour.

## Files

| File | Description |
|------|-------------|
| `masft_data_analysis.ipynb` | Analysis notebook |
| `MSFT_daily_data.csv` | Historical daily MSFT data |

## Run it

```bash
pip install pandas matplotlib seaborn jupyter
jupyter notebook masft_data_analysis.ipynb
```

## Tech stack

Python, pandas, matplotlib, seaborn, Jupyter Notebook

## Disclaimer

This is an educational analysis of historical data. It is not financial advice.


---

<sub>Made by [tanaytejush](https://github.com/tanaytejush)</sub>
