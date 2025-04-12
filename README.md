# 🏎️ Formula 1 Data Pipeline with Azure Databricks & Spark

This project showcases the design and implementation of a **real-world data engineering solution** using **Azure Databricks**, built around the historical data of **Formula 1** races. It is inspired by professional data engineering practices and aligned with the skills required for the **Azure Data Engineer Associate (DP-203)** certification.

---

## 🧩 Tools & Technologies

| Tool                | Purpose |
|---------------------|---------|
| **Azure Databricks** | Unified analytics and Spark environment |
| **Spark Core / PySpark** | Distributed data processing |
| **Delta Lake**      | Lakehouse storage layer with ACID capabilities |
| **Azure Data Lake Gen2** | Scalable cloud data lake storage |
| **Azure Data Factory** | ETL orchestration and scheduling |
| **Power BI**        | Data visualization and reporting |

---

## 💡 Example Use Cases

- Analyze driver and constructor performance across seasons

---

## ⚙️ How to Use This Project

1. Clone or import this repo using **Databricks Repos** or the **Databricks CLI**.
2. Launch notebooks inside `set-up/` to configure the workspace and database.
3. Use `ingestion/` to load data from ADLS Gen2 or DBFS.
4. Process data using notebooks in `trans/` and promote results to Delta tables.
5. Analyze using notebooks in `analysis/` or connect to Power BI.
6. Automate orchestration with ADF pipelines and scheduling triggers.

---

## ✅ Prerequisites

- Access to an **Azure Databricks** workspace
- Access to **Azure Data Lake Gen2** storage
- **Azure Data Factory** environment for orchestration
- Basic understanding of **Spark**, **SQL**, and **Azure fundamentals**
