Trader Performance vs Market Sentiment (Project Overview)

Objective
This project analyzes the relationship between Bitcoin market sentiment (Fear & Greed) and trader performance using Hyperliquid trading data. The goal is to identify patterns in profitability, risk behavior, and trading strategies based on market sentiment.

Data Description
Two datasets are used:

Bitcoin Market Sentiment dataset containing Date and Classification (Fear/Greed)
Historical Trader dataset containing account, symbol, execution price, size, side, timestamp, closedPnL, and leverage
Data Preparation
Loaded both datasets using pandas
Cleaned column names and handled missing values
Converted timestamp into date format for alignment
Merged both datasets on date to link sentiment with trading activity
Feature Engineering
Created key metrics such as:

Closed PnL (profit/loss per trade)
Win rate (profitable trades / total trades)
Trade size (Size USD)
Leverage usage
Long/Short positions
Trade frequency per sentiment
Analysis Performed
Compared trader performance during Fear vs Greed days
Analyzed changes in trading behavior based on sentiment
Studied leverage usage patterns across different market conditions
Evaluated long vs short bias in different sentiments
Segmented traders into groups (high leverage, frequent traders, consistent winners)
Key Insights
Trader profitability varies significantly with market sentiment
Greed periods often lead to higher risk-taking and leverage usage
Fear periods show more cautious trading behavior
Long positions perform better during Greed phases
Short positions perform relatively better during Fear phases
Market sentiment strongly influences trading decisions and risk exposure
Strategy Recommendations
Reduce leverage exposure during Greed phases to avoid overtrading risk
Encourage selective trading during Fear phases for better risk management
Focus on long-biased strategies during Greed conditions
Monitor high-frequency traders separately as they react differently to sentiment
Conclusion
Market sentiment is a strong behavioral driver in crypto trading. Understanding Fear and Greed cycles can help improve trading strategies, risk management, and profitability. This analysis provides actionable insights for smarter trading decisions.
