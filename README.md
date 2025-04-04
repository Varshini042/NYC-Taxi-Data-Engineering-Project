# NYC Taxi Data Engineering Project

## 🚀 Overview
This project walks through a complete **Azure Data Engineering** workflow using **Azure Data Factory, Databricks, PySpark, and Delta Lake**. It covers **data ingestion, transformation, and management using Delta Tables** to build an efficient and scalable data pipeline.

## 🔑 Key Features
- **ETL and Data Transformation** – Ingest and process NYC Taxi data using PySpark.
- **Delta Tables for Storage** – Implement **Delta Lake** for efficient data storage and versioning.
- **Medallion Architecture** – Organize data into **Bronze, Silver, and Gold layers** for structured processing.
- **PySpark for Data Processing** – Perform transformations and analytics on large datasets.
- **Time Travel & Data Versioning** – Utilize **Delta Log** to track changes and enable historical data access.
- **Integration with Azure Data Lake** – Store raw and processed data in **Azure Data Lake Storage Gen2**.

## 🏗️ Data Architecture
The project follows the **Medallion Architecture** with structured data processing:
1. **Bronze Layer** – Raw NYC Taxi data is ingested into **Azure Data Lake**.
2. **Silver Layer** – Data is cleaned, transformed, and stored in **Delta Tables using PySpark**.
3. **Gold Layer** – Aggregated and analytics-ready data is prepared for reporting and BI tools.
4. **Delta Lake & Time Travel** – Enables data versioning, rollback, and historical analysis.
![image](https://github.com/user-attachments/assets/7db228c5-0435-46c3-8b6b-1a590fdbfd1d)


## 🛠️ Technologies Used
- **Azure Data Factory (ADF)** – Data ingestion and pipeline automation.
- **Azure Data Lake Gen2** – Cloud-based scalable storage.
- **Azure Databricks** – Compute environment for big data processing.
- **PySpark** – Data processing and transformation.
- **Delta Lake** – ACID-compliant storage for data versioning and optimization.

## 📁 Data Sources
- **NYC Taxi Data API** – Public dataset from NYC Government. https://www.nyc.gov/site/tlc/about/tlc-trip-record-data.page
- **CSV Files** – Hosted on GitHub.




