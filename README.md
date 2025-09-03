
📘 README.md
🚀 AdventureWorks Data Engineering Project

This repository contains a complete data engineering workflow built on the AdventureWorks dataset. It demonstrates skills in data ingestion, transformation, SQL development, and Databricks notebooks—with a focus on Azure Data Engineering practices.

📂 Repository Structure
├── AdventureWorks_Calendar.csv        # Calendar dimension data  
├── AdventureWorks_Customer.csv        # Customer dimension data  
├── AdventureWorks_Product.csv         # Product master data  
├── AdventureWorks_ProductCategory.csv # Product categories  
├── AdventureWorks_ProductSubcat.csv   # Product subcategories  
├── AdventureWorks_Returns.csv         # Product returns data  
├── AdventureWorks_Sales_Order.csv     # Sales orders  
├── AdventureWorks_Sales_OrderDetail.csv # Sales order details  
├── AdventureWorks_Sales_Reason.csv    # Sales reason mapping  
├── AdventureWorks_Territory.csv       # Territory mapping  
├── Create Views Gold.sql              # SQL script for Gold layer views  
├── silver_layer.dbc                   # Databricks notebook (DBC format)  
├── silver_layer_refer.ipynb           # Databricks/Spark notebook (Python)  
├── git.json / git (1).json            # Config files  
└── README.md                          # Project documentation  

🛠️ Key Features

Data Ingestion: AdventureWorks data loaded into storage for processing.

Silver Layer: Data transformations using PySpark/Databricks notebooks.

Gold Layer: Final business-ready tables created via SQL scripts (Create Views Gold.sql).

Data Modeling: Dimensional model including fact & dimension tables (Calendar, Customer, Product, Sales, etc.).

Notebooks: Code-based transformations & exploratory analysis (silver_layer.dbc, silver_layer_refer.ipynb).

🧰 Tools & Technologies

Azure Databricks – Data processing and transformation

Azure Data Lake / Storage – Data storage

SQL – Gold layer transformations & reporting

PySpark – ETL pipeline development

AdventureWorks Dataset – Sample retail dataset

📊 Workflow

Raw Layer – Import CSV files (AdventureWorks datasets).

Silver Layer – Clean & transform using Databricks notebooks.

Gold Layer – Create business views using SQL (Create Views Gold.sql).

Consumption – Data ready for reporting & dashboards (Power BI / Synapse).

🚦 How to Use

Clone the repository

git clone https://github.com/yourusername/AdventureWorks-DataEngineering.git


Import .csv files into Azure Data Lake.

Upload .dbc / .ipynb notebooks into Databricks workspace.

Run silver layer transformations.

Execute Create Views Gold.sql for gold layer tables.

📌 Future Enhancements

Add Bronze Layer raw ingestion pipeline.

Automate ETL with Azure Data Factory.

Integrate with Power BI dashboards.
