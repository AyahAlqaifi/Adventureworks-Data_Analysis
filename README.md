Data Analysis for AdventureWorks2022
Introduction
This repository contains a series of Python scripts designed to perform various data analyses on the AdventureWorks2022 database. Using the pandas and pyodbc libraries, these scripts extract and analyze data from the AdventureWorks database to provide insights into various aspects of the business. Each analysis is focused on a specific area, such as customer purchasing behavior, inventory management, and sales performance.

Analysis Questions
1. Customer Purchasing Behaviour Analysis
This analysis examines the Sales.SalesOrderHeader table to:

Calculate the total number of orders placed by each customer.
Determine the total monetary value of purchases made by each customer.
Identify the top 5 customers with the highest monetary value of purchases.
Calculate the average monetary value of purchases per order.
2. Inventory Safety Stock Level Analysis
This analysis looks into the Production.Product table to:

Identify the top 10 products with the highest safety stock levels.
Determine the total safety stock level for all products.
Calculate the average safety stock level across all products.
3. Sales Territory Analysis
This analysis focuses on the Sales.SalesTerritory table to:

Identify the top 5 territories with the highest year-to-date (YTD) sales.
Determine the total sales across all territories.
Calculate the average sales per territory.
4. Employee Sales Performance Analysis
This analysis utilizes the Sales.SalesOrderHeader table to:

Calculate the total number of sales orders processed by each salesperson.
Identify the top 5 salespersons with the highest number of sales orders processed.
Determine the average number of sales orders processed per salesperson.
5. Customer Demographics Analysis
This analysis investigates the Sales.Customer table to:

Determine the total number of customers.
Identify the number of individual customers (where PersonID is not NULL) and store customers (where StoreID is not NULL).
Calculate the percentage of individual customers and store customers.