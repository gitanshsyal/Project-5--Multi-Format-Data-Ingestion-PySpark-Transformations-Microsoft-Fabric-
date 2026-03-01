# Project-5--Multi-Format-Data-Ingestion-PySpark-Transformations-Microsoft-Fabric-
In this project, I worked on ingesting multiple file formats from Azure Data Lake Gen2 into a Lakehouse and performed data processing using PySpark notebooks.  The goal was to handle CSV and Excel data seamlessly, standardize it, and apply transformations for analytics readiness.

## Tech Stack
Microsoft Azure
Azure Data Lake Storage Gen2
Microsoft Fabric
PySpark
Lakehouse Architecture

## Implementation Steps
1️.Data Ingestion

Used Copy Data activity to ingest:
CSV files from Azure Gen2 → Lakehouse
Excel files from Azure Gen2 → Lakehouse
Ensured schema consistency and smooth ingestion across file formats

2. Data Processing (PySpark Notebook)

Performed multiple transformations using PySpark, including:
Schema validation and standardization
Data cleaning and formatting
Column-level transformations

Handling nulls and data inconsistencies

Preparing curated datasets for downstream analytics
