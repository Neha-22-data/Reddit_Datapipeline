# Reddit Data Pipeline Project-

This designed for efficiently extract, transform, and load (ETL) Reddit data into a Redshift data warehouse. Leveraging a blend of industry-standard tools and services, the pipeline ensures seamless data processing and integration.

## Overview
This pipeline is structured to accomplish the following tasks:
1) Extraction: Retrieve data from Reddit utilizing its API.
2) Storage: Store the raw data efficiently into an S3 bucket managed by Airflow.
3) Transformation: Employ AWS Glue and Amazon Athena to transform the data effectively.
4) Loading: Load the transformed data seamlessly into Amazon Redshift, facilitating analytics and query operations.

## Architecture
![Pipeline Architecture](RedditDataEngineering.png)

## Components - 
**- Docker:** Containerization platform that packages applications and their dependencies
**- Apache Airflow:** orchestrator for scheduling and managing ETL workflows
**- Celery:** Facilitates distributed task execution, enhancing scalability and performance
**- PostgreSQL:** Utilized for intermediate data storage and manipulation
**- AWS S3:** Provides storage for raw and processed data
**- AWS Glue:** provides automated ETL service for transformation and loading
**- AWS Athena:** Enables querying data directly from S3
**- AWS Redshift:** Datawarehouse to load transformed and aggregated Reddit data

## Requirements -:
- AWS Account
- Reddit API credentials
- Docker installed on system
- Python






