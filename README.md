# Data Warehouse and Analytics Project
 
This project demonstrates a comprehensive data warehousing and analytics solution, from building a data warehouse to generating actionable insights. Designed as a portfolio project, it highlights industry best practices in data engineering and analytics.

---
## Data Architecture

The data architecture for this project follows Medallion Architecture **Bronze**, **Silver**, and **Gold** layers:

1. **Bronze Layer**: Stores raw data as-is from the source systems. Data is ingested from CSV Files into SQL Server Database.
2. **Silver Layer**: This layer includes data cleansing, standardization, and normalization processes to prepare data for analysis.
3. **Gold Layer**: Houses business-ready data modeled into a star schema required for reporting and analytics.

---
## Project Overview

This project involves:

1. **Data Architecture**: Designing a Modern Data Warehouse Using Medallion Architecture **Bronze**, **Silver**, and **Gold** layers. 
2. **ETL Pipelines**: Extracting, transforming, and loading data from source systems into the warehouse. 
3. **Data Modeling**: Developing fact and dimension tables optimized for analytical queries. 
4. **Analytics & Reporting**: Creating SQL-based reports and dashboards for actionable insights.

---
## Repository Structure
```
data-warehouse-project/
│
├── datasets/                           # Raw datasets used for the project (ERP and CRM data)
│
├── scripts/                            # SQL scripts for ETL and transformations
│   ├── bronze/                         # Scripts for extracting and loading raw data
│   ├── silver/                         # Scripts for cleaning and transforming data
│   ├── gold/                           # Scripts for creating analytical models
│
├── tests/                              # Test scripts and quality files
│
├── analytics/                          # Scripts for Exploratory Data Analysis and advanced analytics
│
├── data_catalog.md                     # Catalog of datasets, including field descriptions and metadata
├── README.md                           # Project overview and instructions
├── LICENSE                             # License information for the repository
```
---

## About Me

Hiya! I'm **Reeha Khan**, a data scientist with 2.5 years of professional experience. I spent 1 year working at a Think Tank on data-driven narratives for the Government of Pakistan and 1.5 years researching AI in healthcare with 2 publications. I'm passionate about all things data, and you'll find me learning new skills!! :)

Let's stay in touch! Feel free to connect with me:

[![LinkedIn](https://img.icons8.com/?size=30&id=xuvGCOXi8Wyg&format=png&color=000000)](https://www.linkedin.com/in/reehakhan/)
[![Email](https://img.icons8.com/?size=30&id=nQ4dZIRCI0nW&format=png&color=000000)](mailto:khanreeha22@gmail.com)
