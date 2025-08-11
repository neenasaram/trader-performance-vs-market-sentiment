# trader-performance-vs-market-sentiment
# Bitcoin Sentiment Trading Analysis

## 📌 Project Overview
This project explores the relationship between **Bitcoin market sentiment** and **trader performance** using data from the **Bitcoin Market Sentiment Dataset** and **Hyperliquid trade history**.  
The goal is to uncover hidden patterns and deliver insights that can drive **smarter trading strategies**.

## 📂 Datasets
### 1. **Bitcoin Market Sentiment Dataset**
- **Columns:** `Date`, `Classification` (Fear / Greed)

### 2. **Hyperliquid Historical Trader Data**
- **Columns:**  
  `account`, `symbol`, `execution_price`, `size`, `side`, `time`,  
  `start_position`, `event`, `closedPnL`, `leverage`, etc.

## 🎯 Objectives
- Investigate how **market sentiment** impacts trading decisions and outcomes.
- Identify **patterns in trader performance** based on Fear/Greed sentiment.
- Provide actionable insights for **improving trading strategies**.

## 🛠️ Steps Performed
1. **Data Loading & Cleaning**
   - Imported both datasets.
   - Handled missing values and standardized column formats.
   - Converted timestamps to a common timezone.

2. **Feature Engineering**
   - Classified trades by market sentiment (Fear/Greed).
   - Calculated key metrics like average PnL, trade frequency, and position sizes.

3. **Exploratory Data Analysis (EDA)**
   - Distribution of sentiment over time.
   - Performance metrics comparison across sentiment categories.
   - Correlation analysis between leverage, PnL, and sentiment.

4. **Insights & Visualization**
   - Plotted sentiment vs trader profitability.
   - Identified conditions where traders perform better/worse.
   - Created aggregated performance statistics by sentiment.

## 📊 Key Insights
- Certain traders consistently outperform during **Greed** phases.
- High leverage trades tend to be riskier during **Fear** sentiment.
- The sentiment shift patterns can serve as **early warning signals**.

## 📦 Tech Stack
- **Python** (Pandas, NumPy, Matplotlib, Seaborn)
- **Jupyter Notebook**
- **Data Visualization** libraries for insights
- **Git/GitHub** for version control
