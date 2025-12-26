 Part 1 – Database ETL

Overview

This part of the project focuses on building an ETL (Extract, Transform, Load) pipeline for the FlexiMart retail dataset. The raw data is taken from CSV files, cleaned, validated, and then loaded into a relational database.

 Data Sources

The ETL pipeline uses the following raw input files:
- customers_raw.csv
- products_raw.csv
- sales_raw.csv

These files contain basic customer details, product information, and sales transactions.

ETL Process

1. Extract
   - Data is read from CSV files using Python and pandas.

2. Transform
   - Missing values are handled.
   - Duplicate records are removed.
   - Data types are corrected.
   - Basic validation checks are performed.

3. Load
   - Cleaned data is inserted into relational database tables.

 Files in This Folder

- `etl_pipeline.py` – Python script that performs the ETL process  
- `schema_documentation.md` – Database table structure and design  
- `business_queries.sql` – SQL queries to answer business-related questions  
- `data_quality_report.txt` – Report generated after ETL showing data issues  

Outcome

At the end of this part, all cleaned and validated data is available in the database and ready for querying and further analysis.
