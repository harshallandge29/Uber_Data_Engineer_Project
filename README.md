End-to-End Uber Data Engineering Project (Azure + Databricks + Streaming)

This repository contains a complete End-to-End Data Engineering Project built using Azure Data Engineering services, Databricks, PySpark, and Structured Streaming.
The project demonstrates how to design and implement a modern real-time + batch data pipeline following industry best practices including metadata-driven pipelines, streaming ingestion, Slowly Changing Dimensions, and Star Schema modeling.

The architecture simulates a real production-grade data platform where events are generated from a web application, ingested through Event Streaming, processed using Spark, and loaded into a dimensional data warehouse.

The project follows a modern Lakehouse + Streaming architecture:

1.Web Application → Event Hub ,
Events are generated from a WebApp ,
Sent to Azure Event Hub for real-time streaming ingestion.

2.Event Hub → Azure Data Factory / Data Lake ,
Azure Data Factory orchestrates ingestion pipelines ,
Raw data stored in Azure Data Lake.

3.Databricks + PySpark Structured Streaming ,
Streaming data processed using Spark Structured Streaming ,
Metadata-driven pipelines for scalable ingestion ,
Transformation logic implemented using PySpark .

4.Delta / Lakehouse Processing ,
Bronze → Silver → Gold pattern ,
Slowly Changing Dimensions (SCD) ,
Incremental streaming loads .

5.Star Schema Data Model ,
Fact and Dimension tables created ,
Optimized for analytics & reporting .








