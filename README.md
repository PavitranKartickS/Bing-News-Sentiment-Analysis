# Bing-News-Sentiment-Analysis

### Overview
The News Sentiment Analysis Project leverages Microsoft Fabric's comprehensive suite of tools to derive sentiment insights from news articles. This project integrates data engineering, data science, and data analysis tasks, along with automated pipelining, to create a seamless and efficient workflow. By utilizing the Bing News API, the project collects news articles, processes and cleans the data using PySpark and SQL, performs sentiment analysis with SynapseML, and visualizes the results through an interactive Power BI dashboard. Azure Data Factory automates the entire workflow, ensuring reliability and efficiency. A pipeline is scheduled to run daily, performing the entire process to display an up-to-date Power BI report, an example of which is provided in the repository.

### Components
- Bing News API: Collects news articles from various sources.
- Microsoft Fabric: Provides the infrastructure for data storage, processing, and analysis.
- OneLake Database: Stores raw and processed data.
- SynapseML: Performs sentiment analysis on the cleaned data.
- Power BI: Visualizes and analyzes the sentiment analysis results.
- Azure Data Factory: Automates data pipelines for seamless workflow integration.

### Workflow
- Data Collection: News articles are gathered using the Bing News API.
- Data Pre-Processing: Data is cleaned and formatted using PySpark, including removing duplicates, handling missing values, and standardizing data formats.
    SQL queries are used to manage and manipulate the data within the OneLake database.
- Sentiment Analysis: Sentiment analysis is conducted using SynapseML, leveraging PySpark for efficient data processing and machine learning model application.
    The results are stored in a separate table within the same Lakehouse database.
- Data Visualization: An interactive Power BI dashboard is created to visualize and analyze the sentiment analysis results, providing valuable insights and trends.
- Data Pipelines: Data pipelines are developed and automated using Azure Data Factory to streamline the entire workflow, from data collection to analysis, ensuring efficiency and reliability.

A pipeline is scheduled to run daily, performing the entire process to keep the Power BI report up-to-date. An example of the report is provided in the repository.
### Key Features
- Comprehensive Data Handling: Efficiently collects, processes, and analyzes news articles.
- Advanced Sentiment Analysis: Utilizes SynapseML for in-depth sentiment insights.
- Interactive Visualization: Power BI dashboard provides clear and actionable insights.
- Automated Workflow: Azure Data Factory ensures a seamless and reliable data pipeline with daily updates.
  
### Acknowledgements
Thanks to Microsoft for providing the tools and services used in this project.
Special thanks to the developers of SynapseML, Power BI, and Azure Data Factory.
