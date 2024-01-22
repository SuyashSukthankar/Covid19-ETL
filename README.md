# AWS End to End Project using COVID 19 Data 

## Brief Description
This project aims to create a comprehensive big data pipeline that leverages various AWS tools such as AWS Lambda, AWS Glue, AWS S3, Amazon Redshift, Amazon EventBridge, and Amazon Quicksight to conduct intricate analysis on COVID-19 data. The goal is to develop an interactive dashboard that can provide insights into the trends and patterns of the virus, allowing for more informed decision-making by public health officials, researchers, and the general public.Using AWS tools I have created an ETL Pipeline to load data from the John Hopkins Github Repository, perform changes to the dataset in Pyspark, create an external Dataset on top of the S3 bucket in Redshift and finally visualize the reuslts using Amazon Quicksight.

## Tech Stack 
Language: Python
Package: PySpark
Services: AWS Lambda, AWS Glue, AWS S3, Amazon Redshift, Amazon EventBridge, Amazon Quicksight

## Dataset Used
John Hopkins University maintains a GitHub repository that contains up-to-date data on COVID-19 cases, deaths, and recoveries from around the world. The repository is publicly available and can be accessed by anyone interested in analyzing the data. The data is provided in a CSV (comma-separated values) format and is updated on a daily basis. It includes information on the number of confirmed cases, deaths, and recoveries, as well as other relevant data such as the date, country, and region.

## Architecture Diagram
![image](https://github.com/SuyashSukthankar/Covid19-ETL/assets/9166373/54932d8a-660d-4e88-9614-c724317d6b14)
![image](https://github.com/SuyashSukthankar/Covid19-ETL/assets/9166373/86bf7a02-aede-4605-900b-33ac72e1255b)

