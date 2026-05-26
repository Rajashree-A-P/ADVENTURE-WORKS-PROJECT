 🚴 Adventure Works Sales Analysis | Power BI Dashboard

 📌 Overview
This Power BI project analyzes the business performance of Adventure Works, a global retail company specializing in bicycles and accessories. The dashboard transforms raw business data into interactive visual insights to support data-driven decision-making.

The project focuses on:
- Sales & Profit Analysis
- Customer Insights
- Product Performance
- Returns Analysis
- Regional Performance
- Time Intelligence Metrics

---

🎯 Project Objectives
- Analyze sales and profitability trends
- Monitor business KPIs dynamically
- Identify high-performing products and regions
- Track return patterns and operational risks
- Build interactive dashboards for business insights

---

 🛠️ Tools & Technologies
- Power BI Desktop
- Power Query
- DAX (Data Analysis Expressions)
- Data Modeling
- Excel / CSV Dataset

---


🔹 Data Transformation
- Cleaned and transformed raw data using Power Query
- Verified data types and handled null values
- Extracted SKU categories and customer domain names
- Created calendar tables and calculated fields

🔹Data Modeling
Implemented:
- Star Schema
- Snowflake Schema

Configured relationships between:
- Sales Data
- Returns Data
- Customer Lookup
- Product Lookup
- Calendar Lookup
- Territory Lookup

🔹 DAX Calculations
Created measures and calculated columns for:
- Total Sales
- Total Returns
- Return Rate
- Total Revenue
- Total Profit
- Rolling Profit
- Previous Month Comparisons
- Customer Segmentation

 🔹 Dashboard Development
Designed interactive dashboards using:
- KPI Cards
- Matrix Visuals
- Drill-down Analysis
- Hierarchies
- Filters & Slicers
- Time Intelligence Visuals

---

 📊 Dashboard Features
✔ Interactive KPI Tracking  
✔ Revenue & Profit Analysis  
✔ Bike Sales & Returns Dashboard  
✔ Country-wise Performance Analysis  
✔ Customer Demographics Insights  
✔ Rolling Revenue & Profit Analysis  
✔ Dynamic Filters & Drill-through Reports  

---

📈 Key Insights

 🌍Country-Wise Insights
# 🇺🇸 United States
- Highest profit and order volume
- Highest returns impacting profitability

# 🇦🇺 Australia
- Strong profitability with lower return rates
- Most efficient market performance

# 🇨🇦 Canada
- Lower profit margins due to higher returns

# 🇬🇧 🇩🇪 🇫🇷 Europe
- Stable performance with margin optimization opportunities

---

🚲 Sales Insights
- Mid-range bike models generated the highest revenue
- High-end products showed lower sales volume
- Strong business recovery observed in 2022
- Customer product preferences remained stable over time

---

 🔄 Returns Analysis
- Returns increased significantly after late 2021
- Accessories contributed to the highest return percentage
- Clothing recorded the lowest return percentage

Business Recommendations
- Improve product quality checks
- Analyze recurring return reasons
- Enhance customer guidance and support
- Optimize product design strategy

---
Customer Insights
- 1,000 distinct customers analyzed
- Majority of customers born between 1960–1980
- Strong middle-aged customer base with stable purchasing power

---
💰 Financial Performance
- Total Profit (2022): **$3.89M**
- Average Product Cost: **$413.66**
- Revenue showed strong rebound growth in 2022

---

📌 DAX Measures Used


Total Customers = DISTINCTCOUNT('Sales Data'[Customer Key])

TOTAL RETURNS = COUNT('Returns Data'[Quantity returned])

Return Rate = [TOTAL RETURNS] / [TOTAL SALES]

Total Profit = [Total Revenue] - [Total Cost]


