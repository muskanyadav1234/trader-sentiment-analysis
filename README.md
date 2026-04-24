# 📊 Trader Performance vs Market Sentiment Analysis

## 🧠 Project Overview
This project analyzes the relationship between Bitcoin market sentiment (Fear & Greed Index) and trader performance using Hyperliquid trading data. The objective is to identify patterns in profitability, risk behavior, and trading strategies based on market sentiment.

---

## 🎯 Objective
To understand how market sentiment influences:
- Trader profitability
- Risk-taking behavior
- Trading frequency and strategy choices

---

## 📂 Datasets Used

### 1. Bitcoin Market Sentiment Dataset
- Columns: Date, Classification (Fear / Greed)
- Represents market psychology on a daily basis

### 2. Historical Trader Dataset (Hyperliquid)
- Columns include:
  - account
  - symbol
  - execution price
  - size
  - side (LONG/SHORT)
  - timestamp
  - closedPnL
  - leverage

---

## ⚙️ Data Preparation
- Loaded datasets using pandas
- Cleaned column names and handled missing values
- Converted timestamps into date format
- Merged both datasets on date level to align sentiment with trading activity

---

## 🧪 Feature Engineering
Created key trading metrics:
- Closed PnL (Profit/Loss per trade)
- Win rate (profitable trades ratio)
- Trade size (Size USD)
- Leverage usage
- Long/Short positions
- Trade frequency based on sentiment

---

## 📊 Analysis Performed
- Compared trader performance during Fear vs Greed days
- Analyzed behavioral changes based on sentiment
- Studied leverage usage patterns across market conditions
- Evaluated long vs short bias in different sentiments
- Segmented traders into behavioral groups:
  - High leverage traders
  - Frequent traders
  - Consistent winners

---

## 🔍 Key Insights
- Trader profitability significantly varies with market sentiment
- Greed phases lead to higher risk-taking and increased leverage usage
- Fear phases result in more cautious and stable trading behavior
- Long positions perform better during Greed periods
- Short positions perform relatively better during Fear periods
- Market sentiment strongly influences trading decisions and risk exposure

---

## 💡 Strategy Recommendations
- Reduce leverage exposure during Greed phases to avoid overtrading risk
- Encourage selective and cautious trading during Fear phases
- Focus on long-biased strategies during Greed conditions
- Monitor high-frequency traders separately due to behavioral differences

---

## 📌 Conclusion
Market sentiment is a strong behavioral driver in crypto trading. Understanding Fear and Greed cycles can significantly improve trading strategies, risk management, and profitability. This analysis provides actionable insights for smarter trading decisions in financial markets.

---

## 🛠️ Tools Used
- Python
- Pandas
- NumPy
- Matplotlib

---

## 🚀 Author
Muskan Yadav  
B.Tech CSE (AIML)
