# Raise The Stakes 🎯📈

## Team Members
- **Chinmay Agarwal** - 23BCE0715  
- **Veeksha Anne** - 24BCE0628  
- **Mahalakshmi Manikandan** - 24BEE0093  

---

## 🚨 Problem Statement
Investing in the stock market is risky due to its unpredictable nature. Our project leverages Machine Learning to assist users in making better stock decisions by analyzing the last 10 minutes of market data.

---

## 🎯 Goal
Help investors and stock market enthusiasts make **smarter, more informed trading decisions** using real-time ML predictions.

---

## 🛠️ How It Works

### 1. **Data Collection**
- Collects data from the **National Stock Exchange (NSE) and other historical data extraction sites** at second-level intervals.
- Extracts financial indicators such as:
  - Momentum
  - LFV (Liquidity, Flow, Volume)
  - Volatility Index (VIX)
  - Market Sentiment

### 2. **Dual Path Model**
- Combines **LSTM** for short-term trend analysis and **Transformer** for long-term predictions.
- Final prediction is a fusion of both outputs.

### 3. **Volatility Adaptation**
- Model adapts to market instability using results from both LSTM and Transformer paths.

### 4. **Reinforcement Learning**
- Model acts as an agent that:
  - **-1** = Short (predicts price fall)
  - **0** = Hold
  - **1** = Long (predicts price rise)
- Agent receives rewards based on prediction accuracy.

### 5. **Loss Function**
- Minimizes a combined loss:
  - Price prediction loss
  - Volatility loss
  - Reinforcement policy loss

### 6. **Training Strategy**
- Trained using historical stock data.
- Learns and adapts in real time via **reinforcement learning**.

---

## 📊 Target Audience
- Students
- Investors
- Stock market enthusiasts

---

## 🔍 Similar Projects
- [pskrunner14/trading-bot](https://github.com/pskrunner14/trading-bot)
- [krishnaik06/Stock-MArket-Forecasting](https://github.com/krishnaik06/Stock-MArket-Forecasting)

---

## 💡 Model Highlights
- Smart combination of multiple ML models
- Adaptive to real-time market conditions
- Practical implementation of trading principles

---
