# 📉 Bitcoin Trading Sentiment Analysis

This project explores the relationship between Bitcoin market sentiment and trader performance using two datasets: a **Fear & Greed index** and **historical trading data** from Hyperliquid. The analysis demonstrates how sentiment impacts **closed PnL** and trading outcomes.

---

## 📁 Datasets Used

1. **fear_greed.csv**  
   Contains daily Bitcoin sentiment values — either `"Fear"` or `"Greed"` — based on the Fear & Greed Index.

2. **historical_data.csv**  
   Contains real trading data from Hyperliquid, including account activity, closed PnL, time, and trading side.

---

## 🧪 What This Project Does

- Loads and cleans both datasets using `pandas`
- Merges sentiment data with trader performance by date
- Calculates **average closed PnL** by sentiment classification
- Visualizes insights using a **bar chart**
- Helps understand whether trading during fear or greed is more profitable

---

## 🧰 Tools & Technologies

- Google Colab  
- Python  
  - pandas  
  - matplotlib  
- GitHub

---

## ▶️ Open Notebook in Google Colab

Click below to open and run the notebook directly in Google Colab:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/shku23ainds-hash/Bitcoin-Trading-Sentiment-Analysis/blob/main/Trader_Sentiment_Analysis.ipynb)

---

## 📂 Files in This Repo

| File | Description |
|------|-------------|
| `Trader_Sentiment_Analysis.ipynb` | Main analysis notebook |
| `fear_greed.csv` | Sentiment classification data |
| `historical_data.csv` | Trader activity and PnL data |

---

## ✅ How to Use

1. Click the **Open in Colab** badge above.
2. Upload both datasets (`fear_greed.csv`, `historical_data.csv`) in the notebook environment if not already present.
3. Run all cells to view the sentiment-wise PnL analysis.

---

## 📌 Result Summary

📊 The final output graph shows:
- Average PnL for traders on **Fear** days
- Average PnL for **Greed** days
- Helpful insights into sentiment-based trading strategies

---

## 💡 Future Improvements

- Add more sentiment classes (Extreme Fear, Extreme Greed)
- Include volume and leverage-based filtering
- Automate data updates via API

---

## ©️ License

This project is intended for educational and research purposes.

