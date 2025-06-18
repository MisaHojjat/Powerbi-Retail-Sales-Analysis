# Powerbi-Retail-Sales-Analysis

## Introduction

This Power BI project delivers a comprehensive retail sales report for Maven Market, focusing on key product performance metrics. It demonstrates end-to-end business intelligence capabilities, from data integration and robust data modeling to the creation of interactive dashboards providing actionable insights into sales, profit, transactions, and return rates.

## Data Source
In this project, I primarily utilized CSV files as input datasets. These included principal tables such as Customers, Products, and Transactions, along with lookup tables for Regions and Calendar (Date). These files were efficiently imported and transformed within Power BI's Power Query Editor.

While CSVs served as a practical and accessible format for this portfolio project, I am proficient in connecting Power BI to a wide array of enterprise-level data sources, including: 
- SQL Server Databases
- Cloud Services (e.g., Azure Blob Storage, Azure SQL Database, AWS S3, Google Cloud Storage): For highly scalable and flexible data lake solutions

## KPIs & Key Insights
- Product Performance:  
  - Total transactions per Product    
  - Total Profit per product     
  - calculate Profit Margin per product       
  - Calculate Return Rate per products       
- Time based performance   
  - Weekly Revenue Trending(sales)   
- Geographic Analysis      
  - Store distribution and footprint
    
## Process

- Data Connection & Transformation (Power Query): cleaning, shaping, and preparation to ensure data integrity and usability including missing data verification
- Data Modeling: established a robust star schema by connecting Transaction_Data to Customers, Products, and Stores using primary/foreign key relationships. An additional inactive relationship was created between Transaction_Data and Calendar on stock_date for advanced analysis. Return_Data was integrated with Products, Calendar, and Stores via their respective keys. Furthermore, Stores was connected to Regions to form a snowflake extension for geographical analysis
- DAX (Data Analysis Expressions): calculated columns using DAX to derive key performance indicators (KPIs) such as Total Sales, Sales Growth, Average Transaction Value
- Interactive Report Design: Identified trends, utilized slicer and drop down filter


## Dashboard

 ![image](https://github.com/user-attachments/assets/01b4c8ad-0469-4319-89f9-4282e55be15b)   

                    

## Data Modeling 
established a robust star schema by connecting Transaction_Data to Customers, Products, and Stores using primary/foreign key relationships. An additional inactive relationship was created between Transaction_Data and Calendar on stock_date for advanced analysis. Return_Data was integrated with Products, Calendar, and Stores via their respective keys. Furthermore, Stores was connected to Regions to form a snowflake extension for geographical analysis

![image](https://github.com/user-attachments/assets/86cd25ad-a660-4b2b-a85e-6c1a98845d13)   

