# End-to-End Azure Data Lakehouse Pipeline

## Project Overview
Built an enterprise-level data engineering pipeline using Azure Data Factory to ingest, cleanse, and transform data from on-premises files, REST APIs, and Azure SQL Database into an Azure Data Lake Gen2 storage system.

## Tech Stack
* **Azure Services:** Data Factory (ADF), SQL Database, Storage Account (Data Lake Gen2), Logic Apps
* **Concepts:** Medallion Architecture (Bronze, Silver, Gold), High-Watermark Incremental Load, Mapping Data Flows

## Architecture Highlights
* **Multi-Source Ingestion:** Automated data extraction from on-premises systems, REST APIs, and SQL databases.
* **Incremental Loading:** Implemented SQL high-watermark logic using Lookup activities to extract only new or updated records.
* **Medallion Architecture:** Cleansed and aggregated data across Bronze, Silver, and Gold layers.
* **Automated Alerting:** Triggered Azure Logic Apps for email notifications on pipeline failure.

*Note: The ARM template provided in this repository has been cleaned of sensitive credentials. Please refer to the PDF portfolio for architectural diagrams.*
