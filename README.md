

Student Name: Haniya Tamboli
Student ID:bitsom_ba_25071223
Email:haniyatamboli08@gmail.com 
Date:26-12-2025  

Project Overview

This project is based on designing a complete data architecture for a retail system called FlexiMart. The project includes loading and cleaning data using an ETL pipeline, storing product data using MongoDB, and creating a data warehouse for analysis and reporting.

 Repository Structure

├── part1-database-etl/  
│   ├── etl_pipeline.py  
│   ├── schema_documentation.md  
│   ├── business_queries.sql  
│   └── data_quality_report.txt  
├── part2-nosql/  
│   ├── nosql_analysis.md  
│   ├── mongodb_operations.js  
│   └── products_catalog.json  
├── part3-datawarehouse/  
│   ├── star_schema_design.md  
│   ├── warehouse_schema.sql  
│   ├── warehouse_data.sql  
│   └── analytics_queries.sql  
└── README.md  

 Technologies Used

- Python 3.x with pandas and mysql-connector-python  
- MySQL 8.0 / PostgreSQL  
- MongoDB  

 Setup Instructions

 Database Setup

bash
-Create databases
mysql -u root -p -e "CREATE DATABASE fleximart;"
mysql -u root -p -e "CREATE DATABASE fleximart_dw;"

-Run ETL Pipeline
python part1-database-etl/etl_pipeline.py

- Run Business Queries
mysql -u root -p fleximart < part1-database-etl/business_queries.sql

-Load Data Warehouse
mysql -u root -p fleximart_dw < part3-datawarehouse/warehouse_schema.sql
mysql -u root -p fleximart_dw < part3-datawarehouse/warehouse_data.sql
mysql -u root -p fleximart_dw < part3-datawarehouse/analytics_queries.sql

Key Learnings

Through this project, I learned how real-world data is cleaned and loaded into databases using ETL concepts. I also understood the difference between relational and NoSQL databases and how data warehouses help in analytics and decision making.

Challenges Faced

Handling missing and incorrect data during the ETL process was challenging, but it was solved using proper validation and cleaning steps.

Designing the star schema required careful planning to decide fact and dimension tables correctly.