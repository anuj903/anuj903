
<div align="center">

# Anuj · Data Engineer

**Building reliable data systems from raw signals to actionable insights**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/anujgaikwad3009)
[![Email](https://img.shields.io/badge/Email-Reach%20out-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:anujgaikwad392@gmail.com)

</div>

---

I build end-to-end data engineering and analytics solutions, spanning data ingestion, transformation, streaming, data quality, storage, and visualization. My primary interests are **industrial data, real-time data platforms, manufacturing analytics, and AI-enabled data solutions**.

I'm currently developing a near-real-time hydrometry data platform while expanding my knowledge of distributed processing and cloud data engineering with **Spark, Databricks, and Google Cloud Platform**.

---

## Technical Stack

| Layer | Technologies |
|---|---|
| **Ingestion & Streaming** | Python, REST APIs, Apache Kafka, MQTT |
| **Transformation & ETL** | Python, SQL, SSIS, ETL/ELT, Data Validation |
| **Databases & Storage** | SQL Server, PostgreSQL, TimescaleDB, MySQL, MongoDB, DuckDB |
| **Distributed Processing** | Spark Structured Streaming, PySpark, Databricks |
| **Data Modeling** | Star Schema, Dimensional Modeling, SCD Type 2, Medallion Architecture |
| **Business Intelligence** | Power BI, DAX, Power Query, Semantic Data Modeling |
| **Backend & Visualization** | FastAPI, Flask, Streamlit, Plotly Dash |
| **Cloud & Infrastructure** | Google Cloud Platform (learning), BigQuery, Dataform, Docker, Git |
| **Analytics & AI** | Forecasting, Anomaly Detection, Machine Learning, LangChain, LLM Applications, n8n |

---

## Featured Projects

### ⚡ Real-time Energy Analytics Platform

Built an industrial energy analytics solution combining batch and real-time data processing, KPI dashboards, forecasting, and anomaly detection to support energy monitoring, operational visibility, and optimization.

`Python` `SQL Server` `Power BI` `Kafka` `MQTT` `Machine Learning`

### 🏭 Industrial Digital Twin & Condition-Based Monitoring

Developed an industrial equipment monitoring solution combining operational data, KPI-driven dashboards, equipment health analysis, and anomaly detection to support predictive maintenance and performance monitoring.

`Python` `PostgreSQL` `TimescaleDB` `Industrial IoT` `Machine Learning`

### 🌊 Flood Monitoring & Hydrology Data Platform - In Progress

Building a near-real-time data platform using France's Hub’Eau hydrometry API. A Python producer periodically retrieves water observations and publishes events to Kafka. A consumer persists raw events in the Bronze layer, while Spark Structured Streaming validates and transforms the data into Silver and Gold analytical layers. The platform uses TimescaleDB/PostgreSQL for storage and FastAPI with Plotly Dash for data access and visualization.

The architecture is containerized with Docker, with a design that allows Bronze storage to move to Google Cloud Storage in the future.

`Python` `Kafka` `Spark Structured Streaming` `PostgreSQL` `TimescaleDB` `Docker` `FastAPI` `Plotly Dash`

### 📡 IoT Streaming Data Pipeline

Designed and implemented an Industrial IoT pipeline that ingests telemetry from edge devices, transports events through Kafka, stores the data in SQL Server, and exposes operational metrics through Power BI dashboards.

**Architecture:** MQTT → Kafka → SQL Server → Power BI

`Python` `MQTT` `Kafka` `SQL Server` `Power BI`

### 🏗️ Enterprise SQL Data Warehouse

Designed a SQL Server data warehouse using dimensional modeling to organize analytical data into fact and dimension tables. Explored historical tracking with SCD Type 2 and structured data processing using a Medallion Architecture approach.

`SQL Server` `SQL` `Star Schema` `SCD Type 2` `Medallion Architecture`

---

## Current Engineering Focus

### Hydrometry Data Platform

My current focus is taking the Hub’Eau project beyond basic ingestion and building a reliable, observable data platform.

- **Ingestion:** API polling, Kafka event production, and consumer processing.
- **Data quality:** Validation, transformation, duplicate handling, and consistent analytical records.
- **Data architecture:** Bronze, Silver, and Gold layers using Spark Structured Streaming.
- **Storage & serving:** TimescaleDB/PostgreSQL, FastAPI, and Plotly Dash.
- **Infrastructure:** Docker-based local deployment, with future Google Cloud Storage integration.

The objective is to understand and implement the engineering decisions behind a maintainable data platform, not just connect a collection of tools.

---

## Engineering Principles

> Reliable pipelines over impressive demos · Data quality by design · Simple, maintainable architectures · Analytics that support real decisions

---

<div align="center">

**Open to:** Data Engineering · Analytics Engineering · Data Analytics · Industrial Data Platforms

</div>
