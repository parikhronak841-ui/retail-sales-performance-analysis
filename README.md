# 🛒 Retail Sales Performance Analysis

![Python](https://img.shields.io/badge/Python-3.9+-blue?logo=python)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Wrangling-150458?logo=pandas)
![Plotly](https://img.shields.io/badge/Plotly-Interactive%20Viz-3F4F75?logo=plotly)
![Excel](https://img.shields.io/badge/Excel-Power%20BI%20Ready-217346?logo=microsoft-excel)
![Status](https://img.shields.io/badge/Status-Complete-brightgreen)

## 📌 Project Overview

A full-year retail sales performance analysis covering **20 stores, 5 product categories, and 5 Canadian regions** across 2023. This project demonstrates end-to-end data analysis: data generation, cleaning, exploration, visualization, and business storytelling — ready for Power BI dashboard connection.

---

## 🎯 Business Questions Answered

- Which months and seasons drive peak revenue?
- Which product categories contribute most to sales and have the highest return rates?
- How do regions compare in sales performance?
- Does discounting actually drive more sales?
- Where should the business invest for maximum ROI?

---

## 🗂️ Dataset

| Attribute | Detail |
|---|---|
| Period | January 2023 – December 2023 |
| Stores | 20 retail locations |
| Categories | Electronics, Furniture, Clothing, Appliances, Sports |
| Regions | Ontario, BC, Alberta, Quebec, Manitoba |
| Metrics | Sales, Units Sold, Transactions, Returns, Discounts |

---

## 🔧 Tools & Libraries

| Tool | Purpose |
|---|---|
| `Python` | Data generation & analysis |
| `Pandas` | Data manipulation & aggregation |
| `Plotly` | Interactive charts |
| `OpenPyXL` | Excel export for Power BI |

---

## 📊 Analysis Modules

### 1. Monthly Sales Trend
- Revenue bar chart with Month-over-Month growth overlay
- Identifies seasonal peaks (Nov–Dec holiday surge)

### 2. Category Performance
- Revenue share pie chart + return rate comparison
- Reveals top performers and high-return-risk categories

### 3. Regional Analysis
- Bar chart of net sales by Canadian province
- Highlights Ontario dominance and underperforming regions

### 4. Seasonality Heatmap
- Category × Month matrix showing when each category peaks
- Directly actionable for inventory planning

### 5. Discount vs. Sales Analysis
- Scatter plot revealing discount effectiveness by category
- Challenges assumption that deep discounts always drive volume

---

## 💡 Key Insights

| # | Insight | Action |
|---|---|---|
| 1 | Nov–Dec sales spike 30–50% | Scale inventory & staff ahead of Q4 |
| 2 | Electronics = highest revenue share | Prioritize in promotional spend |
| 3 | Ontario leads all regions | Replicate store strategy in other provinces |
| 4 | High discounts don't linearly improve sales | Move to targeted, data-driven promotions |
| 5 | Some categories have 6%+ return rates | Review product quality & descriptions |

---

## 📁 Project Structure

```
project2_retail_sales/
│
├── retail_sales_analysis.py           # Main analysis script
├── monthly_sales_trend.html           # Interactive chart
├── category_performance.html          # Interactive chart
├── regional_sales.html                # Interactive chart
├── seasonality_heatmap.html           # Interactive heatmap
├── discount_vs_sales.html             # Interactive scatter
├── retail_sales_dashboard_data.xlsx   # Excel export (Power BI ready)
└── README.md                          # This file
```

---

## 🚀 How to Run

```bash
# 1. Clone the repo
git clone https://github.com/yourusername/retail-sales-analysis.git
cd retail-sales-analysis

# 2. Install dependencies
pip install pandas numpy plotly openpyxl

# 3. Run the analysis
python retail_sales_analysis.py

# 4. (Optional) Connect retail_sales_dashboard_data.xlsx to Power BI
```

---

## 📊 Power BI Dashboard

The Excel output (`retail_sales_dashboard_data.xlsx`) contains 4 pre-aggregated sheets ready for Power BI connection:
- **Raw Data** — Full transactional dataset
- **Monthly Trend** — Time series with MoM growth
- **Category Performance** — KPIs per product category
- **Regional Performance** — Geographic sales comparison

---

## 👤 Author

**Ronak Parikh**
- 📧 parikhronak841@gmail.com
- 💼 [LinkedIn](https://www.linkedin.com/in/yourprofile)
- 🎓 Business Administration – Finance | Conestoga College
- 📜 IFIC Mutual Fund License | IBM Data Analyst Certificate (In Progress)

---

## 📝 License

MIT License
