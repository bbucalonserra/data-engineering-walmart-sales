# Walmart Sales
This data engineering project focuses on analyzing Walmart sales data. Its goal is to create an efficient pipeline to collect, store, and process this data, providing valuable insights for strategic decision-making. It aims to understand customer purchasing patterns, optimizing the data structure for accurate and reliable analyses. Throughout the project, it prioritizes data quality and the construction of a robust model, aiming not only to address key business questions but also to establish a foundation for future, more complex and informed analyses.

# Index
1. [Objective](#Objective)
2. [O Projeto](#o-projeto)
   - [1. Busca Pelos Dados](#1-busca-pelos-dados)
   - [2. Coleta](#2-coleta)
     - [2.1 Definição do Sistema de Cloud Computing](#21-definição-do-sistema-de-cloud-computing)
     - [2.2 Recursos de Armazenamento](#22-recursos-de-armazenamento)
   - [3. Modelagem e Carga](#3-modelagem-e-carga)
     - [3.1 Conexão Data Lake e Databricks](#31-conexão-data-lake-e-databricks)
     - [3.2 Criação de Schema](#32-criação-de-schema)
     - [3.3 Criação das Tabelas da Camada Bronze](#33-criação-das-tabelas-da-camada-bronze)
     - [3.4 ETL - Extract, Transform e Load (Bronze - Silver)](#34-etl---extract-transform-e-load-bronze---silver)
     - [3.5 Criação das Tabelas da Camada Silver](#35-criação-das-tabelas-da-camada-silver)
     - [3.6 ETL - Extract, Transform e Load (Silver - Gold)](#36-etl---extract-transform-e-load-silver---gold)
     - [3.7 Criação das Tabelas da Camada Gold](#37-criação-das-tabelas-da-camada-gold)
     - [3.8 Catálogo de Dados](#38-catálogo-de-dados)
   - [4. Análise](#4-análise)
     - [4.1 Qualidade dos Dados](#41-qualidade-dos-dados)
     - [4.2 Solução dos Problemas](#42-solução-dos-problemas)
    

## Objective
The objective of this data engineering project is to **develop a data pipeline for collecting, organizing, and analyzing** Walmart sales data. The primary focus is on structuring the data effectively to derive actionable insights into customer purchasing behaviors, patterns, and trends. This includes **ensuring data quality, constructing a data model and establishing a scalable framework** that enables informed decision-making for Walmart's business strategies based on the insights extracted from the analyzed sales data.
