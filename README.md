# Bitcoin Trading Sentiment Analysis

This project analyzes the impact of market sentiment on trader performance using real trading data and sentiment classifications. By combining the **Bitcoin Fear & Greed Index** with **trading activity from Hyperliquid**, we explore whether traders perform better during periods of fear or greed.

---

## Objective

To determine how market sentiment influences trader profitability by:

- Merging sentiment and trading datasets
- Calculating average closed PnL per sentiment category
- Visualizing patterns and extracting insights for strategic trading

---

##  Datasets

1. **fear_greed.csv**  
   - Columns: `date`, `classification`  
   - Source: Bitcoin Fear & Greed Index  
   - Purpose: Sentiment classification (`Fear`, `Greed`, `Extreme Fear`, `Neutral`, etc.)

2. **historical_data.csv**  
   - Columns: `account`, `symbol`, `execution_price`, `size`, `side`, `time`, `start_position`, `event`, `closedPnL`, `leverage`, etc.  
   - Source: Hyperliquid (mock or anonymized real trader data)  
   - Purpose: Analyze trader profitability by date

---

## Analysis Overview

- Preprocessed and cleaned both datasets using `pandas`
- Aligned trades with daily sentiment based on timestamps
- Calculated **average closedPnL** by sentiment type
- Created bar plots to visualize sentiment vs performance

---

## Key Insights

- Traders tend to show **higher average PnL during Greed and Extreme Greed** phases
- **Fear and Extreme Fear** days show more volatility and inconsistent outcomes
- These trends can help design **sentiment-aware trading strategies**

---

## Tech Stack

- **Python**
  - pandas
  - matplotlib
- **Google Colab** (for cloud-based analysis)
- **GitHub** (for version control and sharing)

---

##  Run the Notebook

You can open and run the analysis directly in Google Colab using the badge below:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/shku23ainds-hash/Bitcoin-Trading-Sentiment-Analysis/blob/main/Trader_Sentiment_Analysis.ipynb)

---

## Project Structure

| File                            | Description                                     |
|---------------------------------|-------------------------------------------------|
| `Trader_Sentiment_Analysis.ipynb` | Main analysis notebook                         |
| `fear_greed.csv`               | Bitcoin sentiment classification data          |
| `historical_data.csv`          | Historical trader performance data             |

---

## How to Use

1. Click on the **Open in Colab** badge above.
2. Upload both `.csv` files when prompted or ensure they are in the same directory.
3. Run all cells to view sentiment-wise PnL trends and plots.

---

## Future Enhancements

- Integrate live sentiment API (e.g., Alternative.me)
- Extend to other crypto assets (ETH, SOL, etc.)
- Analyze behavior by trader segments or leverage levels
- Add moving averages or rolling sentiment windows

---

## License

This project is open for educational, research, and demonstration purposes only.

---

##  Author

Shilpi Kumari. | Data Science Enthusiast  
GitHub: [@shku23ainds-hash](https://github.com/shku23ainds-hash)
