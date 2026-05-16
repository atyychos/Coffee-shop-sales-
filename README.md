# Coffee Shop Sales Dashboard | End-to-End Business Analytics Project

## Project Overview
This project showcases a complete end-to-end business analytics workflow using Microsoft Excel, where raw coffee shop transactional data is cleaned, transformed, analyzed, and visualized into an interactive dashboard.

The primary objective of this project is to convert raw business data into actionable insights that support strategic decision-making related to sales performance, customer behavior, and product trends.

The dashboard enables stakeholders to explore performance across different time periods, product categories, and store locations through interactive visualizations and slicers.

---

## Business Objectives

- Analyze sales performance across hourly, daily, and monthly time dimensions
- Identify peak business hours and highest-performing days
- Evaluate revenue contribution by different product categories
- Compare sales performance across multiple store locations
- Understand customer purchasing behavior and average spending patterns

---

## Tools & Technologies Used

| Tool | Purpose |
|------|----------|
| Microsoft Excel | Data analysis & dashboard development |
| Power Query | Data cleaning & transformation |
| Pivot Tables | Data summarization |
| Pivot Charts | Data visualization |
| Excel Formulas | KPI calculations & analysis |

---

## Dataset Information

The dataset contains transactional sales records from a coffee shop business, including:

- Transaction Date
- Transaction Time
- Product Name
- Product Category
- Quantity Sold
- Unit Price
- Store Location

---

## Project Workflow

### 1️) Data Import
- Imported raw transactional sales dataset into Microsoft Excel
- Verified column consistency and dataset structure

---

### 2️) Data Cleaning (Power Query)
Performed preprocessing to ensure data quality and analytical accuracy:

- Changed incorrect data types
- Removed null and inconsistent records
- Standardized column names
- Formatted date and time fields properly
- Prepared dataset for time-series analysis

---

### 3️) Feature Engineering
Created additional analytical columns for deeper business insights:

- Hour Column → Extracted from transaction time  
- Day Name Column → Enabled weekday vs weekend analysis  
- Month Name Column → Used for monthly trend evaluation  
- Date Hierarchy → Enabled drill-down analysis  

---

### 4️) Data Modeling
- Structured a clean analytical model for efficient reporting
- Optimized data structure for smooth dashboard performance
- Prepared dataset for Pivot Tables and KPI calculations

---

## KPI Metrics Developed

| KPI | Value |
|-----|------|
| Total Sales Revenue | $698,812.33 |
| Total Footfall | 149,116 |
| Average Bill per Person | $4.69 |
| Average Orders per Person | 1.44 |

Additional calculations included:
- SUM aggregations
- COUNT analysis
- Average calculations
- Month-wise trend comparisons

---

## Dashboard Features & Visualizations

### KPI Cards
- Total Sales
- Customer Footfall
- Average Bill Value
- Average Orders

---

### Sales by Hour
- Identified peak sales hours during morning rush periods
- Analyzed hourly customer traffic trends

---

### Sales by Day
- Compared weekday and weekend performance
- Evaluated customer purchasing behavior patterns

---

### Monthly Sales Trend Analysis
- Tracked revenue growth across months
- Identified seasonal performance trends

---

### Product Category Analysis
- Analyzed revenue contribution by category
- Compared coffee, tea, bakery, and other products

---

### Top Products Analysis
- Identified best-selling items
- Highlighted high-demand beverages such as espresso and brewed tea

---

### Store Location Comparison
- Compared sales performance across different outlets
- Evaluated location-wise revenue contribution

---

### Interactive Slicers
Users can dynamically filter the dashboard using:
- Month Filter
- Product Category Filter
- Store Location Filter

---

## Key Business Insights

- Morning hours (7 AM – 10 AM) generate the highest sales volume
- Coffee and tea products dominate overall revenue contribution
- Weekday sales outperform weekends, indicating routine-driven customer behavior
- Classic beverages consistently outperform premium or niche offerings
- Lower average customer spending suggests upselling opportunities

---

## Business Recommendations

- Introduce combo offers (coffee + snacks) to increase average order value
- Run targeted marketing campaigns during morning peak hours
- Launch loyalty programs focused on weekday customers
- Promote high-margin items alongside top-selling beverages

---

## Project Deliverables

- Interactive Excel Dashboard (.xlsx)
- Dashboard Preview Images
- Business Insights Report
- Cleaned and Structured Dataset

---

## How to Use

1. Open the `.xlsx` file in Microsoft Excel
2. Use slicers and filters to explore the dashboard
3. Analyze trends by:
   - Month
   - Product Category
   - Store Location
4. Review KPIs and charts for business insights

---

## Skills Demonstrated

- Business Analytics
- Data Cleaning
- Data Transformation
- Dashboard Design
- KPI Development
- Data Visualization
- Analytical Thinking
- Business Insight Generation

---

## Dashboard Preview

![Dashboard](<img width="1786" height="847" alt="Coffee_shop Dashboard" src="https://github.com/user-attachments/assets/4b96f486-cbc2-4410-a7a1-333ebafe5c0b" />
)

---

## 📁 Repository Structure

```bash
Coffee-Shop-Sales-Dashboard/
│
├── Dataset/
├── Dashboard/
├── Images/
│   └── dashboard.png
├── Documentation/
├── Coffee_Shop_Sales_Dashboard.xlsx
└── README.md
