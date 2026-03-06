
📊 Trader Performance vs Market Sentiment Analysis

🚀 Project Overview

This project explores the relationship between cryptocurrency market sentiment and trader behavior using historical trading data from Hyperliquid and the Bitcoin Fear & Greed Index.

Market sentiment often drives trading decisions. When markets are driven by Fear, traders behave differently compared to periods of Greed. This project investigates those behavioral changes and analyzes how trader performance varies under different sentiment conditions.

The goal is to extract insights that can help design smarter trading strategies based on market sentiment signals.

🎯 Project Objectives

Analyze how trader performance changes under different market sentiment conditions.

Understand behavioral patterns during Fear vs Greed periods.

Study trading metrics such as:

Profit and Loss (PnL)

Trade frequency

Trade size

Win rate

Generate actionable insights that can inform trading strategies.

📂 Datasets Used
1️⃣ Bitcoin Fear & Greed Index

This dataset represents market sentiment derived from various market indicators such as volatility, trading momentum, social media activity, and market trends.

Key Fields

Date

Sentiment Classification

Fear

Extreme Fear

Greed

Extreme Greed

2️⃣ Hyperliquid Historical Trader Data

This dataset contains real trading activity from traders on the Hyperliquid platform.

Key Fields

Account

Coin
Execution Price
Trade Size (USD)
Direction (Long / Short)
Timestamp
Closed PnL
Trading Fee

⚙️ Methodology
The project follows a structured data analysis workflow.

1️⃣ Data Collection

Both datasets were imported into a Python analysis environment.

2️⃣ Data Cleaning

Checked for missing values

Removed duplicate records

Standardized timestamps

3️⃣ Data Integration

The datasets were merged using a date-based join to align trader activity with daily market sentiment.

4️⃣ Feature Engineering

Additional features were created including:

Trade profitability indicator

Trader volume segments

Daily aggregated metrics

5️⃣ Exploratory Data Analysis

Key metrics analyzed:

Daily Profit and Loss

Trade frequency

Average trade size

Win rate under different sentiment conditions

6️⃣ Data Visualization

Visualizations were created to reveal behavioral patterns in trader activity.

📈 Key Insights
📌 Insight 1 — Risk Appetite Increases During Greed

Traders tend to execute larger trade sizes during Greed periods, indicating increased risk-taking behavior.

📌 Insight 2 — Higher Volatility During Fear

Profit and loss distributions become more volatile during Fear and Extreme Fear periods, suggesting unstable market conditions.

📌 Insight 3 — High-Volume Traders Face Higher Risk

Traders executing large trade sizes generate higher profits but also larger losses, reflecting greater exposure to market fluctuations.

💡 Strategy Recommendations
🛡 Strategy 1 — Risk Control During Fear

During Fear or Extreme Fear market conditions, traders should reduce position size and leverage to limit downside risk.

⚡ Strategy 2 — Opportunistic Trading During Greed

During Greed periods, traders may increase trading frequency while maintaining disciplined risk management.

📊 Tools & Technologies
Tool	Purpose
Python	Data analysis
Pandas	Data manipulation
NumPy	Numerical computations
Matplotlib	Visualization
Seaborn	Statistical charts
Google Colab / Jupyter	Analysis environment
📁 Project Structure
Trader-Sentiment-Analysis
│
├── Trader_Sentiment_Analysis.ipynb
├── README.md
└── datasets
🧠 Conclusion

This project demonstrates how combining market sentiment indicators with trader behavior data can provide valuable insights into trading patterns.

Understanding sentiment-driven behavior allows traders and analysts to design more adaptive and risk-aware trading strategies in volatile markets.

👤 Author

Ankit Yadav
Email-Ankityyadaav@gmail.com
