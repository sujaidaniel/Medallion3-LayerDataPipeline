# Medallion3-Layer Data Pipeline  
## Data Pipeline Based on Medallion Architecture  

![3-Layer System Architecture](https://github.com/user-attachments/assets/80f552b0-4d3b-46be-8b27-ab063bb4cb48)

### Project Overview

This project develops a data pipeline built on the Medallion Architecture, utilizing Microsoft Azure services such as Azure Data Factory, Azure Databricks, and DBT (Data Build Tool). The pipeline supports efficient data extraction, transformation, and loading (ETL), ensuring seamless data processing and analytics.

### System Architecture

The Medallion Architecture provides a robust framework for building scalable, reliable, and maintainable data pipelines. The components used in our implementation include:

1. **Azure Data Factory**: Manages and automates data workflows, offering a user-friendly interface to design, monitor, and control data pipelines.

2. **Azure Databricks**: A comprehensive analytics platform that integrates with Azure for large-scale data processing. Databricks clusters utilize Apache Spark, while its notebooks enable collaborative development and execution of data transformation processes.

3. **DBT (Data Build Tool)**: A command-line tool that enhances data transformation within data warehouses. DBT focuses on creating modular, verifiable, and adaptable code for transforming data efficiently.

### Key Features

1. **Modular Design**: The pipeline is designed to be modular, simplifying the addition or modification of data sources, transformations, and destinations.
   
2. **Scalability**: Azure services are leveraged to ensure the pipeline can scale to accommodate large datasets and diverse workloads.
   
3. **Automated Workflow**: Automation of data movement, transformation, and orchestration reduces the need for manual intervention and minimizes the risk of errors.
 
4. **Version Control**: DBT supports version control of the data transformation logic, fostering collaboration and ensuring reproducibility.

### Getting Started

To begin using the data pipeline, refer to the steps outlined in the Procedure.pdf file. You are encouraged to make adjustments to the data flow to customize the pipeline according to your requirements.
