# aws-data-analytics-exercise
This repository has following components of a data pipeline application
- Lambda fuction that pushes data on schedule to a Kinesis Data Stream using KPL libraries
- Kinesis Data Analytics Application that performs basic transformations on the data
- Kinesis Data Firehose to publish the data to Redshift
- Basic Queries on Redshift table for the transformed data

For this example, we will use Amazon User Review data from Kaggle.com
