# Customer_behaviour_analysis
This project analyzes customer shopping behavior using python, sql and power BI.

[Project Title:Customer Shopping Behavior Analysis]
📌 Overview
This project demonstrates an end-to-end data analytics workflow designed to transform raw data into actionable business intelligence. The process covers the entire data lifecycle: from initial data ingestion and cleaning in Python, to complex relational querying in SQL, and finally to interactive visualization in Power BI and stakeholder presentation via Gamma.


📊 Dataset
•	Source: Internal Company Data
•	Description: The dataset contains 3900 records of retail transactions, including key variables such as Purchase Amount, Category, Customer Demographics, and Payment Methods.
•	Objective: To identify key drivers of sales growth/customer retention and provide data-backed recommendations.


🛠️ Tools & Technologies
•	Programming: Python (Pandas, NumPy,)
•	Database: SQL (PostgreSQL Server)
•	Visualization: Power BI
•	Documentation & Presentation: Microsoft Word (Report), Gamma AI (PPT)


🚀 Execution Steps
1. Data Processing & EDA (Python)
•	Ingestion: Loaded raw CSV/Excel data into a Python environment.
•	Cleaning: Addressed missing values, removed duplicates, and standardized data types for consistency.
•	EDA: Performed exploratory analysis to identify distributions, correlations, and outliers using heatmaps and histograms.
2. Database Management (SQL)
•	Migrated the cleaned dataset into a PostgreSQL Server.
•	Developed SQL scripts to perform advanced data aggregation, including:
o	Calculating Month-over-Month (MoM) growth.
o	Segmenting customers based on spending patterns.
o	Joining tables to create a consolidated "Master View" for reporting.
3. Business Intelligence (Power BI)
•	Connected Power BI to the PostgreSQL database for real-time data refreshing.
•	Designed a multi-page interactive dashboard focusing on:
o	Executive Summary: High-level KPIs (Total Revenue, Margin).
o	Trend Analysis: Seasonal patterns and forecasting.
o	Demographic Deep-dive: Performance across different customer segments.
4. Stakeholder Communication (Gamma & Reporting)
•	Drafted a detailed analytical report summarizing the methodology and findings.
•	Leveraged Gamma AI to generate a professional, visually engaging presentation to communicate insights to non-technical stakeholders efficiently.


💡 Key Results & Insights
•	Trend: Identified a 50% spike in sales during December, driven primarily in clothing.
•	Efficiency: Automated the data cleaning process, reducing manual reporting time by 5 hours.


🛠️ How to Run
1.	Python: Clone the repo and run analysis_script.ipynb to see the cleaning and EDA process.
2.	SQL: Use the provided .sql files in the /scripts folder to set up the database schema and views in PostgreSQL.
3.	Power BI: Open the .pbix file (ensure you update the data source settings to point to your local/server database).
4.	Presentation: View the Final_Presentation.pdf or access the Gamma link in the /docs folder.
________________________________________
Author: Riyazuddin
LinkedIn: https://www.linkedin.com/in/riyazuddin-saifi-b734b2251/
