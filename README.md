# 📊 Trader Performance vs Market Sentiment Analysis  
**Primetrade.ai – Data Science Intern Round 0 Assignment**

---

## 📌 Objective

To analyze how Bitcoin market sentiment (Fear vs Greed) influences trader behavior and performance on Hyperliquid, and to derive actionable strategy insights.

---

# 📂 Project Structure
```bash
├── notebook.ipynb
├── fear_greed_index.csv
├── historical_data.csv
├── README.md
```

---

# ⚙️ Setup Instructions

## 1️⃣ Clone the repository

```bash
git clone <your-repo-link>
cd <repo-folder>
```


#Install required libraries
```bash
pip install pandas numpy matplotlib seaborn
```

▶️ How to Run

Open notebook.ipynb

Run all cells sequentially

All tables and charts will be generated automatically

# 🔎 Methodology

## 1️⃣ Data Preparation

Converted trader timestamps to daily level

Aligned trader data with daily Fear/Greed sentiment

Filtered overlapping date range

Created daily trader-level metrics

## 2️⃣ Key Metrics Created

Daily PnL per trader

Win rate (profitable day ratio)

Trade frequency per day

Average trade size

Long/Short ratio

PnL volatility (drawdown proxy)

## 3️⃣ Behavioral Segmentation

Traders were segmented into:

High vs Low Frequency

Large vs Small Position

Consistent vs Inconsistent

Performance was analyzed within each segment across sentiment regimes.

# 📈 Key Insights

## 1️⃣ Performance Differences

Average daily PnL is lower during Fear periods.

Win rate declines under Fear sentiment.

PnL volatility increases significantly during Fear.

Interpretation: Negative sentiment environments increase instability and downside risk.

## 2️⃣ Behavioral Changes

Trade frequency increases during Fear days (reactive behavior).

Larger position sizes are observed during Greed periods.

Long bias increases in Greed; short bias increases in Fear.

Interpretation: Traders adapt directionally and risk-wise based on sentiment.

## 3️⃣ Segment-Level Findings

High-frequency traders underperform during Fear regimes.

Large-position traders experience amplified drawdowns in Fear.

Consistent traders demonstrate resilience across sentiment regimes.

# 🚀 Strategy Recommendations

## ✅ Rule 1 — Risk Reduction During Fear

Reduce position sizes for large traders.

Lower trade frequency for high-frequency accounts.

Tighten stop-loss thresholds.

## ✅ Rule 2 — Controlled Exposure During Greed

Moderate increase in exposure.

Favor long bias when supported by sentiment.

Monitor leverage carefully to prevent overextension.

## ✅ Rule 3 — Stability-Based Allocation

Allocate more capital to consistent traders during Fear regimes.

Allow aggressive strategies more flexibility during Greed regimes.

#📌 Conclusion

Market sentiment meaningfully influences both trader performance and behavior.

Incorporating sentiment-aware risk adjustments can improve risk-adjusted returns and reduce drawdown exposure.
