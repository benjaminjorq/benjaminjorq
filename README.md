# Hi, I'm Benjamín Jorquera 👋

**Chemical Engineer & Data Engineer**

I build end-to-end data pipelines, applying process engineering rigor to data quality, traceability, and integrity.

---

## Tech Stack

- **Languages & Processing:** `Python` `SQL` `Pandas` `PySpark`
- **Databases:** `PostgreSQL` `SQL Server`
- **Cloud:** `Google Cloud Platform (BigQuery, Cloud Storage, Cloud Run Jobs, Cloud Scheduler, Artifact Registry, Secret Manager, IAM)`
- **Orchestration:** `Apache Airflow`
- **DevOps:** `Docker` `Git` `GitHub` `GitHub Actions (CI)` `Pytest`
- **BI & Visualization:** `Power BI (Power Query)` `Tableau` `Looker Studio`

---

## 🚀 Featured Projects

### 📌 [Industrial Maintenance Pipeline](https://github.com/benjaminjorq/industrial-maintenance-pipeline)
*Batch data pipeline for industrial maintenance, with a Medallion architecture on GCP.*

- Multi-source ingestion from **PostgreSQL and SFTP**, unifying internal and external data in a single ETL flow.
- **Bronze/Silver/Gold** architecture with **Cloud Storage and BigQuery** as the storage and analytics layers.
- Transformation and **Data Quality** with Python and Pandas: schema validation, nulls, ranges, uniqueness, and accepted values.
- Batch execution on **Cloud Run Jobs**, with automatic cloud backup at every stage of the pipeline.
- SQL queries on the Gold layer for production KPIs, machine downtime, and material consumption.
- **Pytest** for unit testing of cleaning and validation logic, with continuous integration via **GitHub Actions**.

**Stack:** `Python` `SQL` `Pandas` `PostgreSQL` `psycopg2` `Paramiko (SFTP)` `Google Cloud Storage` `BigQuery` `Cloud Run Jobs` `Artifact Registry` `Docker` `Git` `GitHub Actions` `Pytest`

### 📌 [OpenWeather ETL Pipeline](https://github.com/benjaminjorq/openweather-etl-pipeline)
*End-to-end pipeline orchestrated with Airflow, featuring a Medallion architecture and Data Warehouse loading.*

- Ingestion from a **REST API** (weather and air pollution) into the Bronze layer in JSON format.
- Cleaning, typing, and normalization with Pandas, plus data quality validations before loading.
- **Star Schema** modeling in PostgreSQL (fact and dimension tables).
- **Orchestration with Apache Airflow**: scheduled DAGs for hourly ETL and daily Gold report generation.
- **Real-time alerts via Discord** on execution failures, using `on_failure_callback`.
- Reproducible environment with **Docker and Docker Compose**, and unit tests with **Pytest**.

**Stack:** `Python` `Pandas` `Requests` `PyYAML` `python-dotenv` `PostgreSQL` `SQLAlchemy` `Apache Airflow` `Docker` `Docker Compose` `Pytest` `Discord Webhooks`

---

## 📫 Contact

- 📧 benjaminjorq@gmail.com
- 📱 +56 9 4091 0880
- 💼 [LinkedIn](https://www.linkedin.com/in/bjorquera/)
- 💻 [GitHub](https://github.com/benjaminjorq)
