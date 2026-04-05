# 📊 Power BI Electronic Sales Analytics Dashboard

> **A complete end-to-end Power BI solution for sales performance analysis — from data modeling to executive dashboards**

---

## 🎯 Overview

This repository contains a **fully built Power BI report** that analyzes sales performance across products, regions (cities), and delivery efficiency. The solution includes:

- ✅ **Data modeling** (Star Schema with Fact & Dimension tables)
- ✅ **Currency conversion** (USD & CAD)
- ✅ **Time intelligence** (YTD, YoY, monthly trends)
- ✅ **Interactive dashboards** with KPIs, charts, and slicers
- ✅ **Multi-page report** for deep-dive analysis

Designed for **executives, sales teams, and logistics managers** to make data-driven decisions.

---

## 🛠️ Key Features

### 1. **Data Modeling (Star Schema)**
- **Fact Table**: `SalesFact` (transactional data)
- **Dimension Tables**: `ProductDimension`, `CustomerDimension`, `TimeDimension`, `SalesRepDimension`
- **Currency Conversion**: `CurrencyRates` table for USD/CAD conversion
- **Relationships**: One-to-many from dimensions to fact table

### 2. **DAX Measures**
- `Total Sales USD`, `Total Profit USD`, `Profit Margin %`
- `Avg Delivery Time (Days)`, `Count of Late Orders`
- `Sales YTD`, `Sales Last Year`, `YoY Growth %`

### 3. **Interactive Dashboards**
- **Executive Dashboard**: KPIs, sales trends, product & region performance
- **Product Performance**: Top products by sales & profit margin
- **Regional Analysis**: Sales & profit by city (North America focus)
- **Delivery & Customer Performance**: Delivery time, late orders, top customers

### 4. **Time Intelligence**
- Full `TimeDimension` table (2026 calendar)
- Monthly, quarterly, and YTD trends
- Marked as date table for DAX time functions

### 5. **Currency Handling**
- Converts all sales & profit to **USD** using exchange rates
- Supports **USD & CAD** only (simplified for business needs)

---

## 🧩 How to Use

1. **Open the `.pbix` file** in Power BI Desktop
2. **Refresh data** (if connected to live source)
3. **Interact with slicers** to filter by:
   - Year, Quarter, City, Category, Sales Rep
4. **Navigate between pages** using tabs or “Back to Dashboard” buttons
5. **Publish to Power BI Service** for sharing and scheduling refreshes

---

## 📌 Business Insights Delivered

- **Executive Dashboard**: KPI cards, sales trend line chart, product bar chart, map by city
- **Product Performance**: Scatter plot (profit vs. sales), top products by category
- **Regional Analysis**: Sales & profit by city, delivery time by city
- **Delivery & Customer Performance**: Avg delivery time by month, top customers by sales

---

## 📝 Recommendations (Based on Data)

1. **Promote high-margin products** like *Sonos One Speakers* and *MacBook Pro 14"*
2. **Optimize logistics** in cities with long delivery times (e.g., San Francisco)
3. **Reallocate marketing spend** to high-sales cities (Toronto, Boston)
4. **Investigate low-margin cities** (e.g., Miami) for cost reduction opportunities

---

## 🚀 Future Steps

- [ ] Add **automated currency rate updates** (via API or Excel)
- [ ] Build a **mobile-optimized layout**
- [ ] Add **drill-through** to transaction details
- [ ] Export to **PDF/PowerPoint** for presentations
- [ ] Schedule **daily refreshes** in Power BI Service

---

## 📄 License

This project is licensed under the **MIT License** — see `LICENSE` for details.

---

## 🎉 Acknowledgments

Built with ❤️ using **Power BI Desktop** and **DAX**.  
Inspired by real-world sales analytics needs.

---
