# trader-sentiment-analysis
# Trader Behavior vs Market Sentiment Analysis

##  Overview

This project analyzes how Bitcoin market sentiment (Fear vs Greed) impacts trader behavior and performance using Hyperliquid trading data.

## Objectives

1. Compare trader performance across sentiment regimes
2.Analyze behavioral changes (trade frequency, position size, bias)
3.Identify trader segments
4.Propose actionable trading strategies

## Dataset

Due to file size limitations, datasets are not included in this repository.

## Setup

### 1. Clone the repository

bash
git clone https://github.com/Bhavanasetty/trader-sentiment-analysis.git
cd trader-sentiment-analysis

### 2. Install dependencies

bash
pip install pandas numpy matplotlib seaborn scikit-learn

##  How to Run

1. Open Jupyter Notebook:

bash
jupyter notebook

2. Navigate to:

bash
notebooks/Trader_Sentiment_Analysis.ipynb

3. Run all cells from top to bottom

## Data Preparation

1.Converted timestamps to date format
2.Merged trading data with sentiment data
3.Handled missing values and inconsistencies
4.Created features like:

  1. Daily PnL
  2.Trade frequency
  3. Position size
  4.Buy/Sell ratio

## Key Insights

1. Traders achieve higher profitability during Greed periods, but with increased volatility
2. Trading activity and position sizes increase during Greed
3. Frequent traders underperform during Fear periods due to overtrading

##  Strategy Recommendations

* During Fear periods:

  * Reduce trade frequency and position size
* During Greed periods:

  * Increase exposure cautiously with risk controls
* Built a Random Forest model to predict trader profitability
* Clustered traders into behavioral groups

## Conclusion

Market sentiment significantly influences trader behavior and performance. Incorporating sentiment into trading strategies can improve risk-adjusted returns.
