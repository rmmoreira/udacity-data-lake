# Project 3: Song Play Analysis With AWS Data Lake and Apache Spark

## Summary
* [Introduction](#Introduction)
* [Schema design](#Schema-design)
* [Usage](#Usage)
* [Files in repository](#Files-in-repository)

## Introduction
Build an ETL pipeline that extracts song and log data from json files hosted in a S3. 
This data is processed into tables using a star schema with **Apahce Spark**.
Lastly the tables are loaded back in a S3 bucket

### Schema design
* **songplays:** records in log data associated with song plays.

### Usage

1. Fill the configuration file `dl.cfg` with your AWS credentials

2. Open a terminal session

3. Run `python etl.py` to extract data from S3, transform it and load **songplays table** again in S3 
 

### Files in repository
* **etl.py:** retrieve data and process it into tables (star schema) writing them in S3
* **dl.cfg:** AWS credentials