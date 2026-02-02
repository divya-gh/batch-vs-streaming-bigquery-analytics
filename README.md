# batch-vs-streaming-bigquery-analytics
Timely access to data is critical for organizations to respond quickly to market changes, customer needs, and operational issues.

Batch processing is a method of collecting large volumes of data over a period of time, then processing it all at once. It is best for processing large amounts of data and tasks that do not require near real-time processing.

Streaming processing is a method of processing data as it is received. It is best for processing data continuously in real time. It is important for data analysts and data scientists to understand the difference between the two since both processes have their own advantages and disadvantages.

## 🚀 Project Overview

This project demonstrates how to identify, analyze, and query batch and streaming data sources using Google BigQuery. The use case is based on a real-world eCommerce scenario where near real-time shopping cart activity is analyzed to support merchandising and pricing decisions.

The project highlights how streaming data enables minute-by-minute insights, while batch data supports historical and aggregated analysis.

## 🧠 Business Scenario

### A lead merchandiser needs to monitor:

* Real-time items added to shopping carts

* Minute-by-minute trends for promotional effectiveness

### Using BigQuery, we analyze:

* Streaming source: shopping_cart table (live data ingestion)

* Batch source: orders table (periodic batch loads)

## 🏗️ Architecture

* Data Warehouse: Google BigQuery

* Streaming Source: User shopping cart activity

* Batch Source: Completed orders

* Analytics Layer: SQL queries with time-based aggregation

## 🔍 Key Concepts Demonstrated

* Difference between batch vs streaming data processing

* Identifying streaming buffers in BigQuery

* Real-time analytics using CURRENT_TIMESTAMP()

* Time-based aggregation with FORMAT_TIMESTAMP()

* Join operations between transactional and dimensional tables

* Designing queries for live dashboards

## 🧪 Queries Used
### 1️⃣ Identify Streaming Data
<img src="./queries/streaming_cart_query.png" height="400" width="400">

### 2️⃣ Identify Batch Data

<img src="./queries/batch_orders_query.png" height="400" width="400">

### 3️⃣ Minute-by-Minute Streaming Analytics

<img src="./queries/minute_level_dashboard_query.png" height="400" width="400">

## 📈 Insights Generated

* Streaming data provides real-time visibility into customer behavior

* Batch data is ideal for historical reporting and reconciliation

* Combining both enables hybrid analytics architectures

## 🛠️ Tools & Technologies

- Google BigQuery
- SQL
- Streaming Buffers
- Time-series Aggregation
- Cloud Data Analytics

## 🎯 Skills Demonstrated

- Cloud Data Analytics
- Streaming vs Batch Processing
- SQL for Analytics
- Time-based Data Aggregation
- Data Modeling & Joins
- Business-Oriented Analytics Design

## 📌 Use Cases
- Real-time dashboards
- Promotion effectiveness analysis
- Inventory and demand monitoring
- eCommerce behavioral analytics

🏁 Conclusion



### 📎 This project was completed as part of the Google Cloud Data Analytics learning program.
