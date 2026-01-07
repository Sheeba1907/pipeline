This repository contains a reference architecture diagram implementing end-to-end data ingestion, processing, and serving.  
Incremental data is ingested using Azure Data Factory from Azure SQL database, stored in Azure DataLake Storage Gen2.
Raw data from ADLS is transformed using Azure Databricks across Bronze, Silver, and Gold layers, and served for analytics.  
