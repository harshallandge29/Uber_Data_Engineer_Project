End-to-End Uber Data Engineering Streaming Project (Azure + Spark + EventHub + Databricks)

The project demonstrates how to design and implement a modern real-time + batch data pipeline following industry best practices including metadata-driven pipelines, streaming ingestion, Slowly Changing Dimensions, and Star Schema modeling.
The pipeline simulates event generation from a web application, streams data through Event Hub, processes it using PySpark Structured Streaming in Databricks, and loads it into a STAR Schema data warehouse for analytics.

The goal of this project is to showcase real-world data engineering skills including:

Streaming ingestion,
Cloud data pipelines,
Metadata-driven processing,
Slowly Changing Dimensions (SCD),
Data warehouse modeling,
End-to-end architecture design.


A modern Lakehouse + Streaming architecture:

1.Web Application → Event Hub, 
Events are generated from a WebApp ,
Sent to Azure Event Hub for real-time streaming ingestion ,

2.Event Hub → Azure Data Factory / Data Lake , 
Azure Data Factory orchestrates ingestion pipelines ,
Raw data stored in Azure Data Lake ,

3.Databricks + PySpark Structured Streaming ,
Streaming data processed using Spark Structured Streaming ,
Metadata-driven pipelines for scalable ingestion ,
Transformation logic implemented using PySpark ,

4.Delta / Lakehouse Processing ,
Bronze → Silver → Gold pattern ,
Slowly Changing Dimensions (SCD) ,
Incremental streaming loads ,

5.Star Schema Data Model ,
Fact and Dimension tables created ,
Optimized for analytics & reporting ,
