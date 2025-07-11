Microsoft-Stock-Data-Analysis:

This project performs an in-depth Exploratory Data Analysis (EDA) on historical daily stock data for Microsoft (MSFT). The goal is to uncover trends, evaluate performance, understand volatility, and extract actionable insights from the stock's price behavior over time.

Key Objectives:
Analyze price trends using time series plots.

Examine interdependencies between features using correlation heatmaps.

Smooth out noise and identify momentum with 10-day and 50-day moving averages.

Compute and visualize daily returns to measure risk and volatility.

Study the distribution of returns using histograms to assess behavior and outliers.

🛠️ Tools & Libraries Used:
Python

Pandas

Matplotlib

Seaborn

Jupyter Notebook

📁 Dataset:
Source: MSFT_daily_data.csv

Fields include: Date, Open, High, Low, Close, Volume

📈 Insights:
MSFT stock exhibits clear upward trends and periods of high volatility.

Price-related variables are strongly correlated, while volume behaves independently.

Moving averages help visualize trend shifts and potential support/resistance levels.

Daily returns are mostly stable with occasional extreme spikes.

Return distribution is centered around zero but shows signs of fat tails (risk).

This analysis serves as a foundational step toward developing trading strategies, risk assessment models, or forecasting tools based on historical stock behavior.
