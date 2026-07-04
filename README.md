# Trader Performance vs Market Sentiment Analysis

## Project Overview

This project analyzes the relationship between Bitcoin market sentiment (Fear & Greed Index) and trader behavior using historical trading data.

### Objectives

- Analyze trader profitability across market sentiment
- Compare win rates during Fear and Greed
- Study drawdown proxy
- Analyze trading frequency
- Analyze position size
- Study long/short bias
- Build a predictive model
- Cluster traders based on behavior

---

## Dataset

- Historical Trader Data
- Bitcoin Fear & Greed Index

---

## Methodology

1. Data Cleaning
2. Data Preparation
3. Feature Engineering
4. Merge datasets
5. Exploratory Data Analysis
6. Behavioral Analysis
7. Predictive Modeling
8. Trader Clustering

---

## Key Insights

- Extreme Greed achieved the highest win rate.
- Fear periods had the highest trading activity.
- Position sizes increased during Fear and Extreme Greed.
- SELL trades slightly exceeded BUY trades.
- Fear periods experienced the largest drawdowns.

---

## Strategy Recommendations

- Reduce position size during Fear periods to manage risk.
- Increase trading activity during Extreme Greed only with trend confirmation.

---

## Machine Learning

A Random Forest classifier was trained to predict trader profitability using sentiment and behavioral features.

**Accuracy:** 63.69%

---

## Libraries

- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

---

## Setup

### Prerequisites

- Python 3.10+
- Jupyter Notebook

### Install Required Libraries

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

## How to Run

1. Clone the repository

```bash
git clone https://github.com/rishavkumar3333/Trader-Performance-vs-Market-Sentiment.git
```

2. Open the project folder.

3. Launch Jupyter Notebook.

```bash
jupyter notebook
```

4. Open

```
Trader_Performance_vs_Market_Sentiment.ipynb
```

5. Run all cells from top to bottom.
