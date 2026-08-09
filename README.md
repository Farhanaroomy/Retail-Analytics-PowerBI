# 🛒 Retail Analytics Power BI Dashboard

## 📌 Project Overview
An interactive and dynamic end-to-end Power BI report engineered to track retail performance, sales revenue trends, payment mode share, and regional profitability.

---

## 📊 Key KPIs & Metrics
- **Total Revenue:** ₹290.20K
- **YTD Sales:** ₹290.20K
- **Previous Month Sales:** ₹138.80K
- **Average Order Value (AOV):** ₹20.73K
- **Total Portfolio Sales (Detailed Analysis):** ₹15.11L (75 Total Orders)
- **UPI Sales Contribution:** 22%

---

## ⚙️ Features & Architecture
- **Data Modeling:** Star Schema design connecting sales facts with calendar, category, and regional dimensions.
- **Advanced DAX & Time Intelligence:** Implemented time series measures (`TOTALYTD`, `PREVIOUSMONTH`, `DIVIDE`) for YoY/MoM analysis.
- **Drill-Through & Drill-Down:** Configured `Category` → `Sub-category` hierarchies and cross-page drill-through to the Detailed Analysis page.
- **Custom Page Tooltips:** Dynamic sub-category breakdown on hover (*Laptops, Smartphones, Furniture*).
- **Static & Dynamic RLS:** Integrated Role-Based Security (*Delhi Manager*, *Mumbai Manager*) and Dynamic RLS via `UserMapping` table and `USERPRINCIPALNAME()`.
- **Interactive Navigation:** Integrated bookmarks for custom views (*Mumbai View*, *Reset*, *Back Navigation*).

---

## 🛠️ Tools & Technologies Used
- **Power BI Desktop & Power BI Service**
- **Power Query (ETL Processing)**
- **DAX (Data Analysis Expressions)**
- **SQL / Excel Data Sources**
