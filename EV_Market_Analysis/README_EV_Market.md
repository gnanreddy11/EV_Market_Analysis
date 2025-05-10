# EV Market Segmentation Strategy

This repository contains a full analysis of the Indian Electric Vehicle (EV) market to identify optimal customer and geographic segments for market entry. The project was developed as part of a solo internship assignment, focusing on data-driven market segmentation aligned with the **Innovation Adoption Life Cycle**.

---

## 📁 Repository Structure

```
EV_Market_Analysis/
├── data/
│   ├── EV Maker by Place.csv
│   ├── Vehicle Class - All.csv
│   └── ev_sales_by_makers_and_cat_15-24.csv
├── notebooks/
│   └── ev_market_analysis.ipynb
├── reports/
│   └── Gnan_Reddy_EV_Report.pdf
├── README.md
```

---

## 🧠 Project Objective

To help an EV startup determine:
- The best customer and vehicle segments to target
- Geographic regions suitable for early market adoption
- Strategic insights for pricing, promotion, and rollout based on data

---

## 📊 Dataset Overview

| Dataset | Description |
|---------|-------------|
| **EV Maker by Place.csv** | Lists Indian cities and states where EV manufacturers are located |
| **Vehicle Class - All.csv** | Category-wise total EV registration data (2W, 3W, 4W, etc.) |
| **ev_sales_by_makers_and_cat_15-24.csv** | Year-wise EV sales data by manufacturer and category from 2015–2024 |

All data was sourced from government and open-source platforms like [data.gov.in](https://data.gov.in/) and [EV Reporter](https://evreporter.com/).

---

## 🧹 Preprocessing & Tools Used

- Cleaned missing values
- Converted textual numbers (e.g. "1,23,456") to numerical
- Aggregated data for trend and cluster analysis

**Tools:** `Pandas`, `NumPy`, `Seaborn`, `Matplotlib`, `Scikit-learn`

---

## 🔍 Analysis Performed

### ✅ Exploratory Data Analysis
- EV manufacturer hotspots: Karnataka, Maharashtra, Delhi
- Popular EV segments: 2W > 3W > 4W
- Strong EV sales growth post-2020

### ✅ Clustering (KMeans Simulation)
Segmented hypothetical EV buyers based on:
- Age
- Income
- EV Adoption Propensity

Identified 3 customer segments and focused on **Cluster 0: Early Urban Adopters**.

---

## 📦 Marketing Strategy Highlights

| Category | Strategy |
|----------|----------|
| **Product** | Electric scooters (2W) and delivery EVs (3W) |
| **Price** | ₹1–3L for 2W; ₹3–6L for 3W |
| **Place** | Bengaluru, Pune, Delhi NCR (Phase 1) |
| **Promotion** | Digital-first campaigns, student ambassador programs, influencer collaborations |

---

## 💰 Profit Estimation

- **Early Market**: 100,000 target users
- **Conversion**: 5%
- **Revenue Estimate**: ₹60 Crores in early phase (avg. ₹1.2L per unit)

---

## 📄 Final Deliverables

- 📘 `ev_market_analysis.ipynb`: Full notebook with EDA, clustering, and insights
- 📑 `Gnan_Reddy_EV_Report.pdf`: Professional business report
- 📂 `data/`: Cleaned and organized datasets used

---

## 👤 Author

**Gnan Reddy Bobba**  
Solo Intern – Data Science & Market Analytics  
[LinkedIn](https://linkedin.com/in/gnanreddy11) | [GitHub](https://github.com/gnanreddy11)

---

Feel free to ⭐ the repo or fork it for future enhancements!
