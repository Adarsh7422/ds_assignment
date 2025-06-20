 Trader Performance & Bitcoin Market Sentiment Analysis
 

This project explores the relationship between **trader performance** and the **Bitcoin Fear & Greed Index**, using historical trader data from Hyperliquid and market sentiment data.

---

  Datasets Used

1. Fear & Greed Index Dataset**  
   - Columns: `date`, `classification` (e.g., Fear, Greed), `value`

2. Hyperliquid Historical Trader Data**  
   - Columns: `account`, `symbol`, `execution price`, `size`, `side`, `time`, `start position`, `event`, `closedPnL`, `leverage`, etc.

---

# Project Goals

-  Merge market sentiment data with trader activity by date
- Analyze how **market emotions (Fear/Greed)** impact **profitability and trading behavior**
-  Visualize key metrics like:
- Average PnL by sentiment
- Trading volume and number of trades by sentiment
-  Derive actionable insights to inform better trading strategies



# Key Insights

- **Highest Avg Profit** occurred during `Extreme Greed` (₹67.89 per trade)
-  **Most Trades & Volume** occurred during `Fear` (61,837 trades, ₹483M volume)
-  **Neutral sentiment** led to the **lowest average PnL**
-  Execution prices were highest in `Fear` & `Greed` — likely due to market volatility



# Conclusion

  Market sentiment strongly influences trader behavior. 
 Fearful markets trigger high volume and trade count.  
 Neutral markets result in lower performance.

These insights can help traders and platforms build smarter, sentiment-aware strategies.



# Tools Used

- Python (Pandas, NumPy)
- Seaborn & Matplotlib
- Jupyter Notebook
- CSV data sources
