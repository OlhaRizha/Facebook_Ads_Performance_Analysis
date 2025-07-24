# Facebook Ads Performance Analysis

This project explores the performance of Facebook advertising campaigns using Python. The goal is to uncover trends, evaluate efficiency, and identify top- and underperforming campaigns using custom marketing KPIs and visual analytics.

## 📊 Objective

Analyze ad performance at both daily and campaign levels with the help of:
- Spend and ROMI dynamics over time
- Custom metrics: CPC, CPM, CTR, ROMI
- Correlation and regression insights

## 🧰 Tools Used
- Python (Pandas, Matplotlib, Seaborn)
- Jupyter Notebook
- CSV dataset (facebook_ads_data.csv)

## 📁 Dataset Overview

- Columns:
  - `ad_date` — date of the ad
  - `campaign_id` — unique campaign ID
  - `total_spend`, `impressions`, `clicks`, `value`
  - `romi` — return on marketing investment

## 📈 Key Analysis Tasks

- 📆 **Daily Analysis**:
  - Visualized daily spend and ROMI
  - Applied 7-day rolling averages for trend smoothing

- 📊 **Campaign-Level KPIs**:
  - Calculated:
    - **CPC** = Spend / Clicks
    - **CPM** = Spend per 1000 Impressions
    - **CTR** = Clicks / Impressions
    - **ROMI** = Value / Spend

- 🧪 **Exploratory Analysis**:
  - Correlation heatmap between KPIs
  - Regression plots to investigate relationships (e.g., Spend vs. ROMI)

## ✅ Key Insights

- Identified low-efficiency campaigns with high spend but low ROMI
- Found strong correlation between CPM and ROMI decline
- Suggested optimization directions based on performance drivers

## 📌 Outcome

Strengthened skills in EDA, KPI calculation, and storytelling with data. Project delivered as part of a personal data analytics portfolio.

---

> 💡 This notebook is part of my data analysis project collection.
