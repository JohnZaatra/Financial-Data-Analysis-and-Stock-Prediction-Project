## Financial Data Analysis and Stock Prediction Project

# Overview

This project focuses on analyzing stock market data, identifying trading opportunities, and predicting future price movements using various financial indicators and machine learning models. Key models used in this project include Logistic Regression, ARIMA, and LSTM to forecast stock price movements and guide trading decisions. The project also incorporates key metrics and statistical tools that support the predictions.
Key Metrics

1. Portfolio Optimization Metrics
* Max Returns Portfolio (Red): This portfolio provides the highest return but comes with high volatility. It is heavily weighted towards NVDA (84.11%).
* Safest Portfolio (Yellow): This portfolio offers the lowest risk but also provides lower returns. It is heavily weighted towards T (61.66%).
* Sharpe Portfolio (Green): The best balance between risk and return, maximizing the Sharpe ratio. It is diversified, but NVDA remains prominent (82.95%).
These portfolios provide insights into different risk-return trade-offs, helping to visualize the impact of various stock allocations.
2. Bollinger Bands
Interpretation & Insights:
Volatility: NVDA showed periods of high and low volatility, indicated by the width of the Bollinger Bands.
Strategy Effectiveness: The Bollinger Bands strategy generated modest profits, with buy signals near the lower band and sell signals near the upper band or when the price crosses above the moving average.
This indicator is essential for visualizing potential entry and exit points based on price volatility, helping traders make informed decisions.
3. Distribution Plot
Shape and Distribution:
Bell-Shaped Curve: NVDA's returns follow a normal distribution with most daily price changes being small.
Skew: A slight positive skew indicates that large positive returns are more likely than large losses.
Summary Statistics:
Median: 0.26%
Min: -18.76%
Max: 24.37%
Mean: 0.29%
5% & 95% Quantiles: -4.73% to 5.29%
This distribution plot reveals the general volatility and return characteristics of NVDA, offering a sense of typical daily price movements.
4. Moving Average Plot
Key Observations:
Buy/Sell Signals: The 12-day moving average (short-term) crossing above the 26-day moving average (long-term) signals potential buying opportunities, and vice versa for selling.
Profitability: The strategy yielded a 99.31% profit during the analyzed period, reflecting NVDA’s strong uptrend.
This moving average strategy helps identify key trading signals in trends, making it a vital tool for active traders.
5. RSI Plot
Key Observations:
RSI Oscillations: The RSI fluctuates, identifying overbought and oversold conditions.
Buy/Sell Signals: Buy signals occur when RSI falls below 30 (oversold) and sell signals when RSI rises above 60 (overbought).
Profitability: The RSI strategy yielded a profit of $82.38, with a return of 167.08%.
This RSI-based strategy is an effective momentum indicator for identifying price reversal points, crucial for short-term trading.
Key Models

1. Logistic Regression
Objective: Predict the probability of a stock’s price movement (up or down) based on historical features such as moving averages and RSI.
Approach: A binary classifier using features derived from technical indicators to determine the direction of future price movement.
Use Case: Helps generate buy or sell signals based on the predicted direction of price movement.
2. ARIMA (AutoRegressive Integrated Moving Average)
Objective: Forecast future stock prices based on historical price data and trend components.
Approach: ARIMA captures patterns from past price movements and trends (autoregressive, moving average, and integration) to make forecasts.
Use Case: Ideal for forecasting medium-term stock prices, providing a foundation for long-term trading strategies.
3. LSTM (Long Short-Term Memory)
Objective: Predict future stock prices by learning complex patterns in sequential data.
Approach: LSTM models use gates to retain or forget information, making them ideal for time series data. Trained on historical stock prices and technical indicators to make future predictions.
Use Case: Provides highly accurate predictions of future price movements, helping guide real-time trading decisions.
Conclusion

The combination of financial metrics (like portfolio analysis, Bollinger Bands, distribution plots, moving averages, and RSI) with advanced predictive models (Logistic Regression, ARIMA, and LSTM) offers a comprehensive approach to analyzing stock market data. These models are crucial for making informed trading decisions based on both short-term price movements and long-term trends.
