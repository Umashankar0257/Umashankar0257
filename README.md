# 👋 Hi, I'm Umashankar Reddy M

### Azure Data Engineer | Azure Data Factory | Azure Databricks | PySpark | SQL

**Building reliable data pipelines, scalable data processing workflows, and cloud-based data engineering solutions.**

I am an IT professional with **2.5+ years of experience** in enterprise application support, database troubleshooting, SQL development, stored procedures, data validation, and reporting. My professional experience includes supporting business-critical applications at **ISRO HQ through Cezen Technologies**, where I work with application workflows, database logic, production issues, and data-related requirements.

Alongside my professional responsibilities, I am developing hands-on expertise in **Azure Data Engineering** by building end-to-end projects using Azure Data Factory, Azure Data Lake Storage Gen2, Azure Databricks, PySpark, and Delta Lake.

My goal is to combine my strong SQL and database background with cloud data engineering skills to build maintainable, reliable, and scalable data pipelines.

---

## 🚀 About Me

- 💼 **Professional experience:** 2.5+ years in enterprise application and database support.
- 🏢 **Current work experience:** Supporting the COWAA application at ISRO HQ through Cezen Technologies.
- 🗄️ **Database expertise:** SQL queries, stored procedures, debugging, data corrections, validation, and reporting.
- ☁️ **Cloud focus:** Azure Data Factory, Azure Data Lake Storage Gen2, Azure Databricks, and PySpark.
- 🔄 **Data engineering:** ETL/ELT, data ingestion, transformations, pipeline parameterization, and incremental loading concepts.
- 🏗️ **Data architecture:** Learning and implementing Medallion Architecture with Bronze, Silver, and Gold layers.
- ⚡ **Lakehouse technologies:** Delta Lake, Spark DataFrames, schema management, and transactional data processing.
- 🔧 **Development practices:** Git, GitHub, feature branches, pull requests, code reviews, and CI/CD concepts.
- 🎯 **Career focus:** Azure Data Engineer / Data Engineer.

## 🛠️ Technical Skills

### Azure & Data Engineering

- Microsoft Azure
- Azure Data Factory (ADF)
- Azure Data Lake Storage Gen2 (ADLS Gen2)
- Azure Databricks
- Apache Spark
- PySpark
- Delta Lake
- ETL/ELT Pipeline Development
- Data Ingestion and Transformation
- Pipeline Parameterization
- Medallion Architecture
- Data Quality and Validation
- Full and Incremental Loading Concepts

### Programming & Databases

- SQL
- Python
- PySpark
- Stored Procedures
- PL/SQL and T-SQL
- Query Debugging and Optimization
- Data Reconciliation
- Data Cleansing and Validation
- Relational Database Concepts

### Azure Data Engineering Concepts

- Source-to-Destination Data Movement
- ADF Copy and Lookup Activities
- Linked Services and Datasets
- Pipeline and Notebook Parameters
- Parquet File Processing
- Bronze, Silver, and Gold Data Layers
- Delta Lake MERGE and UPSERT Concepts
- Batch Processing
- Schema Validation and Evolution
- Data Lineage and Ingestion Metadata
- Error Handling and Rerun Safety

### Development & Collaboration

- Git and GitHub
- Git Branching and Pull Requests
- Code Review Workflows
- Databricks Notebooks
- JSON Configuration
- CI/CD Concepts
- Technical Documentation

---

## 💼 Professional Experience

### Cezen Technologies Pvt. Ltd. — Application & Database Support
**Client / Work Location: ISRO Headquarters (ISRO HQ)**

I support the COWAA enterprise application, developed by SHAR and used across ISRO centres for business transactions.

The application supports modules such as Administration, Accounts, Payroll, Purchase, and Stores.

**Key responsibilities:**

- Troubleshoot application and database-related issues reported by end users.
- Debug application workflows by tracing values from JSP screens to stored procedures and database results.
- Analyze SQL queries and stored procedure logic to identify root causes of production issues.
- Perform data corrections and validation in coordination with business and technical teams.
- Develop SQL queries and reports to meet end-user data and reporting requirements.
- Investigate issues involving employee information, payroll-related processes, transaction workflows, and business rules.
- Validate application behaviour and database results after changes.
- Coordinate with relevant teams to resolve incidents and maintain application reliability.

**Relevant skills:** SQL, stored procedures, PL/SQL, T-SQL, database debugging, production support, data validation, reporting, root-cause analysis, and business-rule analysis.

This experience provides a strong foundation in understanding how enterprise applications generate, process, store, and retrieve business data.

---

## 📌 Featured Data Engineering Projects

### 1. CareSync — End-to-End Azure Data Engineering

**Status:** In progress

CareSync is my hands-on Azure Data Engineering portfolio project, designed to demonstrate how data can be ingested, stored, processed, validated, and prepared for analytical consumption using Azure services.

The project separates pipeline orchestration from data transformation using two GitHub repositories.

#### Architecture

```text
Source Data
    |
    v
Azure Data Factory
    |
    v
Azure Data Lake Storage Gen2
    |
    v
Landing Files
    |
    v
Azure Databricks
    |
    v
Bronze Layer
    |
    v
Silver Layer
    |
    v
Gold Layer
    |
    v
Analytics-Ready Data
```

#### Repository A — Azure Data Factory

