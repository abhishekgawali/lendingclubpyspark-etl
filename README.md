
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
```text
lendingclub-pyspark-etl/
├── notebook/
│   ├── LendingClub_Intro.ipynb
│   ├── LendingClub_DataCleaning_S1.ipynb
│   ├── LendingClub_DataCleaning_S2.ipynb
│   ├── LendingClub_DataCleaning_S3.ipynb
│   └── LendingClub_DataCleaning_S4.ipynb
├── data-dictionary/
│   └── Lending Club Data Dictionary.csv
└── README.md
```

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
