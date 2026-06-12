# Bitcoin Market Sentiment vs Trader Performance Analysis

## Overview

This project investigates the relationship between Bitcoin market sentiment and trader performance on the Hyperliquid decentralized exchange.

Using the Bitcoin Fear & Greed Index and Hyperliquid historical trading data, the analysis explores how different market sentiment regimes influence:

- Trader profitability
- Win rates
- Risk-adjusted returns
- Trading behavior
- Position direction
- Trader segmentation

The goal is to identify actionable insights that can support more informed trading and risk-management decisions.

---

## Objective

To analyze whether market sentiment (Fear, Greed, Extreme Fear, Extreme Greed) has a measurable impact on trader performance and uncover patterns that can help improve trading strategies.

---

## Datasets

### 1. Bitcoin Fear & Greed Index

Contains daily market sentiment information.

**Columns include:**
- Date
- Fear & Greed Score
- Classification

Sentiment Categories:
- Extreme Fear
- Fear
- Neutral
- Greed
- Extreme Greed

### 2. Hyperliquid Historical Trader Data

Contains historical trading activity from Hyperliquid.

**Columns include:**
- Account
- Symbol
- Side
- Size
- Execution Price
- Closed PnL
- Fee
- Trade Direction
- Timestamp
- Leverage

---

## Project Workflow

### Data Preparation

- Data cleaning
- Missing value handling
- Timestamp conversion
- Dataset merging
- Feature engineering

### Exploratory Data Analysis

- Sentiment distribution
- Trade volume analysis
- PnL distribution
- Daily profitability trends
- Coin-level analysis

### Statistical Analysis

- Mann-Whitney U Test
- Correlation analysis
- Risk-adjusted return analysis

### Trader Analysis

- Top trader performance
- Profitable vs losing traders
- Trade direction analysis
- Buy vs Sell comparison

### Machine Learning

- K-Means clustering
- Trader segmentation

---

## Key Findings

- Extreme Greed produced the highest average profitability.
- Extreme Fear showed the highest volatility and lowest risk-adjusted returns.
- Buy trades generally outperformed Sell trades during the analysis period.
- Trader performance differed significantly across sentiment regimes.
- High-frequency traders generated the largest overall profits.
- Sentiment can be a useful contextual signal when evaluating trading conditions.

---

## Visualizations Included

The project contains visualizations for:

- Sentiment Distribution
- PnL Distribution
- Win Rate Analysis
- Buy vs Sell Analysis
- Trade Direction Analysis
- Daily Profitability
- Correlation Heatmap
- Risk-Adjusted Returns
- Trader Segmentation
- Coin-Level Performance
- Top Trader Analysis
- Profitable vs Losing Traders

---

## Project Structure

```text
.
├── analysis.ipynb
├── Report.pdf
├── executive_summary.csv
├── sentiment_trading_insights.csv
├── trader_performance.csv
├── fear_greed_index.csv
├── historical_data.csv
│
├── visualizations
│   ├── buy_vs_sell.png
│   ├── coin_sentiment.png
│   ├── daily_pnl.png
│   ├── direction_analysis.png
│   ├── heatmap.png
│   ├── pnl_distribution.png
│   ├── profitable_vs_losing.png
│   ├── risk_adjusted.png
│   ├── sentiment_distribution.png
│   ├── top_traders.png
│   ├── trader_clusters.png
│   └── winrate.png
```

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- SciPy
- Scikit-Learn
- Jupyter Notebook

---

## Deliverables

- Analysis Notebook
- PDF Report
- Processed Insight Files
- Visualizations
- Statistical Findings
- Trader Segmentation Results

---

## Author

**Shubham Sinha**

Data Science & Machine Learning Enthusiast

---

## Disclaimer

This analysis is based solely on the provided datasets and is intended for educational and research purposes. The findings should not be interpreted as financial advice or guarantees of future trading performance.