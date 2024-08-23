# tokyo-olympic-data

Project Outcomes:  

Understanding the 2021 Olympics dataset  
Creating Azure Resource Group  
Creating Azure Storage account  
Creating a container in Azure Storage  
Uploading data files in Azure Storage Container  
Create a pipeline to ingest data from Azure storage into SQL pool tables   
Understanding the concept of Azure Synapse Analytics  
Creating a Azure Synapse workspace  
Creating a SQL pool in Azure Synapse workspace  
Creating tables in SQL pool  

In this project, I utilized my GitHub repository as the data source. I began by creating an Azure Resource Group and then set up a data pipeline for data ingestion. The raw data, originally in a delimited format accessible via an HTTP network, was ingested into Azure Data Lake Storage Gen2, stored within containers. This data was subsequently read on the Databricks platform using client credentials, including the client key and secret key. Utilizing Apache Spark on Databricks, I transformed the data to extract valuable insights. After the transformation, the data was written back to the storage account. For further analysis, the transformed data was imported as tables into Azure Synapse Analytics, where SQL queries were executed. The insights gained were visualized using the charting features of Synapse Analytics.
