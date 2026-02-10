# Bitcoin-_Trader_Analysis
Analysis of trader behavior under a  condition like fear and greed sentiment over a crypto trade data.


# Overview
This project analyzes how trader performance and behavior change under different
Bitcoin market sentiment regimes (Fear vs Greed). The analysis combines market
sentiment data with historical trader-level data to uncover actionable insights
and strategy recommendations.


# Data
Bitcoin Fear & Greed Index*
  - Daily market sentiment classified as Fear or Greed
Historical Trader Data (Hyperliquid)*
  - Trade-level data including position size, direction, and realized PnL

# Pipeline 
1. Cleaned and validated both datasets (no missing or duplicate records).
2. Aligned trader activity with market sentiment at a daily level.
3. Computed key metrics such as:
   - Average PnL
   - Trade frequency
4. Compared trader behavior and performance across Fear and Greed periods.
5. Derived sentiment-aware strategy recommendations.

# Key Insights
- Traders achieve higher average PnL during Greed periods compared to Fear periods.
- Trade activity increases significantly during Greed markets.
- High-exposure traders suffer larger losses during Fear periods, while low-exposure
  traders show more stable performance.

# Strategy Recommendations
- Reduce exposure and trade frequency during Fear periods to limit downside risk.
- Allow selective increase in exposure during Greed periods for consistent traders.
- Apply sentiment-aware risk controls based on trader exposure profiles.



# How to Run
1. Open analysis.ipynb in Jupyter Notebook or Google Colab.
2. Ensure required Python libraries are installed (pandas, numpy, matplotlib).
3. Run all cells from top to bottom.



