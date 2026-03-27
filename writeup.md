# Trader Behavior vs Market Sentiment — Analysis Summary

## Objective
The goal of this analysis is to understand how market sentiment (Fear vs Greed) impacts trader behavior and performance using Hyperliquid trading data.

---

## Methodology
The analysis began with data cleaning and preprocessing, including handling missing values and converting timestamps into a daily format. The sentiment dataset was then merged with trading data at a daily level.

Key features were engineered, including:
- Daily PnL per trader  
- Win rate  
- Trade frequency  
- Average trade size  
- Leverage usage  
- Long/Short ratio  

Traders were further segmented into groups such as high vs low leverage and frequent vs infrequent traders.

---

## Key Insights

1. Traders tend to achieve higher PnL during Greed periods, but with increased variability, indicating higher risk.

2. Trading activity and leverage increase during Greed phases, suggesting more aggressive strategies. Fear periods show reduced activity and more cautious behavior.

3. Traders show stronger long-position bias during Greed, while Fear periods reflect more defensive positioning.

4. Frequent traders exhibit higher performance variability, indicating higher risk exposure.

---

## Strategy Recommendations

1. Reduce leverage and trading frequency during Fear markets to avoid losses.

2. Use controlled leverage with proper risk management during Greed periods.

3. Adjust trading strategies dynamically based on market sentiment.

---

## Conclusion

Market sentiment significantly influences trader behavior and performance. Incorporating sentiment-aware strategies can improve trading outcomes and risk management.
