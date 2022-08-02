# Capstone Project
Ramon Kidd's Capstone Project for SADA Technical Account Manager
------

The objective of this capstone project is to solve a fictitious analytics problem for a highway sensor company, SanDiego Analytics. The company is trying to improve its excel based traffic data analysis. They would like to remove the manual upload process; have a mechanism to ingest data as it becomes available, analyse and make faster decisions to inform commuters on traffic conditions?


The project will demo a solution by building a pipeline in Google Cloud, with PubSub, DataFlow and BigQuery. Live seneor traffic will be  published to a Cloud Pub/Sub topic. Then, a Cloud Dataflow streaming pipeline will subscribe to it. The pipeline will take the streaming sensor data, transform it, and insert it into a BigQuery table. We will then we be able to run a number of queries to make decisions about traffic health.
