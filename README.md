# End-to-End Earthquake Data Engineering Pipeline

A complete ETL pipeline built on **Azure Databricks** to ingest, process, and prepare earthquake data for analytics using the **Bronze–Silver–Gold architecture**.

---

## 📌 Overview
This project demonstrates a cloud-based ETL workflow designed for earthquake event analysis.  
Raw JSON data is ingested, cleaned, transformed using PySpark, and stored in **Delta Lake** for fast, reliable analytics.

The goal is to showcase Databricks best practices and modern lakehouse design.

---

## 🚀 Features
- Automated processing of raw earthquake JSON data  
- PySpark-based transformations and schema normalization  
- Multi-layer **Bronze → Silver → Gold** architecture  
- ACID-compliant Delta Lake storage  
- Optimized datasets for downstream analytics and reporting  
- Modular, notebook-driven ETL flow  

---

## 🧱 Pipeline Architecture

### **Bronze Layer**
Raw ingestion layer where data is stored exactly as received.  
No transformations are applied.

### **Silver Layer**
Processed and cleaned dataset.  
Flattened JSON, validated fields, and normalized schema.

### **Gold Layer**
Curated, analytics-ready tables.  
Aggregated for dashboards, reporting, and BI tools.

---

## 🛠️ Technologies Used
- **Azure Databricks**  
- **PySpark**  
- **Delta Lake**  
- **Azure Data Lake Storage Gen2**  
- **Notebook-driven ETL design**



