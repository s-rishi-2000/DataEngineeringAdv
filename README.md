# DataEngineeringAdv

A lightweight data engineering sample repository built around the AdventureWorks retail dataset. The project is intended for ETL, data modeling, analytics engineering, and lakehouse-style experimentation using SQL, Python, and Databricks.

## Overview

This repository contains structured CSV files representing core business entities and sales activity for an AdventureWorks-style retail scenario. The data is suitable for:

- building staging and curated datasets
- developing ELT/ETL pipelines
- creating star/snowflake schemas
- running analytics and KPI reporting
- testing data quality checks and transformations
- experimenting with Databricks notebooks and data engineering workflows

## Repository Structure

- `Data/` – raw source files for the AdventureWorks dataset
- `DataBricksNotebooks/` – notebook-related assets or starter files for Databricks workflows
- `Dataset` – placeholder file in the root
- `README.md` – project documentation

## Included Data Files

Inside the `Data/` folder, the repository contains:

- `AdventureWorks_Calendar.csv` – calendar dimension data
- `AdventureWorks_Customers.csv` – customer master data
- `AdventureWorks_Product_Categories.csv` – product category dimension
- `AdventureWorks_Product_Subcategories.csv` – product subcategory dimension
- `AdventureWorks_Products.csv` – product catalog data
- `AdventureWorks_Returns.csv` – return records
- `AdventureWorks_Sales_2015.csv` – sales data for 2015
- `AdventureWorks_Sales_2016.csv` – sales data for 2016
- `AdventureWorks_Sales_2017.csv` – sales data for 2017
- `AdventureWorks_Territories.csv` – sales territory dimension

## Typical Use Cases

- Create a raw-to-curated ingestion pipeline
- Load files into a data lake or warehouse
- Join sales, product, customer, and territory data
- Calculate revenue, returns, customer trends, and product performance
- Build dimension and fact tables for BI dashboards

## Suggested Workflow

1. Load the CSV files into a storage layer (e.g., ADLS, S3, or DBFS).
2. Ingest them into a landing zone or bronze layer.
3. Clean and standardize columns, types, and null handling.
4. Build a curated dataset with fact and dimension tables.
5. Run business queries for reporting and analysis.

## Notes

This repository is intentionally lightweight and is designed as a practical starting point for data engineering learning and experimentation. It can be extended with notebooks, transformation scripts, orchestration pipelines, and quality validation logic.

## License

This project is provided for educational and demonstration purposes. Please review the repository owner’s licensing practices before using it in production or commercial settings.
