# Data Warehouse and Analytics Project

This project showcases an end-to-end data warehousing and analytics solution, covering the complete process from designing and building a data warehouse to delivering actionable business insights. Developed as a portfolio project, it demonstrates standard practices in data engineering, data modeling, and analytics.

---
## Data Architecture

The data architecture for this project is based on the **Medallion Architecture**, which organizes data into three distinct layers:

1. **Bronze Layer**: Serves as the raw data repository, storing source data in its original format. Data is ingested from CSV files into a SQL Server database without transformation.
2. **Silver Layer**: Focuses on data refinement by applying cleansing, standardization, normalization, and validation processes to improve data quality and consistency.
3. **Gold Layer**: Contains business-ready data modeled using a star schema, optimized for reporting, business intelligence, and advanced analytics.

---
## Project Overview

This project involves:

1. **Data Architecture**: Designing a scalable data warehouse using the Medallion Architecture, consisting of *Bronze*, *Silver*, and *Gold* layers.
2. **ETL Pipelines**: Building robust ETL processes to extract data from source systems, transform it into a standardized format, and load it into the data warehouse.
3. **Data Modeling**: Designing and implementing fact and dimension tables using a star schema to optimize analytical performance.
4. **Analytics & Reporting**: Developing SQL-based reports that deliver actionable business insights and support data-driven decision-making.

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

Feel free to connect with me:

[![LinkedIn](https://img.icons8.com/?size=30&id=xuvGCOXi8Wyg&format=png&color=000000)](https://www.linkedin.com/in/reehakhan/)
[![Email](https://img.icons8.com/?size=30&id=nQ4dZIRCI0nW&format=png&color=000000)](mailto:khanreeha22@gmail.com)
