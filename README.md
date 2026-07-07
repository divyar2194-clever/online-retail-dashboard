# 🛍️ Online Retail Dashboard

A 5-page interactive Power BI dashboard built on the UCI Online Retail dataset — designed to answer specific business questions from the CEO and CMO of a retail store, covering revenue trends, global demand, top markets, and customer performance.

## 📊 Project Overview

This dashboard was built around four real business questions from leadership, each mapped to a dedicated report page. The dataset covers transactional retail data for the year 2011 across multiple countries, with the United Kingdom excluded from international analysis to focus on global expansion opportunities.

## 🗂️ Dataset Columns

`InvoiceNo` | `StockCode` | `Product` | `Quantity` | `InvoiceDate` | `Price` | `Revenue` | `CustomerID` | `Country`

## 🛠️ Tools Used

- **Power BI** — Data modeling, DAX measures, interactive visuals
- **DAX** — Custom measures for revenue calculations
- **Date Table** — Custom calendar table built for 2011 with Year, Date, Month, Month Number columns

## 🧮 DAX Measures Built

- **Total Revenue** — Overall revenue across all transactions
- **Revenue Ex UK** — Revenue excluding United Kingdom (for international analysis)
- **Revenue by Country** — Revenue aggregated at country level
- **Revenue by Customer** — Revenue aggregated at customer level

## 📋 Dashboard Pages & Business Questions Answered

### Page 1 — Monthly Revenue Trend (CEO)
**Business Question:** The CEO wants to view a time series of revenue for the year 2011 to identify seasonal trends.
- **Key Finding:** Revenue peaked in November 2011 at approximately $1.0M–1.07M, showing a strong year-end seasonal surge before dropping sharply in December
- Visual: Line chart by Month showing monthly revenue movement across all of 2011

### Page 2 — Top 10 Countries by Revenue Excluding UK (CMO)
**Business Question:** The CMO wants to identify the top 10 revenue-generating countries outside the United Kingdom.
- **Key Finding:** Netherlands leads international revenue, followed by EIRE (Ireland), Germany, France, and Australia — all strong candidates for further market investment
- Visual: Horizontal bar chart ranked by Total Revenue, UK excluded

### Page 3 — Top 10 Revenue Generating Customers (CMO)
**Business Question:** The CMO wants to identify top customers by revenue to understand satisfaction and retention priorities.
- **Key Finding:** The highest revenue customer generated approximately $259K, significantly ahead of others — indicating a concentration of revenue in a small number of high-value accounts
- Visual: Bar chart of Customer ID vs Total Revenue, top 10 filtered

### Page 4 — Global Demand View (CEO)
**Business Question:** The CEO wants to understand demand across all countries (excluding UK) to identify expansion opportunities.
- **Key Finding:** Demand is heavily concentrated in Western Europe, with Australia showing notable volume — regions like Asia and South America represent untapped expansion potential
- Visual: Bubble map showing quantity by country globally, UK excluded

### Page 5 — Quantity vs Revenue by Product (CEO)
**Business Question:** Which products drive both high quantity and high revenue — and are there outliers worth investigating?
- Visual: Scatter plot of Sum of Quantity vs Total Revenue by Product, color-coded by product name

## 📁 Files in This Repository

| File | Description |
|------|-------------|
| `online retail dashboard.pbix` | Full Power BI file with data model, DAX measures, date table, and all 5 dashboard pages |

## 💡 Business Recommendation

Western Europe — particularly Netherlands, Ireland, and Germany — represents the strongest international revenue base and the most immediate expansion opportunity. The sharp November revenue peak suggests the business is highly seasonal, and planning inventory and marketing campaigns around Q4 could significantly amplify results. High customer revenue concentration in a small number of accounts also signals a need for loyalty and retention programs targeting top buyers.

---
*Project by Divya R | [GitHub](https://github.com/divyar2194-clever)*
