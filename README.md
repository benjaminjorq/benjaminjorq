# Hola, soy Benjamín Jorquera 👋

**Data Engineer Jr | Formación en Ingeniería Civil Química**

Construyo pipelines de datos end-to-end aplicando rigurosidad de ingeniería de procesos a la calidad, trazabilidad e integridad de los datos.

---

## Stack Técnico

- **Lenguajes y Procesamiento:** `Python` `SQL` `Pandas` `PySpark`
- **Bases de Datos:** `PostgreSQL` `SQL Server`
- **Cloud:** `Google Cloud Platform (BigQuery, Cloud Storage, Cloud Run Jobs)`
- **Orquestación:** `Apache Airflow`
- **DevOps:** `Docker` `Git` `GitHub Actions` `Pytest`
- **BI y Visualización:** `Power BI` `Tableau` `Looker Studio`

---

## 🚀 Proyectos Destacados

### 📌 [Industrial Maintenance Pipeline](https://github.com/benjaminjorq/industrial-maintenance-pipeline)
*Pipeline de datos batch para mantenimiento industrial, con arquitectura Medallion en GCP.*

- Ingesta multifuente desde **PostgreSQL y SFTP**, unificando datos internos y externos en un flujo ETL.
- Arquitectura **Bronze/Silver/Gold** con **Cloud Storage y BigQuery** como capas de almacenamiento y análisis.
- Transformación y **Data Quality** con Python y Pandas: validación de esquema, nulos, rangos, unicidad y valores aceptados.
- Ejecución batch en **Cloud Run Jobs**, con respaldo automático en la nube en cada etapa del pipeline.
- Consultas SQL en la capa Gold para KPIs de producción, downtime de máquinas y consumo de materiales.
- **Pytest** para pruebas unitarias de limpieza y validación, con integración continua vía **GitHub Actions**.

**Stack:** `Python` `SQL` `Pandas` `PostgreSQL` `psycopg2` `Paramiko (SFTP)` `Google Cloud Storage` `BigQuery` `Cloud Run Jobs` `Artifact Registry` `Docker` `Git` `GitHub Actions` `Pytest`

### 📌 [OpenWeather ETL Pipeline](https://github.com/benjaminjorq/openweather-etl-pipeline)
*Pipeline end-to-end orquestado con Airflow, con arquitectura Medallion y carga a Data Warehouse.*

- Ingesta desde **API REST** (clima y contaminación) hacia la capa Bronze en formato JSON.
- Limpieza, tipado y normalización con Pandas, y validaciones de calidad de datos antes de la carga.
- Modelado en **Star Schema** dentro de PostgreSQL (tablas de hechos y dimensiones).
- **Orquestación con Apache Airflow**: DAGs programados para ETL horario y generación diaria de reportes Gold.
- **Alertas en tiempo real vía Discord** ante fallos de ejecución, usando `on_failure_callback`.
- Entorno reproducible con **Docker y Docker Compose**, y pruebas unitarias con **Pytest**.

**Stack:** `Python` `Pandas` `Requests` `PyYAML` `python-dotenv` `PostgreSQL` `SQLAlchemy` `Apache Airflow` `Docker` `Docker Compose` `Pytest` `Discord Webhooks`

---

## 📫 Contacto

- 📧 benjaminjorq@gmail.com
- 📱 +56 9 4091 0880
- 💼 [LinkedIn](https://www.linkedin.com/in/bjorquera/)
- 💻 [GitHub](https://github.com/benjaminjorq)
