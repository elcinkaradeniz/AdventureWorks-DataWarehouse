# AdventureWorks Data Warehouse Project

## Overview
This project demonstrates a simple Data Warehouse (DWH) implementation
using the AdventureWorks OLTP database.

The goal of this project is to understand and practice
data warehouse concepts such as fact tables, dimension tables,
star schema modeling and ETL processes.

## Architecture
- Source System (OLTP): MS SQL Server (AdventureWorks2019)
- Data Warehouse: Oracle Database
- Modeling Approach: Star Schema
- ETL Approach: SQL-based ETL simulation

## Data Model
The data warehouse is designed around a sales analysis use case.

### Fact Table
- fact_sales  
  - SalesAmount  
  - OrderQuantity  
  - DateKey  
  - ProductKey  
  - CustomerKey  

### Dimension Tables
- dim_date  
- dim_product  
- dim_customer  

## ETL Process
Data is extracted from AdventureWorks OLTP tables,
transformed using SQL (data cleaning and joining),
and loaded into the Oracle Data Warehouse.

ETL logic is implemented using SQL scripts for learning purposes.

## Technologies Used
- MS SQL Server
- Oracle Database
- SQL
- Data Warehouse Modeling
- ETL Concepts

## Status
This project is currently **in progress**.
Additional improvements such as schema diagrams
and advanced ETL logic will be added.
