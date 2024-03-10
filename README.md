# End-to-End Data Engineering Project
Welcome to our data engineering end-to-end project repository! This project focuses on leveraging various Azure services to build a robust data pipeline for handling Olympic data sourced from Kaggle. Below is an overview of the project architecture and the technologies used:
## Project Overview:
This project aims to demonstrate a complete data engineering workflow, from data ingestion to analysis and visualization, using Olympic data sourced from Kaggle. The key components of the architecture include:
### Data Source:
Olympic data sourced from Kaggle serves as the primary dataset for this project.
### Data Factory: 
Azure Data Factory is utilized for data ingestion, allowing seamless extraction of data from the source and itstransformation into a format suitable for downstream processing.
### Data Lake Gen2:
Azure Data Lake Gen2 serves as the storage solution for both raw and transformed data, providing scalability and durability for large datasets.
### Azure Databricks: 
Azure Databricks is used for data transformation tasks, enabling efficient processing of data at scale using Apache Spark.
### Azure Synapse Analytics: 
Azure Synapse Analytics is employed for data analysis, providing powerful querying capabilities and integration with various BI tools.
### Power BI: 
Power BI is used for creating interactive dashboards and visualizations, allowing stakeholders to gain insights from the analyzed data.
## Usage:
To utilize this project, follow these steps:
* Clone the repository to your local machine.
* Set up Azure resources including Data Lake Gen2, Azure Databricks, Azure Synapse Analytics, and Power BI.
* Configure Azure Data Factory to ingest data from the Kaggle dataset into Data Lake Gen2.
* Use Azure Databricks for data transformation tasks, manipulating the raw data into a suitable format for analysis.
* Utilize Azure Synapse Analytics to perform data analysis and gain insights from the processed data.
* Connect Power BI to Azure Synapse Analytics to create interactive dashboards and visualizations for stakeholders.
## Contributors:
_Lakshmi Vadlamudi_
## Acknowledgments:
Special thanks to Kaggle for providing the Olympic dataset used in this project, and to the Azure team for developing the robust cloud services utilized for building this data engineering solution.
