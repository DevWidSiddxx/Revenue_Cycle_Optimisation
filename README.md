# Healthcare Revenue Cycle Optimisation
A real-world project focused on Healthcare Revenue Cycle Management (RCM), leveraging Azure Data Factory, Databricks, and Medallion architecture to build scalable, KPI-driven data pipelines for financial insights and timely collections.
---

## 🚀 Project Overview

The project focuses on **Healthcare Revenue Cycle Management (RCM)**, a critical component in hospital financial operations that includes patient appointments, insurance claims, treatments, billing, and payments. It addresses both **Accounts Receivable (AR)** and **Accounts Payable (AP)** to maintain a financial balance and ensure optimized collections.

---

## 🏗️ Architecture Overview

- **Medallion Architecture**:
  - **Bronze Layer**: Raw data ingestion from EMR systems, insurance APIs, and flat files.
  - **Silver Layer**: Cleaned and enriched data with Slowly Changing Dimensions (SCDs).
  - **Gold Layer**: Finalized, business-ready KPIs and reports.

- **Cloud Platforms**:
  - **Azure**:
    - Azure Data Factory (ADF) – for orchestrating ingestion.
    - Azure Databricks – for processing and transformations.
    - Azure Data Lake Storage – for raw/curated data storage.
    - Azure SQL Database – for structured reporting.
  - **GCP**:
    - BigQuery – for large-scale analytics and reporting.
    - Cloud Functions – for triggering alerts/anomaly responses.
    - Cloud Storage – for flat-file management.
    - Vertex AI – used optionally for model experimentation.

- **ML Integration**:
  - **Autoencoder-based Anomaly Detection**:
    - Detect unusual billing patterns, late payments, or suspicious transactions.
    - Applied on AR/AP data to identify risks and highlight anomalies for review.
    - Trained on historical data and deployed in a monitoring pipeline.

---

## 🔑 Key Features

- 📊 **Healthcare RCM Coverage**: End-to-end patient financial flow from registration to reimbursement.
- 📈 **Anomaly Detection with ML**: Autoencoders to catch billing irregularities and payment delays.
- 🏥 **Accounts Monitoring**: Real-time insights on AR and AP balances, payment KPIs.
- 🧠 **Machine Learning Integration**: Seamless embedding of anomaly detection into data pipeline.
- 🌐 **Multi-Cloud Setup**: Robust hybrid setup using **Azure + GCP** for distributed processing.
- 🔄 **Dynamic Pipelines**: Scalable, event-based pipelines for healthcare workflows.
- 🧾 **Audit Trails & Alerts**: Logs, version control, and automated notifications on anomalies.

---

## 🧰 Tools & Tech Stack

| Category         | Tools/Tech                           |
|------------------|---------------------------------------|
| Cloud Platforms  | Azure, GCP                            |
| Data Ingestion   | Azure Data Factory, Cloud Storage     |
| Data Processing  | Azure Databricks, BigQuery            |
| Storage          | ADLS Gen2, Cloud Storage              |
| Database         | Azure SQL, BigQuery                   |
| ML               | Autoencoder (TensorFlow/Keras/PyTorch)|
| Orchestration    | ADF, Cloud Functions                  |
| Reporting        | Power BI, Looker Studio               |

---

## 👩‍💻 User Personas

- **Data Engineers**: Set up pipelines, monitor data flows, ensure data quality.
- **Data Scientists**: Train and evaluate autoencoder models for anomaly detection.
- **Business Analysts**: Explore KPIs for AR/AP health and financial stability.
- **Healthcare Admins**: Use dashboards to ensure timely collections and flag risks.

---

Siddharth Venkatesh,Abinaya Vina,Prajasree,RudhraPriya

