# Data Engineering 
## Project: Data Pipelines with Airflow
## Platform(Cloud): AWS
## Table of Contents
* **Definition**
    * **Project Overview** :
    A music streaming company, Sparkify, has decided that it is time to introduce more automation and monitoring to their data warehouse ETL pipelines and come to the conclusion that the best tool to achieve this is Apache Airflow.
    
    * **Problem Statement** : 
     Sparkify want to create high grade data pipelines that are dynamic and built from reusable tasks, can be monitored, and allow easy backfills. They have also noted that the data quality plays a big part when analyses are executed on top the data warehouse and want to run tests against their datasets after the ETL steps have been executed to catch any discrepancies in the datasets. 
     The source data resides in S3 and needs to be processed in Sparkify's data warehouse in Amazon Redshift. The source datasets consist of CSV logs that tell about user activity in the application and JSON metadata about the songs the users listen to.

   
* **Design**
  
![Sparkify Data Model](/DataPipelinesWithAirflow/images/SparfiyDAG.jpg)    

![Sparkify Data Model](/DataPipelinesWithAirflow/images/Pipelineview.jpg)   

