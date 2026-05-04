☕ Bright Coffee Shop Sales Analysis & BI Dashboard

📌 Project Overview

##This project involves a comprehensive end-to-end data analysis of 149,116 transactional records from Bright Coffee Shop.

##The objective was to provide actionable business insights for a new CEO to drive revenue growth and operational efficiency.  

🎯 Key Objectives
*Identify high-revenue products and categories.  
*Analyze peak sales periods and customer behavior trends.  
*Provide data-driven recommendations for marketing and inventory. 
*Deliver a professional, interactive BI dashboard for executive reporting.  

🛠️ Tech StackPlanning: 

*Miro (Data Flow & Architecture).  
*Data Processing: Databricks, and SQL.  
*Database: Microsoft Excel.  
*Business Intelligence: Looker Studio. 
*Documentation: GitHub & Microsoft Excel. 

🏗️ Data Architecture & ETL Pipeline

*The project followed a structured ETL (Extract, Transform, Load) process:Extraction: Raw transactional data was sourced from Excel.
*Transformation (The "Cleaning" Phase):Time Normalization: Converted ISO timestamps (e.g., 2026-03-19T07:06:11.000Z) into a clean HH:MM:SS format for better readability.  
*Chronological Sorting: Created numeric mapping for months (month_numeric) and days (day_of_week_numeric) to override default alphabetical sorting in Looker Studio.  
*Financial Calculation: Derived Total_Revenue using the formula: $unit\_price \times transaction\_qty$. 
*Loading: The cleaned dataset was connected to Looker Studio for visualization.  

📊 Interactive Dashboard Highlights https://datastudio.google.com/s/oLtf-YIZXfY

#The Bright Coffee Project Dashboard features:

*Total Revenue Scorecard: Real-time tracking of the $698,812.33 total revenue. 
*Revenue by Category: A breakdown showing Coffee as the primary revenue driver. 
*Temporal Analysis: Visualizations of sales trends by MonthName, DayName, and Time_Classification (e.g., Rush Hour vs. Night).  *Location Performance: Comparison of revenue across store locations like Lower Manhattan, Astoria, and Hell's Kitchen.  

💡 Key Business Insights Peak Performance: 

*Sales significantly spike during morning "Rush Hour" intervals.  
*Top Products: Coffee and Tea categories dominate the sales mix, while "Packaged Coffee" shows growth potential.  
*Store Trends: The Lower Manhattan location consistently leads in total transaction volume. 

🚀 Strategic Recommendations

*Targeted Marketing: Implement loyalty programs or "Happy Hour" discounts during slow afternoon time slots to level out daily revenue.
*Inventory Optimization: Increase stock levels for top-performing "Gourmet Brewed Coffee" during weekend shifts. 
*Automation: Transition from manual Excel uploads to an automated daily reporting pipeline using the established Databricks-to-GitHub workflow.
