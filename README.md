# Superstore_Sales_BI
📊 Overview

This project analyzes Yearly and Quarterly Sales Trends from the Superstore dataset using Power BI.
It provides clear insights into regional performance, quarter-over-quarter (QoQ), and year-over-year (YoY) growth — helping businesses identify hidden opportunities and performance gaps.

🧩 Objective

To go beyond annual numbers and uncover quarterly fluctuations that drive sales trends across regions.

⚙️ Steps & Approach
🔹 Data Preparation

Cleaned and modeled the Superstore dataset into a star schema

Created Date Dimension for time intelligence functions

🔹 DAX Measures

Total Sales

Order Count (Distinct)

Last Quarter Sales using PARALLELPERIOD()

Quarterly Difference = [Total_Sales] - [Last_Quarter]

Yearly vs Quarterly Comparison using SAMEPERIODLASTYEAR()

🔹 Visuals Used

Line + Column Combo Chart: To compare yearly and quarterly sales trends

Waterfall Chart: To visualize quarter-over-quarter changes

Cards & Slicers: For dynamic and interactive filtering (Region, Year, Category)

📈 Key Insights

Some regions show consistent yearly growth but unstable quarterly trends

The quarterly view reveals underperforming periods that yearly summaries can miss

Useful for sales planning, target forecasting, and performance tracking

💡 Skills Showcased

✅ Power BI
✅ DAX Time Intelligence
✅ Data Modeling
✅ Data Visualization & Storytelling
✅ Business Analysis
