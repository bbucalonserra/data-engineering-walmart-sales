# Walmart Sales
This data engineering project focuses on analyzing Walmart sales data. Its goal is to create an efficient pipeline to collect, store, and process this data, providing valuable insights for strategic decision-making. It aims to understand customer purchasing patterns, optimizing the data structure for accurate and reliable analyses. Throughout the project, it prioritizes data quality and the construction of a robust model, aiming not only to address key business questions but also to establish a foundation for future, more complex and informed analyses.

# Index
1. [Objective](#Objective)


## Objective
The objective of this data engineering project is to **develop a data pipeline for collecting, organizing, and analyzing** Walmart sales data in Myanmar, country located in the continent of Asia, sharing borders with several countries, including Bangladesh and India. The primary focus is on structuring the data effectively to delivery actionable insights into customer purchasing behaviors and trends. This includes **ensuring data quality, constructing a data model and establishing a scalable framework** that enables informed decision-making for Walmart's business strategies based on the insights extracted from the analyzed sales data. Throughout this investigation, we'll aim to answer the following questions:

- Which product line generates the highest sales revenue?
- What is the distribution of customer types (e.g., member vs. non-member)?
- How does gender impact purchasing habits or product preferences?
- Which products have the highest and lowest unit prices?
- What is the average quantity sold per product line?
- Which product lines have the highest and lowest gross income?
- Are there differences in sales performance among different branches?
- Which city generates the most sales revenue?
- What are the preferred payment methods?
- Is there a relationship between payment method and purchase amount?
- What is the average rating of products sold?
- Is there a correlation between product ratings and sales revenue?
- What is the average tax percentage applied to sales?
- How does the cost of goods sold (COGS) vary across different product lines?

## Project
### 1. Searching for Data
The searching for data is a crucial process of locating and collecting relevant sources of information. It involves exploring various origins, applying extraction methods and ensuring the accurate and reliable acquisition of necessary data for subsequent analysis and processing
The searching for the data was made by the Kaggle website (https://www.kaggle.com/), the data was found by looking sales around the world. The page where the dataset was found is here: https://www.kaggle.com/datasets/msamhoud/walmart-sales


### 2. Data Collection
Data collection is the process of collecting information from one oore more sources to be used in analyses, studies, research or decision-making processes. This procedure involves obtaining **raw or processed data** from diverse sources such as websites, databases, devices, social media, among others.
For this project the data collection will be done using APIs.
The APIs, or Application Programming Interfaces, serve as intermediaries that allow different software applications to communicate and interact with each other. They specify the methods and data formats that applications can use to request and exchange information. APIs enable seamless data retrieval and integration from various sources, offering standardized access to functionalities or data offered by a service, platform, or application. The most common formats for interaction between APIs include:

- JSON (JavaScript Object Notation): A lightweight, human-readable data interchange format widely used due to its simplicity and ease of parsing
- XML (eXtensible Markup Language): Though less prevalent today, it's still used in some APIs. It structures data hierarchically but is more verbose compared to JSON
- REST (Representational State Transfer): Not precisely a data format but an architectural style that utilizes HTTP methods (GET, POST, PUT, DELETE) to access and manipulate resources. Responses are often in JSON or XML
- SOAP (Simple Object Access Protocol): An XML-based protocol used for exchanging structured information over a network, including remote procedure calls. It's more complex than REST and uses XML to structure data
- GraphQL: A query language and runtime for APIs that gives clients control over the data they receive. It enables clients to request only the needed fields, potentially reducing bandwidth and enhancing efficiency
