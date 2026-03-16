End-to-End Data Engineering Streaming Project (Azure + Spark + EventHub + Databricks)

This project demonstrates a complete end-to-end real-time data engineering pipeline built using Azure services, Apache Spark, and modern data warehouse modeling techniques.
The pipeline simulates event generation from a web application, streams data through Event Hub, processes it using PySpark Structured Streaming in Databricks, and loads it into a STAR Schema data warehouse for analytics.

The goal of this project is to showcase real-world data engineering skills including:

Streaming ingestion

Cloud data pipelines

Metadata-driven processing

Slowly Changing Dimensions (SCD)

Data warehouse modeling

End-to-end architecture design

 Architecture

Pipeline flow:

WebApp → EventHub → Data Factory → Data Lake → Databricks (Spark Streaming) → Delta Tables → Star Schema

Main components used:

Web Application (event generator)

Azure Event Hub (stream ingestion)

Azure Data Factory (orchestration)

Azure Data Lake Storage

Azure Databricks

PySpark Structured Streaming

Delta Lake

Star Schema Data Warehouse
