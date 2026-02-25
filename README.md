# Agency Project Performance & Profitability Dashboard

## 📌 Project Overview
A high-level Business Intelligence solution built in **Looker Studio** to manage and analyze the performance of 60+ active agency projects. This dashboard bridges the gap between raw financial data and executive decision-making.

## 🚀 Key Features & Engineering Challenges

### 1. Minimalist Performance Tracking (Page 1)
* **Linear Progress Indicators:** Replaced bulky bullet charts with sleek, linear bars for a modern Executive UI.
* **Target-to-Actual Scorecards:** Integrated conditional formatting to highlight KPI variances instantly.

### 2. Advanced Efficiency Benchmarking (Page 2)
* **Dynamic Trendline Analysis:** Utilizing Scatter Charts to visualize the correlation between Revenue and Labor Cost.
    * **Above Trendline:** High-margin "Benchmark" projects.
    * **Below Trendline:** Projects with disproportionate labor costs requiring immediate audit.
* **Relative Ratios:** Shifted from absolute dollar values to **Labor Cost Ratios (%)** to ensure fair comparisons across small and large-scale projects.

## 🛠 Tech Stack
* **Platform:** Looker Studio
* **Data Source:** Google Sheets (Standardized Flat Schema)
* **Logic & Analytics:** SQL-based Calculated Fields, Data Blending, Trend Analysis.

## 📊 Dashboard Link: https://lookerstudio.google.com/s/qJ0i4sq7-3Y

## 📖 Strategy & Insights
The dashboard isn't just a display—it's a management tool. By identifying the "Green Zone" projects, the agency can replicate successful staffing models across underperforming accounts.

## 📁 Project Structure
```Agency Project Performance & Profitability Dashboard
├── data/
│   └── sample_data.csv    
├── images/
│   ├── overview.png       
│   └── efficiency.png     
└── README.md              

---
**Developed by:** Dat Do  
**Connect with me:** (https://www.linkedin.com/in/datdonguyenphat/)
