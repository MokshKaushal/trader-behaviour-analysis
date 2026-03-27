# Trader Performance vs Market Sentiment Analysis

## 📌 Objective
Analyze how market sentiment (Fear/Greed) affects trader behavior and performance.

---

## ⚙️ Methodology

1. Data Loading & Cleaning  
   - Loaded sentiment and trader datasets  
   - Handled missing values and checked duplicates  

2. Data Alignment  
   - Converted timestamps to date format  
   - Merged datasets at daily level  

3. Feature Engineering  
   - Daily PnL per trader  
   - Win rate  
   - Average trade size  
   - Trade frequency  
   - Long/Short ratio  
   - Leverage segmentation  

4. Analysis  
   - Compared performance across Fear vs Greed  
   - Studied behavior changes (leverage, frequency, bias)  
   - Created trader segments  

---

## 📊 Key Insights

- Traders show higher PnL during Greed periods but with increased volatility  
- Trading activity and risk-taking behavior increase in Greed phases  
- Fear periods lead to reduced trading and more cautious positioning  
- Frequent traders exhibit higher variability in performance  

---

## 🎯 Strategy Recommendations

- Reduce leverage and trading frequency during Fear markets  
- Use controlled leverage with strict risk management during Greed  
- Adjust trading intensity based on market sentiment  

---

## ▶️ How to Run

1. Clone the repository  
2. Place datasets:
   - fear_greed.csv  
   - trader_data.csv  

3. Install dependencies:

 pip install pandas matplotlib seaborn scikit-learn


4. Run:

trader_analysis.ipynb


---

## ⚠️ Limitations

- Sentiment is daily (no intraday granularity)  
- External market factors not included  
- Historical patterns may not always generalize
