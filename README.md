# olympic-azure-data-engineering-project

Overview:
This project uses Azure services to ingest, process, and store data from Kaggle. The raw data is obtained from Kaggle, ingested into the project using Git, and processed using Azure Data Factory and Databricks. The cleaned and transformed data is then stored in Azure Data Lake Gen2.Used pyspark for cleaning and transformations.

Prerequisites:
Azure Account
Git
Azure Data Factory
Databricks

Pipeline Overview:
Ingestion: Raw data is obtained from Kaggle and ingested into the project using Git.
Data Factory: Azure Data Factory is used to build a simple pipeline for data processing.
Storage: Raw data is stored in Azure Data Lake Gen2.
Databricks: Data is cleaned and transformed using Databricks.
Storage (Transformed Data): Cleaned and transformed data is stored in Azure Data Lake Gen2.
