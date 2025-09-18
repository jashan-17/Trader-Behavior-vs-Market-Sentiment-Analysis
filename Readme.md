# 📊 Trader Behavior vs Market Sentiment Analysis  
*Internship Assignment – Web3 Trading Team*  

## 👤 Candidate  
**Name:** Jashanpreet Singh  

---

## 📌 Project Overview  
This project analyzes the relationship between **trader behavior** (profitability, trading volume, leverage, and positioning) and **Bitcoin market sentiment** (Fear & Greed Index).  

The objective is to uncover hidden trends or signals that could influence smarter trading strategies and risk management.  

---

## 📂 Folder Structure  

ds_jashanpreet_singh/
│
├── notebook_1.ipynb # Main analysis notebook (Google Colab)
│
├── csv_files/
│ ├── fear_greed_index.csv # Raw sentiment dataset
│ ├── historical_data.csv # Raw trader dataset
│ ├── processed_trader_sentiment.csv # Final cleaned dataset
│
├── outputs/
│ ├── pnl_vs_sentiment.png
│ ├── volume_vs_sentiment.png
│ ├── bullish_ratio_vs_sentiment.png
│ ├── correlation_heatmap.png
│ └── ... (other charts/EDA results)
│
├── ds_report.pdf 
│
└── README.md



---

## ⚙️ Setup & Usage  

1. Open the analysis notebook in **Google Colab**:  
   👉 [Notebook Link](https://colab.research.google.com/drive/1ZefZIQatzzv5Vjh2cWP3s181xy-52FHt?usp=sharing)

2. Place the raw datasets into the `csv_files/` folder.  
   - `fear_greed_index.csv`  
   - `historical_data.csv`  

3. Run all cells to reproduce data cleaning, feature engineering, and exploratory analysis.  

4. Generated figures will be saved in the `outputs/` folder, and the cleaned dataset will be saved in `csv_files/processed_trader_sentiment.csv`.  

---

## 📊 Datasets  

1. **Fear & Greed Index**  
   - Columns: `date`, `value`, `classification`  
   - Source: [Google Drive link provided in assignment]  

2. **Historical Trader Data (Hyperliquid)**  
   - Columns include: `account`, `symbol`, `execution price`, `size`, `side`, `closedPnL`, `leverage`, etc.  
   - Source: [Google Drive link provided in assignment]  

---

## 🔑 Key Insights  

- **Trading volume spikes during Fear/Extreme Fear**, suggesting panic-driven or forced trades.  
- **PnL distributions are more volatile in Fear**, while Greed periods show steadier returns.  
- **Bullish Ratio increases in Greed**, meaning traders lean long when sentiment is optimistic.  
- **Fees strongly correlate with volume**, confirming that aggressive activity drives higher costs.  

---

## 📄 Report  
The full analysis and visual insights are summarized in **`ds_report.pdf`**.  

---

## 🔗 Links  
- 💻 [GitHub Repository](https://github.com/jashan-17/ds_jashanpreet_singh)  

---