 Part 2 – NoSQL (MongoDB)

 Overview

This part of the project demonstrates how NoSQL databases can be used to store and manage flexible data structures. MongoDB is used to store product-related data in JSON format.

 Why MongoDB?

MongoDB is suitable for this use case because:
- It supports schema-less data
- It works well with JSON documents
- It is flexible and scalable for large datasets

 Data Model

Product data is stored as documents, where each document represents a product along with its attributes such as:
- Product ID
- Name
- Category
- Price
- Stock details

 Files in This Folder

- `products_catalog.json` – JSON file containing product data  
- `mongodb_operations.js` – MongoDB commands for insert, update, and query operations  
- `nosql_analysis.md` – Explanation and comparison of NoSQL vs relational databases  

 Operations Performed

- Insert product documents into MongoDB
- Query products based on category and price
- Update product information
- Analyze advantages of NoSQL for this use case

 Outcome

This part shows how MongoDB can efficiently handle product data and how it differs from relational database storage.
