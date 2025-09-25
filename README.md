# PrimeTradeAssignment

This repository contains my submission for the **Junior Data Scientist – Trader Behavior Insights** assignment at **PrimeTrade**.  

The assignment focuses on exploring the relationship between **trader performance** and **Bitcoin market sentiment**, uncovering patterns, and providing insights that can guide smarter trading strategies.

---

## 📂 Datasets

1. **Bitcoin Market Sentiment Dataset**  
   - Columns: `Date`, `Classification` (Fear / Greed)  
   - Source: [Fear/Greed Index](https://drive.google.com/file/d/1PgQC0tO8XN-wqkNyghWc_-mnrYv_nhSf/view?usp=sharing)

2. **Historical Trader Data from Hyperliquid**  
   - Columns include: `account`, `symbol`, `execution price`, `size`, `side`, `time`, `start position`, `event`, `closedPnL`, `leverage`, etc.  
   - Source: [Historical Data](https://drive.google.com/file/d/1IAfLZwu6rJzyWKgBToqwSmmVYU6VbjVs/view?usp=sharing)

> **Note:** Datasets are not included in this repository due to size; please download them from the links above.

---

## 🛠 Assignment Objective

- Analyze the impact of market sentiment on trader performance.  
- Explore hidden patterns in trading behavior.  
- Deliver insights to support smarter trading strategies.  
- Evaluate relationships between Fear/Greed periods, PnL, leverage, and account activity.

---

## ⚡ Features / Analyses Included

- **PnL Analysis**: Total PnL and segmented PnL during Fear/Greed periods.  
- **Trader Performance Insights**: Distribution of profitable and losing trades.  
- **Leverage Analysis**: Examine the effect of leverage on trading outcomes.  
- **Visualization**: Graphs and plots highlighting trends and patterns.  
- **Statistical Testing**: Assess significance of relationships between sentiment and trader performance.

---

## 💻 How to Run

1. **Clone the repository**
```bash
git clone https://github.com/k-shushh/PrimeTradeAssignment.git
cd PrimeTradeAssignment
```

2. **Create and activate a virtual environment**
```bash
# Using venv
python -m venv env

# Windows
.\env\Scripts\activate

# macOS/Linux
source env/bin/activate
```

3. **Install Dependencies**
```bash
pip install -r requirements.txt
```

4. **Run the main script**
```bash
python main.py
```
