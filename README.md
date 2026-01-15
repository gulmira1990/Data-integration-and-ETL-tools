# Data-integration-and-ETL-tools
End-to-end ETL process using SSIS
# SSIS ETL Project

## Overview
This project implements an end-to-end ETL process using SQL Server Integration Services (SSIS).

## Data Sources
- CSV file: transactions.csv
- Excel file: customers.xlsx
- SQL Server table: Products

## ETL Steps
1. Extract data from CSV, Excel, and SQL Server
2. Clean data (TRIM, UPPERCASE)
3. Remove duplicates using Sort
4. Validate ProductID using Lookup
5. Filter invalid records
6. Calculate TotalCost using Derived Column
7. Load data into SQL Server table ProcessedTransactions

## Technologies Used
- SQL Server Integration Services (SSIS)
- SQL Server Management Studio (SSMS)
- Visual Studio

## How to Run
1. Open the project in Visual Studio
2. Configure SQL Server connection
3. Run the SSIS package

## Results
Screenshots showing successful execution and SQL query results are included.