**Focus:** Pipeline orchestration and data movement.

- Develop and organize ADF pipeline definitions.
- Work with pipeline parameters and reusable configurations.
- Understand linked services, datasets, and activity dependencies.
- Explore Copy and Lookup activities for ingestion and metadata-driven workflows.
- Integrate orchestration with downstream Databricks processing.
- Manage pipeline definitions through GitHub.

🔗 **Repository:** [caresync_adf_repo](https://github.com/Umashankar0257/caresync_adf_repo)

#### Repository B — Azure Databricks

**Focus:** Data processing and lakehouse architecture.

- Work with parameterized Databricks notebooks.
- Read Parquet files using PySpark.
- Use `source_system`, `table_name`, and `landing_timestamp` as notebook parameters.
- Access files through Unity Catalog Volumes.
- Explore ingestion metadata such as landing and insertion timestamps.
- Organize processing into Landing-to-Bronze and Bronze-to-Silver stages.
- Develop the Gold layer for curated analytical datasets.
- Practice data cleansing, validation, and Delta Lake concepts.

🔗 **Repository:** [caresync-adb-repo](https://github.com/Umashankar0257/caresync-adb-repo)

**Technologies:** Azure Data Factory, ADLS Gen2, Azure Databricks, PySpark, Apache Spark, Delta Lake, Unity Catalog, Git, and GitHub.

**Key learning areas:** Reusable ingestion, orchestration, lakehouse architecture, data quality, batch processing, incremental loading, and source control.

---

### 2. COINS Central Data Platform — Azure Data Engineering

**Focus:** Centralized data ingestion and processing across multiple source databases.

This portfolio project is based on the concept of consolidating data from multiple ISRO-centre database structures into a centralized data platform for downstream processing and reporting.

The design draws on the COWAA domain, including Administration, Accounts, Payroll, Budget, and Stores.

#### Proposed data flow

```text
Multiple Source Databases
          |
          v
Azure Data Factory
          |
          v
ADLS Gen2 — Bronze
          |
          v
Azure Databricks / PySpark
          |
          v
Silver — Cleansed Data
          |
          v
Gold — Curated Data
          |
          v
Reporting and Analytics
```

**Technologies:** Azure Data Factory, ADLS Gen2, Azure Databricks, PySpark, SQL, and Delta Lake.

**Engineering objectives:**

- Explore ingestion patterns for multiple source datasets.
- Standardize data into a consistent processing architecture.
- Apply transformations and validation.
- Organize datasets into Bronze, Silver, and Gold layers.
- Develop reusable ingestion and processing patterns.

**Status:** Portfolio project / development work. Refer to the repository for the components actually implemented.

---

### 3. Delta Lake — Hands-on Learning & Practice

**Focus:** Reliable data storage and lakehouse table operations.

I practise Delta Lake concepts through Databricks notebooks to understand how data engineers manage evolving datasets and maintain reliable processing workflows.

**Topics covered in my learning work include:**

- Creating and managing Delta tables.
- Reading and writing Delta datasets.
- ACID transaction concepts.
- Schema enforcement and schema evolution.
- `MERGE INTO` for insert and update operations.
- UPSERT patterns and deduplication.
- Time travel and historical versions.
- `UPDATE`, `DELETE`, and table maintenance concepts.
- `OPTIMIZE` and `VACUUM` concepts.
- Full loads versus incremental processing.

**Technologies:** Azure Databricks, Apache Spark, PySpark, Spark SQL, and Delta Lake.

These topics form part of my hands-on learning and practice. Individual features are implemented in the notebooks where demonstrated.

---

## 🏗️ My Data Engineering Approach

I focus on understanding the complete lifecycle of data rather than only writing transformation code.

| Stage | What I focus on |
|---|---|
| Ingestion | Moving source data into cloud storage |
| Orchestration | Coordinating activities through ADF |
| Storage | Organizing data in ADLS Gen2 |
| Processing | Transforming data using Spark and PySpark |
| Data quality | Validating schemas, required fields, and duplicates |
| Lakehouse | Organizing data into Bronze, Silver, and Gold layers |
| Reliability | Understanding retries, reruns, and incremental processing |
| Collaboration | Managing changes through Git and GitHub |
| Documentation | Explaining architecture, setup, and processing logic |

## 📚 Currently Learning & Improving

- Designing reusable and parameterized Azure Data Factory pipelines.
- Building PySpark DataFrame transformations.
- Implementing Delta Lake MERGE and incremental loading patterns.
- Improving data quality, deduplication, and schema validation.
- Understanding Azure identity, permissions, and secure access.
- Implementing GitHub-based CI/CD for data engineering projects.
- Improving monitoring, error handling, and pipeline reliability.
- Preparing for Azure Data Engineer technical interviews.

## 🤝 Connect With Me

- 💼 **LinkedIn:** [Umashankar Reddy M](https://www.linkedin.com/in/umashankar0257/)
- 🐙 **GitHub:** [@Umashankar0257](https://github.com/Umashankar0257)

I am interested in Azure Data Engineering opportunities where I can apply my SQL and database experience while contributing to modern cloud data platforms.

---

⭐ **Thanks for visiting my profile!** Explore my repositories to follow my progress in Azure Data Engineering, PySpark, and lakehouse development.
