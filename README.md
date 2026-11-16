# Internet Sales Performance & Analytics Dashboard

A Business Intelligence solution developed with Microsoft Power BI analyzing retail sales, customer demographics, and product performance using a Star Schema data model.

---

## Overview
This project provides operational and financial visibility into retail internet sales data, focusing on:
- Tracking core KPIs: Revenue, order volume, customer counts, and profit margins.
- Identifying key drivers of profitability across geographic sales territories.
- Segmenting customers and evaluating product category contributions.
- Providing root-cause analysis through decomposition tree visuals.

---

## Data Model & Architecture
The data model is structured using a Star Schema design:
- Fact Table: `fact_InternetSales` (transaction details, order quantities, sales amounts, product/customer keys).
- Dimension Tables: `dim_Customer`, `dim_Product`, `dim_SalesTeritory`, `dim_Currency`, `Calender`.
- Measures: Centralized DAX measures for time-intelligence calculations (YoY, MoM) and dynamic aggregations.

---

## Report Structure
- Main Navigation: Landing page directing users to report sections.
- Executive KPI Overview: Summary cards, line charts tracking sales trends, and territory/category slicers.
- Diagnostics & Root-Cause: Decomposition tree analysis breaking down revenue drivers, custom KPI status cards, and category segmentation.
- Performance Deep-Dive: Comparative regional performance and product line breakdown.

---

## Tech Stack
- Microsoft Power BI Desktop
- DAX (Data Analysis Expressions)
- Star Schema Data Modeling
- Power Query (ETL)

---

## Usage Instructions
1. Install Microsoft Power BI Desktop.
2. Clone or download this repository.
3. Open `Final_Project.pbix` in Power BI Desktop to inspect the model and interact with the report.
