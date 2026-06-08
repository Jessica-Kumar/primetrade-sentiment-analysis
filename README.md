Here is a clean, professional, and GitHub-ready format for your project documentation. You can copy and paste this directly into your `README.md` file or Colab notebook.

---

# 📊 Trader Performance vs. Bitcoin Market Sentiment Analysis

> **Data Science Assignment** — Primetrade.ai Internship Application
> **Analyst:** Jessica Kumar | **Date:** June 2026

---

## 🎯 Objective

Explore the relationship between the **Bitcoin Fear & Greed Index** and trader performance on Hyperliquid. Uncover hidden behavioral patterns and deliver actionable insights for smarter trading strategies.

---

## 📁 Dataset

Datasets are loaded directly from Google Drive — no manual download is needed to run the analysis.

| Dataset | Source | Size |
| --- | --- | --- |
| **Bitcoin Fear & Greed Index** | Alternative.me | 2,644 days (2018–2025) |
| **Historical Trader Data** | Hyperliquid | 211,224 trades |

---

## 🔍 Analysis Covered

* **Sentiment Distribution:** Across Fear, Greed, and Neutral regimes.
* **Performance Metrics:** Average PnL, win rate, and total returns grouped by sentiment.
* **Directional Edge:** Long vs. Short performance across sentiment bands.
* **Trader Tiers:** Top 20 vs. Bottom 20 trader behavior comparison.
* **Volume & Sizing:** Trade volume and position sizing relative to market sentiment.
* **Correlation:** Pearson correlation between the Fear & Greed value and daily PnL.
* **Asset Heatmap:** Coin × Sentiment analysis for the top 10 traded assets.

---

## 💡 Key Findings

* **Extreme Fear = Highest Edge:** Represents the highest average PnL, signaling a classic contrarian opportunity.
* **Extreme Greed = Lowest Edge:** Generates the most volume but the lowest returns, driven by overconfidence.
* **Divergent Sizing Behavior:** Top traders size up during Fear, whereas bottom-tier traders do the exact opposite.
* **Directional Bias:** Longs historically outperform in Fear regimes; Shorts outperform during Greed regimes.
* **Volume vs. Returns:** High trade volume does not correlate with high returns.

---

## 🎯 Strategy Recommendations

1. **Entry Triggers:** Use F&G < 25 as a strong long entry signal.
2. **Exit/Short Triggers:** Use F&G > 75 to take profits or build short positions.
3. **Dynamic Sizing:** Scale position sizes inversely with the F&G index.
4. **Asset Selection:** Focus on coins demonstrating historically consistent positive PnL in Fear regimes.
5. **Capital Preservation:** Reduce trading frequency within the Neutral band (F&G 40–60).

---

## 🚀 Run the Notebook

No local environment setup is required. All dependencies and datasets load automatically in the cloud.

[](https://www.google.com/search?q=YOUR_COLAB_LINK_HERE) *(Replace YOUR_COLAB_LINK_HERE with your actual URL)*

---

## 🛠️ Tech Stack

**Language:** Python

**Libraries:** Pandas, NumPy, Matplotlib, Seaborn, SciPy

**Environment:** Jupyter Notebook / Google Colab

---

## 👩‍💻 Author

**Jessica Kumar**

B.Tech CSE (AI/ML) — KIET Group of Institutions, Ghaziabad

🔗 [LinkedIn](https://www.google.com/search?q=https%3A%2F%2Flinkedin.com%2Fin%2FJessica-Kumar22) | 🐙 [GitHub](https://www.google.com/search?q=https%3A%2F%2Fgithub.com%2FJessica-Kumar)
