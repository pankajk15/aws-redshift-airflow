# Data Pipeline with Airflow  <img src="images/AirflowLogo.png" width="220" height="100" ALIGN="right">
## Introduction


A music streaming company, Sparkify, has decided that it is time to introduce more automation and monitoring to their data warehouse ETL pipelines and come to the conclusion that the best tool to achieve this is Apache Airflow.
The source data resides in S3 and needs to be processed in Sparkify's data warehouse in Amazon Redshift. The source datasets consist of JSON logs that tell about user activity in the application and JSON metadata about the songs the users listen to.

## Overview

To complete the project, you will need to create your own custom operators to perform tasks such as staging the data, filling the data warehouse, and running checks on the data as the final step.

1. Use Airflow's UI to configure your AWS credentials and connection to Redshift.

2. Verify the DAG graph is as expected 

 <img src="images/DAGgraph.JPG" width="900" height="300" ALIGN="center">
 
 3. Verify DAG tree, 
 
<img src="images/DAGTree.JPG" width="900" height="700" ALIGN="center">
