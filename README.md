# Trader Performance vs Market Sentiment Analysis

## 📊 Overview
This project analyzes how market sentiment (Fear vs Greed) affects trader behavior and performance on Hyperliquid.

---

## 📈 Visualization

### PnL Distribution by Sentiment
![PnL Distribution](charts/pnl_distribution.png)

### Trade Direction (Long vs Short)
![Long Short](charts/long_short.png)

---

## 📂 Dataset

### Sentiment Data
- date
- classification
- value

### Trader Data
- Account
- Size USD
- Direction
- Closed PnL
- Fee
- Timestamp IST

---

## ⚙️ Data Preparation
- Cleaned column names  
- Converted timestamps  
- Created merge_date  
- Merged datasets  

---

## 📊 Key Metrics
- Daily PnL  
- Win Rate  
- Trade Size  
- Trade Frequency  
- Long/Short Ratio  

---

## 🔍 Analysis
- Compared Fear vs Greed performance  
- Analyzed behavior changes  
- Segmented traders  

---

## 💡 Insights
- Greed → higher trading activity and risk  
- Fear → cautious trading behavior  
- Profit concentrated among few traders  

---

## 🚀 Strategy Recommendations
- Reduce position size during Fear  
- Avoid overtrading during Greed  
- Monitor fee-to-PnL ratio  

---

## 🛠 Tech Stack
Python, Pandas, NumPy, Matplotlib, Seaborn  

---

## ▶️ How to Run
pip install pandas numpy matplotlib seaborn  
jupyter notebook trader_sentiment_analysis.ipynb  

---

## 📌 Conclusion
Adapting strategies based on market sentiment improves trading performance.
