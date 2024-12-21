# Data Card

Enter basic information about your dataset here.

# Data Card: NIFTY-50 Stock Market Data (2000 - 2021)

## Overview
The dataset provides historical price and trading volume information for the fifty stocks listed on the NIFTY 50 index from the National Stock Exchange (NSE) of India. This comprehensive dataset spans over two decades, from **January 1, 2000, to April 30, 2021**, and includes daily trading data for each stock in the index.

## Key Features
### Scope
- **Index**: NIFTY 50 (National Stock Exchange of India)
- **Time Period**: January 1, 2000 – April 30, 2021
- **Granularity**: Daily-level data
- **Stocks**: 50 constituent stocks of the NIFTY 50 index
- **File Format**: Individual CSV files for each stock along with a metadata file providing macro-information about the stocks.

### Data Columns
The dataset includes the following columns across all stock data files:

1. **Date**: The trading date for the data entry.
2. **Symbol**: The unique identifier or name of the stock.
3. **Series**: The type of security (e.g., EQ for equity shares).
4. **Prev Close**: The stock’s closing price on the previous trading day.
5. **Open**: The opening price for the trading day.
6. **High**: The highest price achieved during the trading day.
7. **Low**: The lowest price recorded during the trading day.
8. **Last**: The last traded price of the stock for the day.
9. **Close**: The final closing price of the stock for the trading day.
10. **VWAP**: Volume-weighted average price. It represents the average price at which the stock was traded during the day, weighted by trading volume. Formula: 
   \[
   \text{VWAP} = \frac{\text{Cumulative Price × Volume}}{\text{Cumulative Volume}}
   \]
11. **Volume**: The total number of shares traded during the day.
12. **Turnover**: The turnover ratio, representing the ratio of sellers to buyers for a particular stock.
13. **Trades**: The number of trades executed for the stock during the trading day.
14. **Deliverable Volume**: The quantity of stock shares that were physically delivered to the buyer.
15. **%Deliverable**: The percentage of traded shares that were delivered.

### Key Notes
- **Currency**: All prices are recorded in **Indian Rupees (₹)**.
- **Volume Metrics**: The dataset includes both total trading volume and deliverable volume, providing insights into market liquidity and stock delivery patterns.

## Applications
This dataset is well-suited for the following analytical use cases:
1. **Stock Price Prediction**: Using historical prices to predict future trends.
2. **Market Trend Analysis**: Evaluating market patterns over time.
3. **Risk Assessment**: Analyzing stock volatility based on high and low prices.
4. **Trading Strategy Development**: Crafting intraday or long-term investment strategies.
5. **Feature Engineering**: Calculating technical indicators like moving averages, RSI (Relative Strength Index), and Bollinger Bands.
6. **Interpretability**: Understanding the relationship between key stock attributes such as VWAP, turnover, and deliverable volume.

## Considerations
- **Data Quality**: Ensure proper handling of missing or erroneous data points in time-series analysis.
- **Data Size**: Given the long time span and daily granularity for 50 stocks, computational optimization might be required for large-scale analyses.
- **Real-world Context**: Combine this dataset with macroeconomic factors (e.g., interest rates, inflation) for enhanced predictions and insights.

This dataset provides a robust foundation for financial modeling, machine learning, and data-driven decision-making in the stock market domain.
