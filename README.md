# azure-ecommerce-data-engineering-pipeline

Azure-based data engineering pipeline using Databricks and PySpark to process e-commerce data with Medallion architecture and visualize insights in Power BI.

Azure E-Commerce Data Engineering Pipeline

This project demonstrates an end-to-end data engineering pipeline on Azure that processes e-commerce data using the Medallion Architecture (Bronze, Silver, Gold).
The pipeline ingests raw data, transforms it using PySpark in Azure Databricks, and produces analytics-ready datasets that are visualized in Power BI dashboards.

Tech Stack

	•	Azure Data Factory – Pipeline orchestration and ingestion
  
	•	Azure Data Lake Storage Gen2 – Data storage
  
	•	Azure Databricks (PySpark) – Data processing and transformations
  
	•	Delta Lake – Reliable data storage format
  
	•	Power BI – Data visualization and dashboard creation

  Data Pipeline Flow

The pipeline processes data using the Medallion Architecture.

Bronze Layer

	•	Ingest raw e-commerce CSV data into Azure Data Lake
	•	Store raw data with minimal transformation

Silver Layer

	•	Clean and standardize datasets
	•	Handle null values
	•	Convert data types
	•	Remove duplicates

Gold Layer

	•	Create analytics-ready tables such as:
	•	Monthly revenue
	•	Order metrics
	•	Product category performance
