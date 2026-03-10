# Formula1 Databricks Data Engineering Project

## Overview
This project demonstrates a real-world data engineering pipeline built using Azure Databricks and PySpark to analyze Formula 1 racing data. The pipeline processes raw racing datasets, performs transformations using Spark and SQL, and stores curated data in Delta Lake tables for analytics and reporting.

## Technologies Used
- Azure Databricks
- PySpark
- Apache Spark
- Spark SQL
- Delta Lake
- Unity Catalog
- Azure Data Factory

## Project Architecture
The project follows the Medallion Architecture:

- Bronze Layer – Raw data ingestion
- Silver Layer – Data cleaning and transformation
- Gold Layer – Aggregated data for analytics

## Key Features
- Built scalable ETL pipelines using PySpark
- Implemented Delta Lake for ACID transactions
- Processed and transformed large racing datasets
- Created curated analytical tables
- Managed data governance using Unity Catalog
- Orchestrated workflows using Azure Data Factory

## Dataset
The dataset contains historical Formula 1 racing information including:
- Drivers
- Constructors
- Race results
- Lap times
- Circuits
- Seasons

## Outcome
The final dataset enables analysis of driver performance, constructor standings, race results, and season statistics.
