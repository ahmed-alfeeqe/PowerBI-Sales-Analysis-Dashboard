# 📊 Internet Sales Performance & Analytics Dashboard (Power BI)

An end-to-end Business Intelligence solution built with **Microsoft Power BI** analyzing retail internet sales, customer behavior, and product performance using a structured Star Schema data warehouse architecture.

---

## 🎯 Executive Summary & Objectives
The goal of this project is to deliver actionable business insights for retail decision-makers by:
- Monitoring high-level KPIs across sales revenue, order volumes, and customer growth.
- Uncovering key drivers of profitability and sales across geographic territories.
- Segmenting customers and identifying top-performing product categories.
- Providing intuitive root-cause analysis through interactive decomposition trees.

---

## 🏗️ Data Architecture & Star Schema Modeling
The data model is engineered using Star Schema best practices to ensure optimal query performance and scalable DAX computations:

- **Fact Table:**
  - `fact_InternetSales`: Detailed transaction records containing sales amount, order quantities, product keys, customer keys, and dates.
- **Dimension Tables:**
  - `dim_Customer`: Customer demographics, geography, and purchasing profiles.
  - `dim_Product`: Product hierarchies, categories, sub-categories, and unit costs.
  - `dim_SalesTeritory`: Regional sales territories, countries, and groups.
  - `dim_Currency`: Multi-currency exchange rate conversions.
  - `Calender`: Standard continuous date table supporting time-intelligence functions (YoY, MoM, YTD).
- **Measures Table:**
  - `Measure`: Dedicated repository for optimized DAX calculations (Revenue, Profit Margin %, Order Count, Average Order Value).

---

## 🖥️ Dashboard Overview & Key Features

### 1. Main Navigation Hub
* Modern UI/UX layout with custom SVG assets and intuitive navigation buttons to seamlessly move between report sections.

### 2. Executive KPI Summary (`1st Page`)
* **KPI Metric Cards**: Real-time tracking of Total Sales, Orders, Customers, and Profitability.
* **Trend Analysis**: Line charts displaying sales performance over time with dynamic granularity (Monthly / Quarterly).
* **Interactive Slicers**: Multi-dimensional filtering by Date range, Territory, and Product Category.
* **Category Breakdown**: Horizontal bar charts highlighting revenue contribution by product line.

### 3. Root-Cause & Performance Diagnostics (`2nd Page`)
* **Decomposition Tree Visual**: AI-powered root-cause exploration breaking down sales numbers by region, category, and demographic attributes.
* **Custom KPI Indicator Cards**: Status indicators comparing actual performance against target benchmarks.
* **Customer & Product Segmentation**: Donut and pie charts illustrating distribution across market segments.

### 4. Deep-Dive Category & Regional Analysis (`3rd Page`)
* Multi-axis column & line charts showing comparative performance across regions.
* Territory drill-down capabilities for granular operational insights.

---

## 🛠️ Tools & Technologies Used
* **Business Intelligence:** Microsoft Power BI Desktop
* **Data Modeling:** Star Schema, 1-to-Many Relationships, Bidirectional cross-filtering when appropriate
* **Calculations:** Advanced DAX (Time Intelligence, Iterators, Context Transitions)
* **UI/UX Design:** Custom themes, SVG layout components, consistent color palettes

---

## 🚀 How to Run & Explore the Project
1. **Prerequisite:** Install [Power BI Desktop](https://powerbi.microsoft.com/desktop/) (free).
2. Download or clone this repository:
   ```bash
   git clone https://github.com/<your-username>/<repo-name>.git
   ```
3. Open `Final_Project.pbix` in Power BI Desktop.
4. Interact with slicers, drill through categories, and explore the interactive visuals.

---

## 👤 Author
Data Analysis & BI Portfolio Project
