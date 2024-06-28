# Streaming-data-from-Reddit-using-Kafka-Spark-and-MongoDB
In this data engineering project, the primary objective is to architect and deploy a seamless streaming data pipeline that harnesses the power of real-time data for actionable insights. By integrating the Reddit API with Apache Kafka, the aim to continuously collect, process, and funnel real-time subreddit posts into a dedicated Kafka topic. This robust pipeline will enable the continuous flow of data, empowering downstream analytics and applications with fresh, relevant content.

![image](https://github.com/Bolesco12/Streaming-data-from-Reddit-using-Kafka-Spark-and-MongoDB/assets/159485185/bfb48b59-9ae1-49e2-920b-e07df10286fe)


## Table of Contents

Overview/Problem
Rationale for the project
Aim of the Project
Data Description
Tech Stack
Project Scope

## Business Overview/Problem

In the rapidly evolving tech landscape, TechInsight Solutions grapples with the challenge of efficiently leveraging real-time insights from Reddit, a vital source of user-generated content. 
The absence of a streamlined solution hinders the organization from tapping into valuable market intelligence, conducting brand perception analysis, and enhancing customer engagement. To address this, our project aims to develop a scalable streaming data pipeline. This solution will seamlessly integrate Reddit data into TechInsight Solutions' analytics ecosystem, facilitating timely and data-driven decision-making for heightened competitiveness and market responsiveness.


## Rationale for the Project

In this data engineering project, our primary objective is to establish a seamless streaming data pipeline. By leveraging the Reddit API and Kafka integration, we plan to continuously collect and funnel real-time subreddits into a Kafka topic. The heart of our real-time processing lies in Apache Spark Streaming, where we intend to conduct critical tasks like text preprocessing, language detection, and sentiment analysis using machine learning models. Data will be securely stored, in a NoSQL Database
Ultimately, this data pipeline equips organizations with the power to stay ahead in today's dynamic digital landscape by making informed decisions based on real-time data ingestion. It enhances customer engagement, assists in product development, and provides a competitive edge through the integration of robust architecture, data security, and efficient data processing capabilities.

## Aim of the Project

A. Real-time Data Collection: Establish a reliable mechanism to continuously fetch data from Reddit using the Reddit API and stream them into a Kafka topic
B. Efficient Data Processing: Utilize Apache Spark Streaming to process the incoming data streams in real-time.
C. Scalability: Design the pipeline to be scalable, allowing for the handling of varying data volumes and ensuring system performance.
D. Data Storage: Integrate MongoDB for persistent storage, enabling historical trend analysis and cross-platform correlation

## Data Description

![image](https://github.com/Bolesco12/Streaming-data-from-Reddit-using-Kafka-Spark-and-MongoDB/assets/159485185/e171ce74-890e-4eda-89a7-a0120ef44a76)



## Tech Stack

A. Apache Kafka
B. Apache Spark
C. Amazon EC2
D. Reddit API
 

# Data Storage and Persistence
A. MongoDB
 

# Development and Deployment
A. Python


## Project Scope
A. Understanding the project Overview and Architecture
B. Understanding Apache Kafka
C. Create Zookeeper and Kafka Instances
D. Understanding Apache Spark
E. Create Spark Cluster
F. Fetching Data from Reddit using API
G. Create Kafka Producer to stream data from reddit API
H. Ingest and process kafka data within spark
I. Load data into MongoDB collection with Spark
