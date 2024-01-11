# Azure Data Engineering Project
## Overview
This project aims to extract data from SSMS, cleanse and transform it in Azure cloud and genereate analytical report in PowerBI
## Project Stages
1.	Data Ingestion
2.	ETL
a.	Bronze container- Data dump to Blob storage
b.	Silver container- Cleansed data in Blob Storage
c.	Gold container- Data transformed in Blob storage
3.	Analytics
a.	Data from gold layer is curated for analytics in Azure Synapse Analytics
b.	Daat imported to PowerBI to generate report
## Services Used:
1.	Microsoft SQL Server Management Studio (SSMS)
2.	Azure Data Lake Storage Gen2 – Storage account
3.	Azure Key vault
4.	Microsoft Entra ID (previously called Azure Active Directory)
5.	Azure Data factory (ADF)
6.	Azure Databricks
7.	Azure Synapse Analytics
8.	Microsoft Power BI
## Architecture:
![Azure-Data-Engineering-project1]( https://github.com/RoshnaKU/Azure-Data-Engineering-project1/blob/main/azure_data_eng.jpg?raw=true)
