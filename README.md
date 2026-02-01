# 🚀 E‑Commerce Sales Prediction & Decision Support System

<p align="center">
  <b>An end‑to‑end Data & AI solution built on Databricks</b><br/>
  From raw data ingestion to prediction‑driven business decisions
</p>

---

## 🧭 Project Overview

This project delivers a **production‑style, end‑to‑end data engineering and machine learning pipeline** designed to solve a common **e‑commerce business problem**: understanding which products will perform well in the future and what actions the business should take today.

Using **Databricks**, the solution transforms raw transactional data into **decision‑ready insights** through structured data layers, machine learning, dashboards, AI‑powered querying, and automated orchestration.

---

## ❓ Business Problem

E‑commerce businesses often make decisions based only on **historical sales data**, which creates several challenges:

* Uncertainty around **future product performance**
* Overstocking or stockouts due to poor demand estimation
* Ineffective pricing and promotion strategies

To move from **reactive reporting** to **proactive decision‑making**, the business needs a system that can **predict future revenue and recommend actions**.

---

## 💡 Solution Approach

This project implements a **structured and scalable solution** that:

* Organizes data using **Medallion Architecture (Bronze, Silver, Gold)**
* Builds **business‑level metrics and features**
* Trains a **machine learning model** to predict product‑level revenue
* Converts predictions into **clear business actions**
* Enables insights through **dashboards and natural language queries**
* Automates the entire workflow using **Jobs & Pipelines**

---

## 🏗️ Architecture (Medallion Design)

### 🟫 Bronze Layer — Raw Data

* Ingests raw e‑commerce transactional data
* Applies basic schema and data quality validation
* Acts as the **single source of truth**

### 🩶 Silver Layer — Cleaned Data

* Cleans and standardizes transactional data
* Handles missing values, duplicates, and invalid records
* Normalizes data types and formats

### 🟨 Gold Layer — Business Metrics

* Aggregates data to product and category levels
* Creates key business KPIs and analytical features
* Prepares data for analytics, dashboards, and ML

### 💼 Final Business Output

* Combines predictions with business logic
* Produces a **decision‑ready table** for stakeholders

---

## 🧪 Feature Engineering

Key features created at the Gold layer include:

* Total revenue
* Total orders
* Total quantity sold
* Average rating
* Product and category‑level aggregations

These features form the foundation for **analytics, dashboards, and ML model training**.

---

## 🤖 Machine Learning & MLflow

* Trained a **regression model** to predict future product‑level revenue
* Used Gold layer business metrics as input features
* Evaluated model performance using **RMSE**
* Tracked experiments, parameters, metrics, and models using **MLflow**

This ensures **reproducibility, transparency, and experiment tracking**.

---

## 📊 Final Business Output

The final output table delivers:

* **Predicted revenue** for each product
* **Performance buckets** (High / Medium / Low)
* **Recommended business actions**, such as inventory increase, price optimization, or discounting

This table directly supports **business decision‑making**.

---

## 📈 Business Dashboard

An interactive dashboard was built to:

* Compare actual and predicted revenue
* Analyze product and category performance
* Filter insights by performance buckets and products
* Enable quick, visual, data‑driven decisions

---

## 🧠 Genie — AI‑Powered Data Assistant

Databricks **Genie** enables **natural language interaction** with business data:

* Ask questions without writing SQL
* Get instant insights from the final business output
* Designed for **non‑technical stakeholders**

Example questions:

* “Top 5 products by predicted revenue”
* “Which products require discount or optimization?”

---

## ⚙️ Jobs & Pipelines Automation

The entire workflow is automated using **Databricks Jobs & Pipelines**:

* Executes Bronze → Silver → Gold → ML → Final Output
* Ensures consistent and repeatable runs
* Supports scalable and production‑ready execution

---

## 🎯 Business Impact

This solution enables organizations to:

* Shift from **reactive reporting** to **prediction‑driven decisions**
* Improve inventory planning and pricing strategies
* Identify high‑opportunity and high‑risk products early
* Make faster, more confident business decisions

---

## 🛠️ Tech Stack

* Databricks
* Apache Spark
* Delta Lake
* MLflow
* Databricks Dashboards
* Databricks Genie

---

## 🎥 Project Walkthrough

A short walkthrough video demonstrates the complete journey:

**Raw Data → Prediction → Business Decision**

---

## 🙏 Acknowledgements

Special thanks to:

* **Codebasics**
* **Indian Data Club**
* **Databricks**

for the learning resources, community support, and platform.

---

## 👤 Author

**Created by:** Chain kumar choure

> *If you found this project interesting, feel free to connect and share your feedback.*
