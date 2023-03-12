# ETL Pipeline using MS Azure

## Project Description

The project is to add a dataset of [Football World Cup 2022 Data](https://fbref.com/en/comps/1/stats/World-Cup-Stats) from FBRef website and process it through ETL pipeline in Azure. For this purpose, I’ve first scraped the data from the internet. It has two tables. First table is obtained using a Python Script (**script.py**) and the second is obtained using Copy Data module of Azure that uses a Web Page scraper.

The data is ingested using Azure Data Factory into SQL database in Azure. Before ingesting data, transformations are done on data using dataflow. The data is seperated into 4 different tables.


## The Azure resources used:

1. Linked Services
2. Azure Data Factory
3. Azure SQL Databases
4. Azure Blob Storage 










