🌐 Project Title: New York City Taxi Data Azure End-To-End Data Engineering Project
🔧 Azure Services Used:

	• Azure Data Factory
	• Azure SQL Database
	• Azure Data Lake Storage Gen2
	• Azure Synapse Analytics
 
In this project, I have used Azure Data Factory (ADF) to ingest data from Azure SQL Database into Azure Data Lake Storage Gen2 (ADLS Gen2). Once the data is landed in the lake, transform it via mapping data flows, data factory's native transformation service, and sink it into Azure Synapse Analytics.

Flow of Execution:
Create Azure SQL DB, ADLS Gen2, Azure Synapse Analytics and Azure Data Factory services in Azure Portal.
Create linked services in ADF to each above azure service mentioned.
In ADF, ingest data using the copy activity and 
Transform data using mapping data flow activity
Finally sink data into Azure Synapse Analytics
