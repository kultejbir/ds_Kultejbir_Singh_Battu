# Trader Behavior vs Market Sentiment Analysis

## Objective
This project analyzes how market sentiment influences trader behavior and performance.
The analysis combines the Bitcoin Fear & Greed Index with historical trader data from Hyperliquid
to understand how emotions such as fear and greed affect trading activity, profitability, and risk.

---

# Setup Instructions and Notes

## Setup Instructions
1. This project was developed and executed using Google Colab.
2. All required Python libraries (pandas, matplotlib, seaborn) are pre-installed in Google Colab.
3. Upload the provided CSV files (`fear_greed_index.csv` and `historical_data.csv`) to the Colab environment before running the notebook.

   NOTE : The `historical_data.csv` exceeds GitHub’s file size limit and is provided via a Google Drive link.
5. Run all cells in `notebook_1.ipynb` sequentially to reproduce the analysis and visualizations.

## Notes
- The Fear & Greed Index data is available at a daily level, while trader data is event-level.
- Trade data was aggregated at a trader-day level for analysis.
- The provided dataset does not contain an explicit leverage column; therefore, leverage-specific analysis was not performed.
- Risk was evaluated using PnL volatility instead.

---

## Author
Kultejbir Singh Battu
