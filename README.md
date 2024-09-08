
# Finance Data Project

## Project Overview

In this project, we explore stock prices of major banks, focusing on their performance from the period of the 2008 financial crisis up to early 2016. This project is designed to help you practice **exploratory data analysis (EDA)**, **visualization**, and **pandas** skills. 

### Disclaimer
This project is purely educational and is **not intended as financial advice**. It is meant to strengthen your data analysis skills by working with real-world financial data. The analysis performed here is not exhaustive or comprehensive for making financial decisions.

## Objectives

The primary objectives of this project are:
- Perform exploratory data analysis on stock price data.
- Visualize trends, relationships, and patterns using **matplotlib** and **seaborn**.
- Practice essential **pandas** operations for working with time-series data.

## Dataset

The dataset consists of historical stock price data of major banks, including:
- **Bank of America**
- **Citigroup**
- **Goldman Sachs**
- **JPMorgan Chase**
- **Morgan Stanley**
- **Wells Fargo**

Each stock's data includes:
- **Date**: The date of the stock price.
- **Open**: The price at market opening.
- **High**: The highest price during the trading day.
- **Low**: The lowest price during the trading day.
- **Close**: The price at market close.
- **Volume**: The number of shares traded.
- **Ticker Symbol**: The symbol representing the bank's stock.

## Installation and Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/finance-data-project.git
   cd finance-data-project
   ```

2. Install required libraries:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the Jupyter Notebook:
   ```bash
   jupyter notebook
   ```

## Exploratory Data Analysis (EDA)

Key analyses performed in the project include:
- **Line Plot of Stock Prices**: Visualize the stock prices of each bank over time.
- **Moving Averages**: Calculate and plot moving averages to smooth out short-term fluctuations.
- **Correlation Analysis**: Use heatmaps to show correlations between stock prices of different banks.
- **Volatility**: Calculate and visualize the daily percentage change to analyze volatility.

### Example Visualizations

1. **Stock Price Line Plots**:
   - Line plots showing stock prices of each bank from 2008 to 2016.

2. **Moving Averages**:
   - Plotting the 30-day moving averages to smooth out the data and observe long-term trends.

3. **Heatmaps**:
   - A heatmap showing the correlation between the closing prices of different banks over the years.

## Key Results

- The stock prices during the financial crisis showed a sharp decline, particularly in **Citigroup** and **Bank of America**.
- Moving averages helped reveal overall trends in the stock prices, which were otherwise obscured by daily fluctuations.
- **Correlation analysis** showed a strong positive correlation between the stock prices of the major banks, particularly during periods of financial stability.

## Key Concepts and New Techniques

This project introduces several advanced concepts and techniques, including:
- **Working with time-series data** in pandas.
- **Calculating moving averages** and other rolling statistics.
- **Plotting with seaborn** to visualize correlations and patterns.
- **Volatility Analysis**: Analyzing daily percentage changes to understand the stock's risk and volatility.

## Conclusion

This project demonstrates how to perform exploratory data analysis on stock price data, providing valuable insights into how bank stocks moved before, during, and after the financial crisis. The practice with **pandas** and **visualization** tools in this project is useful for anyone looking to sharpen their data analysis skills.

## Next Steps

- Implement more sophisticated time-series models to predict future stock prices.
- Include additional features such as dividends or economic indicators to enhance the analysis.


