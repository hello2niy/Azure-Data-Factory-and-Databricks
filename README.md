# Azure-Data-Factory-and-Databricks
End-to-End Project 

This project aims to implement Analytics/Insights on the trip transaction and ride-based
source data from SQL Server, utilizing a combination of Azure Data Factory (ADF),
Azure Blob Storage (ADLS Gen2), and Azure Databricks, in accordance with a
Medallion Architecture approach. The project entails data ingestion into a Bronze Zone,
data transformation through Azure Databricks, and data loading into Delta tables for the
Gold Zone. Moreover, we plan to create a pipeline and schedule it using Azure Data
Factory and leverage Logic Apps for pipeline resiliency in order to trigger emails.

**Tech Stack**
➔
Language: Python, SQL, Spark
➔
Package: PySpark
➔
Services: Azure Data Factory (ADF), Azure Blob Storage (ADLS Gen2), and Azure
Databricks, Logic Apps, Azure SQL Database

**Azure Data Factory (ADF)**
Azure Data Factory is a cloud-based data integration service provided by Microsoft as
part of its Azure cloud computing platform. It allows organizations to create, schedule,
and orchestrate data workflows to ingest, prepare, transform, and move data from
various sources to various destinations. Azure Data Factory supports a wide range of
data sources and destinations, including relational databases, big data platforms, cloud
storage, and other data services.

**Azure Databricks**
Azure Databricks is a cloud-based big data and analytics service provided by Microsoft,
which is powered by Apache Spark, an open-source big data processing framework. It
provides a collaborative workspace for data scientists, data engineers, and analysts to
process, analyze, and visualize large datasets using Spark's distributed computing
capabilities.

**Logic Apps**
Azure Logic Apps is a cloud-based service provided by Microsoft that allows users to
create and run workflows to automate business processes and integrate with various
systems and services. Logic Apps provides a visual designer and a wide range of
connectors to enable organizations to create workflows without writing any code,
making it accessible to both technical and non-technical users.
