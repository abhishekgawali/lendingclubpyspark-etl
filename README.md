
# Lending Club PySpark ETL Pipeline

## Overview
This project implements an end-to-end PySpark-based ETL pipeline
for processing Lending Club loan data. The pipeline transforms raw,
high-volume loan data into clean, analytics-ready datasets that can
be used for credit risk analysis and reporting.

## Dataset
- Source: Lending Club public dataset
- Size: ~2.2M records, 118 columns
- Format: CSV

## Project Structure
lendingclub-pyspark-etl/
├── notebooks/
│ ├── 01_project_overview.ipynb
│ ├── 02_customers_data_cleaning.ipynb
│ ├── 03_loans_data_cleaning.ipynb
│ ├── 04_loan_repayments_cleaning.ipynb
│ └── 05_loan_defaulters_cleaning.ipynb
├── data_dictionary/
│ └── lending_club_data_dictionary.csv
└── README.md

## Key Transformations
- Schema enforcement
- Null and missing value handling
- Deduplication
- Data type casting
- Hash-based unique customer ID generation
- Business-rule driven data corrections

## Technologies Used
- Apache Spark (PySpark)
- Spark SQL
- Jupyter Notebooks