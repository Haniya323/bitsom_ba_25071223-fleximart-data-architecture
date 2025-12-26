 Part 3 – Data Warehouse
Overview

This part of the project focuses on designing and implementing a data warehouse for analytical purposes. A star schema is used to organize data in a way that supports fast and efficient analysis.

 Star Schema Design

The data warehouse consists of:
- One central fact table (sales facts)
- Multiple dimension tables such as customer, product, and time

This structure makes analytical queries easier and faster.

 Files in This Folder

- `star_schema_design.md` – Explanation of the star schema and table relationships  
- `warehouse_schema.sql` – SQL script to create warehouse tables  
- `warehouse_data.sql` – Script to load data into the warehouse  
- `analytics_queries.sql` – OLAP queries for business analysis  

 Analytical Queries

The queries in this part help to:
- Analyze total sales over time
- Identify top-selling products
- Understand customer purchase behavior

 Outcome

This data warehouse enables business intelligence reporting and supports decision-making by providing meaningful insights from historical data.
