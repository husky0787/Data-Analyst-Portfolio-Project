HR Data Analytics Dashboard

Overview

This project develops an HR analytics dashboard to track key employee metrics using Power BI, Tableau, and Excel. It addresses HR's need for clear KPIs by visualizing employee count, attrition rates, and job satisfaction, enabling better workforce planning.

Features





Data Storage: PostgreSQL database (hrdata table) to store employee data.



Data Import: SQL query to import data from hrdata.csv.



Analysis: SQL queries to calculate KPIs (e.g., attrition rate: 16.12%, average age: 37).



Visualization: Dashboards in Power BI, Tableau, and Excel showing trends like department-wise attrition (R&D: 56.12%) and gender-based patterns.

Setup





Create the hrdata table in PostgreSQL using the provided SQL script.



Import data with: COPY hrdata FROM 'D:\hrdata.csv' DELIMITER ',' CSV HEADER;.



Run SQL queries to analyze data.



Open the dashboard files in Power BI, Tableau, and Excel to explore visualizations.

Tools Used





PostgreSQL for data management



Power BI, Tableau, and Excel for dashboard creation



SQL for data analysis
