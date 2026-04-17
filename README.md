# 🍫 Chocolate Shipments Dashboard — Power BI

> An interactive, multi-page Sales & Shipments Performance Dashboard built in Power BI,
> analyzing revenue, profit, logistics, and team performance across products and regions.

---

## 📋 Table of Contents

- [Overview](#overview)
- [Tools & Technologies](#tools--technologies)
- [Dataset Description](#dataset-description)
- [Dashboard Pages & Features](#dashboard-pages--features)
- [Key Insights](#key-insights)
- [Dashboard Preview](#dashboard-preview)
- [Business Value](#business-value)
- [Future Improvements](#future-improvements)
- [Author](#author)

---

## Overview

The **Chocolate Shipments Dashboard** is a comprehensive Power BI report that transforms
raw sales and logistics data into actionable business intelligence.

The dashboard spans **6 report pages** and **19 interactive visualizations**, enabling
stakeholders to explore KPIs across products, geographies, time periods, and individual
salesperson performance — all with dynamic filtering and drill-down capabilities.

---

## 🛠️ Tools & Technologies

| Tool / Technology         | Purpose                                      |
|---------------------------|----------------------------------------------|
| Power BI Desktop          | Dashboard design and report publishing       |
| Power Query               | Data cleaning, shaping, and transformation   |
| DAX (Data Analysis Expressions) | Custom KPI measures and calculated columns |
| Data Modeling             | Star-schema relational table design          |

---

## 📁 Dataset Description

The dashboard is powered by a star-schema data model with five interconnected tables:

| Table         | Key Fields                                              | Role                              |
|---------------|---------------------------------------------------------|-----------------------------------|
| `shipments`   | Amount, Total Profit, Profit %, Total Boxes, Shipment Count | Central fact table — all KPIs |
| `products`    | Product, Category                                       | Product dimension                 |
| `locations`   | Geo                                                     | Geographic dimension              |
| `people`      | Sales_person, Team, First Name, Picture                 | HR / Salesperson dimension        |
| `calendar`    | Year, Month_num                                         | Time intelligence dimension       |

---

## 📊 Dashboard Pages & Features

### Page 1 — Sales Analysis
- Column chart: Sales amount by product (sorted descending)
- Pie chart: Revenue contribution by sales team
- Slicer: Geographic region filter for dynamic page-level filtering

### Page 2 — Profit Analysis
- Clustered column chart: Total profit comparison by region
- Detailed table: Product-level profit, revenue, and profit % breakdown

### Page 3 — Shipment Trends
- Line chart: Shipment count over time (monthly & yearly trends)
- Donut chart: Shipment distribution by sales team

### Page 5 — Salesperson Performance
- Table: Top 5 employees by profit %
- Table: Bottom 5 employees by profit %
- Table: Full salesperson performance overview
- Clustered column chart: Monthly profit trend by salesperson

### Page 8 — KPI Summary
- Multi-KPI card: Total Amount, Total Profit, Profit %, Shipment Count, Total Boxes
- Slicer: Product category filter for segmented KPI view

### BI Report (Executive Page)
- Donut chart: Revenue by geography
- Histogram: Shipment size distribution (boxes binned)
- Leaderboard table: Top 6 salespersons with profile photos
- Treemap: Top 6 products by revenue
- Summary table: All products with revenue and profit %
- KPI card: Global performance summary

---

## 📈 Key Insights

- 🏆 Identified top-performing products that drive the majority of revenue
- 🌍 Revealed significant profit variation across geographic regions
- 📅 Detected seasonal shipment peaks enabling proactive capacity planning
- 👥 Surfaced top and bottom salesperson performance for targeted coaching
- 📊 Delivered a single-page executive KPI view for fast decision-making

---

## 📷 Dashboard Preview

> 📌 *Open the `.pbix` file in Power BI Desktop to explore the full interactive dashboard.*

| Page | Description |
|------|-------------|
| Page 1 | Sales by Product & Region |
| Page 2 | Profit Analysis |
| Page 3 | Shipment Trends |
| Page 5 | Salesperson Performance |
| Page 8 | KPI Summary |
| BI Report | Executive Dashboard |

*(Add screenshots here after opening in Power BI Desktop)*

---

## 💼 Business Value

This dashboard empowers stakeholders to:

- ✅ Monitor all critical KPIs from a single executive view
- ✅ Identify high and low-performing products and regions instantly
- ✅ Optimize logistics and shipment planning using trend data
- ✅ Evaluate and improve individual salesperson performance
- ✅ Make faster, data-driven decisions without manual reporting

---

## 🔮 Future Improvements

- [ ] Add date range slicers for time-window filtering across all pages
- [ ] Implement Row-Level Security (RLS) for regional manager access control
- [ ] Build drillthrough pages for individual product and salesperson deep dives
- [ ] Apply conditional formatting to profit % columns for instant anomaly detection
- [ ] Add custom tooltip pages with enriched context on hover
- [ ] Optimize mobile layout for tablet and phone viewing

---

## 👩‍💻 Author

**Asmitha Chapa**

- 🐙 GitHub: [github.com/Asmithachapa](https://github.com/Asmithachapa)
- 💼 LinkedIn: [linkedin.com/in/asmitha-chapa-b5a86b377](https://www.linkedin.com/in/asmitha-chapa-b5a86b377)

---

⭐ If you found this project useful, consider giving it a star!
