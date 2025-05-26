# 📊 Crypto Trading Account Performance Analysis

Unlock insights into trader behavior and strategy effectiveness under different market sentiments using real trading data and quantitative metrics.


## 🚀 Project Overview

This project analyzes **32 crypto trading accounts** using a comprehensive set of **risk-adjusted performance metrics**. By linking trader performance to **market sentiment states**—like Extreme Fear, Greed, or Neutral—we aim to uncover which trader behaviors work best under which conditions.

The ultimate goal: **Build a foundation for sentiment-aware trading models**.


## 📌 Key Objectives

- Evaluate trader performance using metrics like Sharpe Ratio, Max Drawdown, and Win Rate.
- Cluster traders into strategy-based categories (e.g., trend-followers, inconsistent risk-takers).
- Examine how trading outcomes vary with **market sentiment shifts**.
- Identify **top-performing strategies** and flag underperformers.
- Lay the groundwork for future **sentiment-aware trading bots/algorithms**.


## 📈 Performance Metrics Used

We computed 10+ metrics to profile trading behavior:

- **Sharpe Ratio**
- **Sortino Ratio**
- **Maximum Drawdown**
- **Value at Risk (VaR)**
- **Win Rate / Loss Rate**
- **Profit Factor**
- **Average Return**
- **Risk-Reward Ratio**
- **Average Win & Loss Size**



## 🔍 Highlights & Key Findings


### 📊 Sentiment-Wise Consistency
- Certain accounts showed consistent **profitability under Extreme Greed or Fear**.
- Performance clustering revealed:
  - **Elite Quants** – high Sharpe, low drawdown.
  - **Balanced Traders** – steady performance.
  - **Break-Even Players** – volatile, inconsistent results.
  - **Unstable Traders** – poor risk control, negative returns.


## 🧠 Sentiment vs Performance: What We Found

- **Sentiment plays a measurable role** in profitability.
- Top performers often thrive in **Extreme Greed** phases.
- **Very few accounts** show consistent profits during **Extreme Fear** — suggesting avoidance or better risk mitigation is key.
- This opens the door to **sentiment-aligned trading strategy development**.

## Note ⚠️ For a More Detailed insight download the "Trading Account Performance Analysis.docx".

## 🗃️ Data Used

- **Trading Account Data**: PnL, entry/exit times, trade-level granularity.
- **Market Sentiment Data**: Derived from sources like the Crypto Fear & Greed Index, social media, or news-based sentiment scores.


## 📎 Files in This Repo

| File | Description |
|------|-------------|
| `Assignment.ipynb` | Jupyter notebook with full analysis, visualizations, and metric computation |
| `Trading Account Performance Analysis.docx` | High-level summary and key takeaways from findings |
| `README.md` | You’re here. Project overview and documentation |


## 🔮 Future Work

- **Build a sentiment-aware trading recommendation engine**
- **Integrate real-time sentiment APIs**
- Expand dataset with **more trader accounts or cross-exchange performance**
- Experiment with **machine learning models** to predict profitable trader behavior


## 🛠️ Tech Stack

- Python (Pandas, NumPy, Matplotlib, Seaborn, Sci-kit Learn)
- Jupyter Notebooks
- Sentiment Index data


## 📬 Contact / Connect

Have ideas or want to collaborate? Feel free to open an issue or drop a message.
