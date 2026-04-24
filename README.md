# 📊 Sales Data Analysis — Excel Project

## Project Overview
Cleaned and analysed a 50-row sales dataset using Microsoft Excel.
Identified key business insights across product categories, regions, cities, and delivery performance.

## Tools Used
- Microsoft Excel
- Pivot Tables & Pivot Charts
- Data Cleaning (Find & Replace, TRIM, PROPER)
- Functions: VLOOKUP, INDEX-MATCH, IF, COUNTIF, SUMIF

## Dataset
- 50 orders across 6 Indian cities
- 3 product categories: Electronics, Furniture, Stationery
- 12 columns: Order ID, Customer, Product, Category, Region, City, Sales, Quantity, Discount, Profit, Status, Month

## Data Cleaning Steps
- Fixed inconsistent text case (lowercase/UPPERCASE) in Category, Region, Status columns
- Removed leading/trailing spaces using TRIM
- Filled missing Profit values using AVERAGEIF for respective categories
- Verified cleaning using COUNTBLANK and COUNTIF checks

## Key Business Insights

### 1. Electronics Dominates Revenue
Electronics contributes ₹9,67,800 (71% of total sales) — 2.5x Furniture and 163x Stationery.
June is the peak sales month at ₹1,92,000.
**Recommendation:** Focus marketing campaigns before June and April — both are high-demand months.

### 2. Delivery Performance
76% of orders (38/50) successfully delivered.
8 Pending + 4 Cancelled orders represent revenue at risk.
Delhi and Kolkata each have 2 Pending orders — highest among all cities.
**Recommendation:** Investigate Pending orders in Delhi and Kolkata for fulfilment issues.

### 3. Laptop = Highest Profit Product
Laptop generates ₹83,500 total profit with only 2.5% average discount.
Printer and Sofa carry 15% discounts but low profit returns.
**Recommendation:** Protect Laptop's low-discount strategy. Review Printer and Sofa pricing.

## Pivot Tables Built
1. Sales & Profit by Category across Months
2. Delivery Status breakdown by City
3. Profit and Average Discount by Product
4. Total Sales by Month (trend analysis)

## Files
- `Project1.xlsx` — Cleaned dataset + all pivot tables + insights
- `screenshots/` — Images of pivot tables and key charts

---
*Project completed as part of my Data Analytics learning journey | Tools: Excel*
*Connect with me on [LinkedIn](https://linkedin.com/in/nishmapm)*
