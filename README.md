📊 Trader Behavior vs Market Sentiment Analysis
A Data Science Project by Pragati Andewadi
🧭 Project Overview

This project investigates how trader behavior (profitability, risk, leverage, volume) correlates with market sentiment (Fear vs. Greed).
Using two datasets — Bitcoin Fear & Greed Index and Hyperliquid Historical Trades —
the analysis identifies patterns, behavioral biases, and insights that can support smarter, data-driven trading strategies.

📂 Project Structure
ds_pragati_andewadi/
│
├── notebook_1.ipynb         # Main analysis notebook (Google Colab)
│
├── csv_files/               # Cleaned + intermediate datasets
│   ├── historical_data_clean.csv
│   ├── fear_greed_index_clean.csv
│   └── trades_with_sentiment_merged.csv
│
├── outputs/                 # All charts, graphs, exported visuals
│   └── *.png / *.jpg
│
├── ds_report.pdf            # Final project report
└── README.md                # Project documentation

🎯 Objective

To analyze how trader performance (profit/loss, leverage usage, risk behavior, volume) changes during different market sentiment regimes
and to identify:

Hidden trading patterns

Behavioral biases

Sentiment-driven risks

Data-backed strategy recommendations

📊 Datasets Used
1️⃣ Bitcoin Market Sentiment Dataset

Columns: Date, Classification (Fear/Greed)

Represents the crypto market’s emotional state on each day.

2️⃣ Hyperliquid Historical Trader Data

Includes:
account, execution_price, size, side, time,
closedPnL, event, symbol, leverage, etc.

Contains trade-level details from multiple traders.

🧹 Data Preprocessing

✔ Converted timestamps to datetime
✔ Cleaned missing and invalid rows
✔ Removed duplicates
✔ Standardized column naming
✔ Engineered features:

Profit/Loss category

Aggression Score (size × leverage)

Leverage bucket

Sentiment mapping by date

✔ Merged both datasets on Date
✔ Exported cleaned files to csv_files/

📈 Key Analyses Performed

Sentiment-wise profit distribution

Leverage behavior in Fear vs. Greed

Volume spikes by sentiment

PnL vs. aggression levels

Risk behavior across market states

Market-regime impact on trader performance

All visuals are saved under outputs/.

🧠 Major Insights
🔹 1. Traders use higher leverage during Greed
🔹 2. Profitability is slightly higher during Fear due to better entry prices
🔹 3. Volume increases significantly during Greed
🔹 4. Highest losses occur during high-leverage Greed trades
🔹 5. Aggression Score peaks in Greed phases
🔹 6. Fear periods show more disciplined, risk-aware trading

These highlight emotional biases that can be corrected using data-driven strategies.

🛠 Technologies & Tools

Python (Google Colab)
Pandas · NumPy · Matplotlib · Seaborn

Power BI (Interactive dashboard)

GitHub for version control

Google Drive for dataset hosting

📘 How to Run

Open notebook_1.ipynb in Google Colab
Google colab link : https://drive.google.com/file/d/1KYZjF5Z5AzZc5Po10PhnzhCCObqsKMAN/view?usp=sharing

Upload datasets from csv_files/

Run all cells to generate updated charts

Visual outputs appear inside outputs/

Refer to ds_report.pdf for full explanation

📄 Project Report

The final detailed report is available as:

👉 ds_report.pdf

It contains:
Abstract · Introduction · Methods · EDA · Visuals · Insights · Recommendations · Conclusion

👩‍💻 Author

Pragati Andewadi
Data Science | Analytics | Machine Learning
