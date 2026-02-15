# 📊 Retail Sales Analytics Pipeline — P&G Simulation

> **End-to-End Data Science Workflow** | FMCG Sector | Descriptive → Predictive → Strategic Analytics  
> *From raw data to executive dashboards and demand forecasting — a complete analytics pipeline.*

---

## 🎯 Project Overview

This project demonstrates a **full Data Science pipeline** simulating real-world analytics at a company like **Procter & Gamble**. It covers four critical business capabilities:

| # | Capability | Technique | Business Value |
|---|-----------|-----------|----------------|
| 1 | **📋 Descriptive Analytics** | Pandas, Matplotlib, Seaborn | "What happened?" — Clean data, visualize trends |
| 2 | **🔗 Correlation Analysis** | Seaborn Heatmap | "What moves together?" — Cross-selling opportunities |
| 3 | **🔮 Predictive Analytics** | Scikit-Learn Linear Regression | "What will happen next?" — Demand forecasting |
| 4 | **📉 Strategic Analysis (80/20)** | Pareto / Cumulative Distribution | "Where to focus?" — Resource allocation |

---

## 🚀 Key Skills Demonstrated

### 1. Data Manipulation & Engineering 🛠️
- Built structured DataFrames from raw data using **Pandas**
- Feature engineering: growth rates, rolling averages, cumulative metrics
- SQL-like operations: `groupby()`, aggregation, filtering

### 2. Predictive Modeling (Machine Learning) 🤖
- **Supervised Machine Learning** with Scikit-Learn
- Linear Regression model: `model.fit(X, y)` → `model.predict()`
- R² scoring for model evaluation
- Q1 2026 demand forecast with stock order recommendations

### 3. Time Series Analysis ⏳
- **Rolling Window** technique (`df.rolling(window=3).mean()`)
- 3-Month Moving Average for short-term supply chain planning
- Trend detection and seasonality identification

### 4. Interactive Visualization 🖱️
- **Plotly** interactive 4-panel executive dashboard
- Hover tooltips, zoom, legend filtering — ready for live presentations
- Python → JavaScript/HTML conversion for web-based reporting

---

## 📈 Analytics Modules (10 Steps)

| Step | Module | Technique | Business Question |
|------|--------|-----------|-------------------|
| 1–2 | Data Engineering | Pandas, Feature Engineering | Is the data clean? |
| 3–4 | Descriptive Analytics | Line + Bar Charts | What happened in 2025? |
| 5 | Regional Analysis | Pie Chart | Which geography matters? |
| 6 | Statistical Analysis | Correlation Heatmap | Do products move together? |
| 7 | Business Reporting | Executive Summary | So what does this mean? |
| **8** | **Forecasting** | **Moving Avg + Linear Regression** | **What will Q1 2026 look like?** |
| **9** | **Pareto 80/20** | **Cumulative Distribution** | **Where should we focus?** |
| **10** | **Interactive Dashboard** | **Plotly 4-panel Dashboard** | **How do we present to leadership?** |

---

## 💡 Business Insights Generated

```
📊 EXECUTIVE BUSINESS INSIGHTS REPORT — FY 2025

🏷️  Product Performance:  21,150 + 18,300 = 39,450 total units
📅  Best Month: December (4,700 units) — Holiday spike
🗺️  Top Region: Warsaw (49.7% of total volume)
📈  Shampoo Growth: +108.3% (Jan → Dec)
🔗  Correlation: 0.63 — Bundle opportunity confirmed

💼 STRATEGIC RECOMMENDATIONS:
  1. Boost Q4 inventory — holiday spike is predictable
  2. Bundle Shampoo + Detergent — high correlation = cross-sell
  3. Target Feb–Mar with promotions — eliminate seasonal dip
  4. Warsaw is core revenue driver — protect & grow
```

---

## 🔮 Forecasting Results

| Period | Method | Forecast |
|--------|--------|----------|
| Jan 2026 | Moving Average (3M) | ~1,900 units |
| Jan 2026 | Linear Regression | ~2,273 units |
| Feb 2026 | Linear Regression | ~2,351 units |
| Mar 2026 | Linear Regression | ~2,430 units |
| **Q1 2026 Total** | **Regression** | **~7,054 units + 10% buffer** |

---

## 🛠️ Tech Stack

| Tool | Purpose |
|------|---------|
| **Python** | Core programming language |
| **Pandas + NumPy** | Data manipulation & feature engineering |
| **Matplotlib + Seaborn** | Static publication-quality charts |
| **Plotly** | Interactive executive dashboard |
| **Scikit-learn** | Linear Regression forecasting (ML) |
| **Jupyter Notebook** | Reproducible, interactive reporting |

---

## ▶️ How to Run

```bash
# 1. Install dependencies
pip install pandas numpy matplotlib seaborn plotly scikit-learn jupyter

# 2. Launch the notebook
jupyter notebook sales_analysis.ipynb
```

Run all cells sequentially. The notebook will generate:
- 📈 5 static charts (`.png`)
- 🖱️ 1 interactive dashboard (`interactive_dashboard.html`)
- 📋 2 executive reports (printed output)

> **Quick demo:** Open `interactive_dashboard.html` directly in any browser — no Python needed.

---

## 📁 Project Structure

```
Retail-Sales-Dashboard/
├── sales_analysis.ipynb         # Main analytics notebook (10 steps)
├── README.md                    # Project documentation
├── .gitignore                   # Git configuration
└── (generated outputs)
    ├── trend_analysis.png
    ├── monthly_revenue_bar.png
    ├── regional_distribution.png
    ├── correlation_heatmap.png
    ├── forecast_report.png
    ├── pareto_analysis.png
    └── interactive_dashboard.html
```

---

*Created by **Akif Şahin** — Data Analytics Portfolio Project*
