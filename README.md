<div align="center">

# 🎨 ━━ Asian Paints · Executive Sales Dashboard ━━ 🎨
### *Interactive Power BI Report on Revenue, Regions, Products, Dealers & Forecasting*

[![Power BI](https://img.shields.io/badge/Power%20BI-Dashboard-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)](https://powerbi.microsoft.com/)
[![DAX](https://img.shields.io/badge/DAX-Measures%20%26%20KPIs-0A3FD1?style=for-the-badge&logo=microsoft&logoColor=white)](https://learn.microsoft.com/en-us/dax/)
[![MySQL](https://img.shields.io/badge/MySQL-Data%20Source-4479A1?style=for-the-badge&logo=mysql&logoColor=white)](https://www.mysql.com/)
[![Sales Analytics](https://img.shields.io/badge/Domain-Sales%20Analytics-FF6F00?style=for-the-badge&logo=target&logoColor=white)](https://powerbi.microsoft.com/)
[![Pages](https://img.shields.io/badge/Report%20Pages-5-4CAF50?style=for-the-badge&logo=googleanalytics&logoColor=white)](https://powerbi.microsoft.com/)

<br/>

![Revenue](https://img.shields.io/badge/💰%20Revenue-₹176.68%20Cr-0A3FD1?style=flat-square)
![Profit](https://img.shields.io/badge/📈%20Profit-₹57.52%20Cr-2E7D32?style=flat-square)
![Margin](https://img.shields.io/badge/%25%20Margin-32.55%25-7B1FA2?style=flat-square)
![Orders](https://img.shields.io/badge/🧾%20Orders-75K-FB8C00?style=flat-square)
![Target](https://img.shields.io/badge/🎯%20Target%20Achieved-102.46%25-00897B?style=flat-square)

<br/>

> *"Every great color starts with a drop — every great decision starts with data."*

</div>
---
Video Link - https://drive.google.com/drive/u/0/folders/1XHJ6_SMOhRFSydBG2MxhBsNn4ct9P3Qw
## 📋 Table of Contents

- [📌 Overview](#-overview)
- [🎯 Problem Statement](#-problem-statement)
- [✨ Key Features](#-key-features)
- [🏗️ Project Structure](#️-project-structure)
- [🔄 Project Workflow](#-project-workflow)
- [📊 Dashboard Pages](#-dashboard-pages)
  - [🏠 Page 1 — Executive Overview](#-page-1--executive-overview)
  - [📍 Page 2 — Regional Performance](#-page-2--regional-performance)
  - [🚀 Page 3 — Product Analytics](#-page-3--product-analytics)
  - [🤝 Page 4 — Dealer Performance](#-page-4--dealer-performance)
  - [📈 Page 5 — Trends & Executive Summary](#-page-5--trends--executive-summary)
- [🛠️ Tech Stack](#️-tech-stack)
- [📈 Results & Insights](#-results--insights)
- [🏆 Advantages](#-advantages)
- [⚙️ How to Run](#️-how-to-run)
- [📄 License](#-license)
- [👤 Author](#-author)
- [🙏 Acknowledgements](#-acknowledgements)

---

## 📌 Overview

The **Asian Paints Executive Dashboard** is a five-page, interactive **Power BI** report that converts sales data into clear business insight. It tracks **revenue, profit, margin, orders and target achievement** across regions, product categories and **5,000 dealers**, and closes with a year-over-year trend view and a **6-month revenue forecast**.

This project is designed to:
- 📊 Give leadership a one-glance view of sales health versus target
- 🗺️ Compare performance across **Region ➜ Zone ➜ State ➜ City**
- 🎨 Identify top products, categories and inventory turnover
- 🤝 Evaluate dealer productivity, types and locations
- 🔮 Compare against the previous year and look ahead with forecasting

> 📅 **Data as on:** 31 Mar 2024 &nbsp;|&nbsp; 💱 **All values in ₹ Crores** &nbsp;|&nbsp; **PY** = Previous Year

---

## 🎯 Problem Statement

> **Objective:** Build an interactive sales analytics dashboard that helps management monitor performance against targets and decide where to focus growth.

Sales teams generate large volumes of transaction data, but without visualization it is difficult to answer: *"Are we hitting target?"*, *"Which regions and categories drive profit?"*, *"Which dealers perform best?"* and *"What does the next quarter look like?"*

| 📂 Dashboard Page | 📄 Focus Area | 🔍 Key Question Answered |
|-------------------|---------------|--------------------------|
| 🏠 Executive Overview | Top-line KPIs | How are revenue, profit and targets doing overall? |
| 📍 Regional Performance | Geography | Which regions and states drive revenue and margin? |
| 🚀 Product Analytics | Products & Categories | Which products and categories perform best? |
| 🤝 Dealer Performance | Dealer Network | Which dealers and dealer types create the most value? |
| 📈 Trends & Summary | Growth & Forecast | How are we trending versus last year and what's next? |

The goal is to demonstrate **end-to-end BI skills**: data modeling, DAX, visual design and storytelling.

---

## ✨ Key Features

| Feature | Description |
|--------|-------------|
| 🗂️ **5 Interactive Pages** | Left navigation panel with highlighted active page |
| 📅 **Date Range Slicer** | Analyze any custom time window |
| 🎛️ **Smart Filters** | Region, Zone, State, City, Product Category, Sub Category, Product, Price Tier, Dealer Type |
| 🔽 **Hierarchy Drill-Down** | Region ➜ Zone ➜ State ➜ City and Category ➜ Sub Category ➜ Product |
| 🔢 **KPI Cards with vs-PY** | Every KPI shows change versus previous year |
| 🚦 **Target Scorecards** | Revenue / Profit achievement with traffic-light indicators |
| 🗺️ **Map Visuals** | Filled map by state and dealer location map |
| 🔮 **Forecasting** | 6-month revenue forecast with 95% confidence band |
| 💡 **Insight Call-outs** | Highlighted notes and executive summary banners |
| 🔄 **Reset Button** | One click to clear all filters |

---

## 🏗️ Project Structure

```
📦 asian-paints-dashboard/
│
├── 📄 AsianPaints_.pbix          ← Power BI report file (data model + visuals)
│
├── 🖼️ images/                    ← Dashboard screenshots
│   ├── ap-01-executive-overview.png
│   ├── ap-02-regional-performance.png
│   ├── ap-03-product-analytics.png
│   ├── ap-04-dealer-performance.png
│   └── ap-05-trends-summary.png
│
└── 📄 README.md                  ← Project documentation
```

---

## 🔄 Project Workflow

```
Raw Sales Data (Orders, Products, Dealers, Regions, Targets)
      │
      ▼
┌──────────────────────────────┐
│  Power Query — Clean & Shape │  ← Types, nulls, dates, hierarchies
└────────────┬─────────────────┘
             │
             ▼
┌──────────────────────────────┐
│   Data Model (Star Schema)   │  ← Fact tables + Date, Product, Dealer, Region dims
└────────────┬─────────────────┘
             │
             ▼
┌──────────────────────────────┐
│    DAX Measures & KPIs       │  ← Revenue, Profit, Margin %, Achievement %, YoY, PY
└────────────┬─────────────────┘
             │
     ┌───────┴───────┬──────────────┬──────────────┬──────────────┐
     ▼               ▼              ▼              ▼              ▼
┌─────────┐   ┌───────────┐  ┌───────────┐  ┌───────────┐  ┌───────────┐
│Executive│   │ Regional  │  │  Product  │  │  Dealer   │  │  Trends & │
│Overview │   │Performance│  │ Analytics │  │Performance│  │  Summary  │
└─────────┘   └───────────┘  └───────────┘  └───────────┘  └───────────┘
             │
             ▼
   Insights & Business Decisions ✅
```

---

## 📊 Dashboard Pages

### 🏠 Page 1 — Executive Overview

> A one-page view of the company's top-line performance versus target.

<div align="center">

![Executive Overview](images/ap-01-executive-overview.png)

</div>

**What's inside:**

| Visual | Purpose |
|--------|---------|
| 🔢 KPI Cards | Revenue (**₹176.68 Cr**), Profit (**₹57.52 Cr**), Margin (**32.55%**), Orders (**75K**), Target Achievement (**102.46%**) |
| 📈 Revenue Trend | Monthly revenue, Apr 23 ➜ Mar 24 |
| 📊 Revenue vs Target | Bars for revenue and target, line for achievement % |
| 🟩 Revenue by Category | Treemap of category contribution |
| 🗺️ Revenue by Region | State-level map |
| 📋 Executive Scorecard | Revenue / Profit achievement % per category with status lights |

**Highlights:**
- 💰 Revenue is up **1.6%** and profit up **2.0%** versus the previous year
- 🥇 **Putty** is the largest category (₹29.04 Cr), followed by **Interior Emulsion** (₹28.71 Cr)
- 🟢 Every category beat its revenue target except **Interior Emulsion** (99.68%)
- 🏁 Overall profit achievement is **106.79%**

---

### 📍 Page 2 — Regional Performance

> Analyze performance across Region ➜ Zone ➜ State ➜ City.

<div align="center">

![Regional Performance](images/ap-02-regional-performance.png)

</div>

**What's inside:**

| Visual | Purpose |
|--------|---------|
| 🔢 KPI Cards | Revenue, Profit, Target Achievement, Orders, Profit Margin |
| 🗺️ Filled Map | Revenue by state |
| 📊 Region Ranking | Revenue and contribution by region |
| 🏆 Top 10 States | Highest revenue states |
| 📊 Revenue vs Target by Region | Bars with achievement % line |
| 🔥 Margin Heatmap | Profit margin % by State × Region |

**Highlights:**
- 🌎 **West** leads with **₹43.28 Cr** and the best target achievement (**105.97%**)
- 📊 North ₹33.19 Cr, South ₹31.47 Cr, East ₹34.34 Cr, Central ₹34.40 Cr
- 🏔️ Top states include **Mizoram** (8.0% of revenue) and **Himachal Pradesh** (7.3%)
- ⚠️ **Central** is the only region slightly below target (**99.32%**)
- 💹 Profit margins are very stable at roughly **32.3% – 32.9%** across states

---

### 🚀 Page 3 — Product Analytics

> Comprehensive insights across Product ➜ Sub Category ➜ Category.

<div align="center">

![Product Analytics](images/ap-03-product-analytics.png)

</div>

**What's inside:**

| Visual | Purpose |
|--------|---------|
| 🔢 KPI Cards | Revenue, Profit, Margin, Total Products (**500**), Avg Inventory Turnover (**1.87**) |
| 📊 Product Revenue / Profit (Top 10) | Best-performing products |
| 🍩 Category Contribution | Donut chart with revenue share |
| 📊 Inventory Turnover by Category | Stock efficiency comparison |
| 📋 Top Products by Revenue | Ranked product table |
| 🔵 Revenue vs Profit Scatter | Relationship with **R² = 0.96** |

**Highlights:**
- 🥇 **Asian Paint Product 168** and **Product 470** top the revenue chart (₹0.45 Cr each)
- 🎨 **Putty** contributes the most revenue (**16.4%**); **Waterproofing** the least (**11.7%**)
- 🔄 **Waterproofing** has the best inventory turnover (**1.94**); **Wood Finish** the lowest (**1.83**)
- 📐 Revenue and profit are strongly correlated (R² = 0.96)

---

### 🤝 Page 4 — Dealer Performance

> Track and analyze dealer performance across India.

<div align="center">

![Dealer Performance](images/ap-04-dealer-performance.png)

</div>

**What's inside:**

| Visual | Purpose |
|--------|---------|
| 🔢 KPI Cards | Dealer Revenue, Profit, **5,000** Dealers, Orders, Avg Revenue per Dealer (**₹3.53 Lakh**), Satisfaction (**4.19 / 5**) |
| 🏆 Top 10 Dealers | Ranked by revenue |
| 📊 Revenue per Dealer | Distribution of dealers by revenue band |
| 📈 Dealer Visits Trend | Monthly visits vs orders booked |
| 🍩 Satisfaction Rating | Dealer rating breakdown |
| 📊 Revenue by Dealer Type | Distributor, Retail, Silver, Premium, Gold |
| 🗺️ Dealer Location Map | Geographic spread + Top 5 cities |

**Highlights:**
- 📊 Most dealers (**1,862**) generate ₹3–4 Lakh; only **9** exceed ₹7 Lakh
- 💎 **Premium & Gold** dealers contribute **39.2%** of total revenue
- 🏙️ Top cities by dealer revenue: **Jamnagar**, **Ghaziabad**, **Aurangabad**
- ℹ️ Satisfaction ratings are sample (placeholder) values, not part of the dataset

---

### 📈 Page 5 — Trends & Executive Summary

> Track performance trends, growth and future outlook.

<div align="center">

![Trends & Executive Summary](images/ap-05-trends-summary.png)

</div>

**What's inside:**

| Visual | Purpose |
|--------|---------|
| 🔢 KPI Cards | YTD Revenue, YTD Profit, Margin, YoY Revenue Growth, YoY Profit Growth, Orders |
| 📈 Revenue & Profit Trend | FY 2023-24 vs FY 2022-23 by month |
| 🌄 YTD Revenue (Cumulative) | Running total versus last year |
| 🔮 Revenue Forecast | Next 6 months with 95% confidence band |
| 📋 Executive Scorecard | Actual vs Target vs Achievement % vs PY |
| 📉 YoY Growth Trend | Revenue and profit growth % by month |
| 📝 Executive Summary | Four-point summary banner |

**Highlights:**
- 🎯 Revenue **₹176.68 Cr** vs target **₹172.44 Cr** ➜ **102.5%** achievement
- 💹 Profit **₹57.52 Cr** vs target **₹53.86 Cr** ➜ **106.8%** achievement
- 📈 Margin of **32.55%** is above the **31.23%** target
- ✅ Summary: *Steady Revenue Growth · Healthy Profitability · On Track with Targets · Forecast Outlook*

---

## 🛠️ Tech Stack

| Tool | Purpose |
|------|---------|
| 📊 **Microsoft Power BI Desktop** | Report building & visualization |
| 🧮 **DAX** | Measures, YoY / PY comparisons, achievement %, rankings |
| 🧹 **Power Query (M)** | Data cleaning and transformation |
| 🗄️ **MySQL** | Source database |
| 🔗 **Data Modeling** | Star schema with date, product, dealer and region dimensions |
| 🗺️ **Bing Maps Visual** | State-level and dealer-location maps |
| 🔮 **Power BI Forecasting** | 6-month forecast with confidence interval |

---

## 📈 Results & Insights

After exploring the dashboard, the following conclusions emerge:

- ✅ **Target Beaten** — Revenue at 102.46% and profit at 106.79% of target
- 💹 **Strong Margins** — A consistent ~32.55% margin across regions and categories
- 🌎 **West Leads** — Highest revenue (₹43.28 Cr) and best achievement (105.97%)
- ⚠️ **Watch List** — Interior Emulsion (99.68%) and the Central region (99.32%) sit just under target
- 🎨 **Balanced Portfolio** — Putty leads at 16.4% share, but no category dominates
- 🔄 **Efficient Stock** — Waterproofing turns inventory fastest (1.94×)
- 💎 **Premium & Gold dealers** drive nearly 40% of revenue
- 🔮 **Positive Outlook** — Revenue up 1.6% and profit up 2.0% YoY, with a 6-month forecast included

---

## 🏆 Advantages

| Advantage | Detail |
|-----------|--------|
| 🎯 **Single Source of Truth** | All sales KPIs in one interactive report |
| 🔍 **Actionable Insights** | Pinpoints regions, products and dealers needing attention |
| 🎛️ **Fully Interactive** | Cross-filtering, hierarchies and drill-downs on every page |
| 📅 **PY Comparison** | Every KPI is benchmarked against the previous year |
| 🎨 **Visually Consistent** | Navy-blue theme with intuitive side navigation |
| 🔮 **Forward Looking** | Includes forecasting, not just history |
| 🔄 **Refreshable** | Update the data source and all visuals refresh automatically |
| 🧪 **Extensible** | Easy to add pages such as Customer, Discount or Supply Chain |

---

## ⚙️ How to Run

1. **Clone** this repository
   ```bash
   git clone https://github.com/your-username/asian-paints-dashboard.git
   ```
2. **Install** [Power BI Desktop](https://powerbi.microsoft.com/desktop/) (free, Windows)
3. **Open** `AsianPaints_.pbix`
4. If the report connects to MySQL, make sure the **MySQL80** service is running and refresh the data
5. Use the **left navigation panel** to switch pages, and **slicers** to filter
6. Click **Reset** to clear all filters

---

## 📄 License

This project is licensed under the **MIT License** — see the [LICENSE](LICENSE) file for full details.

```
MIT License — Free to use, modify, and distribute with attribution.
```

> ⚠️ *Disclaimer: This is an educational/portfolio project. The dataset is simulated, and the Asian Paints name and branding are used only for illustration. It is not affiliated with or endorsed by Asian Paints.*

---

## 👤 Author

Asvi Ambaliya

### Your Name

[![GitHub](https://img.shields.io/badge/GitHub-yourhandle-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/yourhandle)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/your-profile/)

> *"Every dashboard starts with a question — and ends with a decision."*

**🎓 Role:** Data Analyst | Power BI Developer \
**📍 Location:** India \
**🛠️ Skills:** Power BI · DAX · Power Query · MySQL · Data Modeling · Sales Analytics

</div>

---

## 🙏 Acknowledgements

Special thanks to the following resources and communities that made this project possible:

- 📚 [Microsoft Power BI Docs](https://learn.microsoft.com/en-us/power-bi/) — Official Power BI documentation
- 🧮 [DAX Guide](https://dax.guide/) — Complete DAX function reference
- 🎓 [SQLBI](https://www.sqlbi.com/) — Data modeling and DAX best practices
- 🗄️ [MySQL Docs](https://dev.mysql.com/doc/) — Database reference
- 💬 [Power BI Community](https://community.fabric.microsoft.com/) — Problem-solving support
- 📖 [Microsoft Learn](https://learn.microsoft.com/en-us/training/powerplatform/power-bi) — Power BI learning paths

---

<div align="center">
Asvi Ambaliya
</div>
# AsianPaints-
