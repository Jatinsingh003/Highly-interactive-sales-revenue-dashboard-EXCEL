# 📊 Interactive Sales & Revenue Dashboard — Excel

### Business Intelligence & Data Analytics Portfolio Project

An interactive **Sales & Revenue Dashboard built in Microsoft Excel** to transform 10,000+ realistic sales transactions into actionable business insights.

---

## 🎯 Project Overview

The objective of this project was to build a **decision-support dashboard**, rather than a static Excel report.

The solution uses **Power Query, Pivot Tables, KPIs, interactive filters and data visualization** to analyze sales performance, profitability, customers, products, salespeople and operational metrics.

The dashboard is divided into two analytical views:

- **Executive Overview** — high-level business performance
- **Detailed Analysis** — deeper investigation into customers, products, salespeople and operations

---

## 💼 Business Questions

The dashboard helps answer questions such as:

- How are revenue and profit performing?
- Are sales targets being achieved?
- Which regions and categories generate the most profit?
- Which products are driving sales?
- Which salespeople perform best?
- Which customers contribute the most profit?
- How are sales changing over time?
- What percentage of orders are completed, returned or cancelled?
- Which payment and shipping methods are most commonly used?
- Where are the major opportunities and areas requiring attention?

---

## 🛠️ Tools & Techniques

| Tool / Technique | Application |
|---|---|
| **Microsoft Excel** | Dashboard development and analysis |
| **Power Query** | Data cleaning, transformation and ETL |
| **Excel Tables** | Structured data management |
| **Pivot Tables** | Business data aggregation |
| **Pivot Charts** | Interactive visualization |
| **Excel Formulas** | KPI calculations and analytical logic |
| **Slicers & Filters** | Interactive analysis |
| **Data Visualization** | Performance reporting |
| **Dashboard Design** | Executive reporting and decision support |

---

## 🔄 Data Workflow

```text
Raw Data
   ↓
Power Query
   ↓
Data Cleaning & Transformation
   ↓
Clean Dataset
   ↓
Pivot Tables & KPI Calculations
   ↓
Pivot Charts
   ↓
Interactive Dashboard
   ↓
Business Insights
The Power Query layer creates a repeatable ETL workflow so that the analytical dataset can be refreshed when the source data changes.

📊 Dataset

The project uses a realistic 10,000+ row sales dataset containing multiple business dimensions.

Main fields include:
Order ID & Order Date
Customer ID & Customer Name
Customer Segment
Region, State & City
Salesperson
Product Category & Sub-Category
Product Name
Quantity
Unit Price
Discount
Revenue
Cost
Profit
Profit Margin
Sales Target
Target Achievement
Payment Mode
Shipping Mode
Order Status

The dataset contains realistic variations across products, customers, regions, salespeople and order outcomes to simulate a business sales environment.

📈 Executive Overview
Screenshots/Executive_Overview.png

The Executive Overview is designed to provide a quick understanding of overall business performance.

Key KPIs
💰 Total Revenue
💵 Total Profit
📈 Profit Margin
🛒 Total Orders
👥 Unique Customers
🎯 Target Achievement
Analysis includes
Monthly performance trends
Yearly performance
Regional performance
Category profitability
Customer segmentation
Key Business Insights
🔎 Detailed Analysis

The Detailed Analysis dashboard allows users to investigate the underlying drivers of business performance.

Analysis includes
Top profitable customers
Salesperson performance
Bestselling products
Category performance
Order status
Payment methods
Shipping methods
Customer segments
Product performance
🎛️ Interactive Features

Users can dynamically filter the dashboard by dimensions such as:

Year
Month
Region
Customer Segment
Product Category
Salesperson

The dashboard updates its KPIs, charts and analysis according to the selected filters.

A Clear All Filters function allows users to quickly return to the overall view.

💡 Business Insights

The dashboard is designed to go beyond displaying numbers by highlighting meaningful business patterns.

Examples include:

Leading revenue and profit categories
High-performing regions
Product and customer concentration
Salesperson performance
Target achievement gaps
Return and cancellation levels
Payment preferences
Shipping patterns

The overall analytical approach follows:

Raw Data
   ↓
Analysis
   ↓
Insight
   ↓
Business Decision
📐 Key Metrics
Total Revenue
SUM(Revenue)
Total Profit
SUM(Profit)
Profit Margin
Total Profit / Total Revenue
Average Order Value
Total Revenue / Total Orders
Target Achievement
Total Revenue / Total Sales Target
Return Rate
Returned Orders / Total Orders
Cancellation Rate
Cancelled Orders / Total Orders

Aggregate percentages are calculated from their underlying totals rather than simply averaging row-level percentages to avoid misleading results.

🖥️ Dashboard Preview
Screenshots/Dashboard_Preview.png

Detailed Analysis

📁 Repository Structure
interactive-sales-revenue-dashboard-excel/
│
├── README.md
│
├── Dashboard/
│   └── Interactive_Sales_Revenue_Dashboard.xlsx
│
├── Screenshots/
│   ├── Dashboard_Full_Preview.png
│   ├── Executive_Overview.png
│   └── Detailed_Analysis.png
│
├── Documentation/
│   ├── Data_Dictionary.xlsx
│   ├── Project_Insights.pdf
│   └── Dashboard_User_Guide.pdf
│
└── Data/
    └── Sales_Dataset.xlsx
🎓 Skills Demonstrated

Excel • Power Query • ETL • Data Cleaning • Data Validation • Pivot Tables • Pivot Charts • KPI Development • Data Visualization • Business Intelligence • Dashboard Design • Business Analysis

🚀 Future Improvements

Potential future enhancements include:

Year-over-Year and Month-over-Month analysis
Sales forecasting
Anomaly detection
Advanced customer segmentation
SQL-based data pipeline
Power BI implementation
Python-based advanced analytics
📌 Project Information

Project: Interactive Sales & Revenue Dashboard
Domain: Sales Analytics & Business Intelligence
Primary Tool: Microsoft Excel
Data Volume: 10,000+ transactions
Project Type: Data Analytics Portfolio Project

⭐ Project 2 of my Data Analytics Portfolio

Building practical analytics projects focused on transforming raw data into clear, actionable business insights.
