# 🚀 SQL Data Warehouse Project  
A complete end-to-end data warehouse and analytics solution built using a modern Medallion Architecture (Bronze → Silver → Gold).  
This project demonstrates how raw operational data from multiple systems can be transformed into reliable, analytics-ready datasets.

---

# 🧱 1. Data Architecture Overview  

This project follows a layered Medallion architecture:

![Data Architecture](docs/data_architecture.png)

### 🔹 Bronze Layer – Raw Ingestion  
- Direct load of CSV files from CRM and ERP source systems  
- No transformations  
- Acts as the single source of truth

### 🔸 Silver Layer – Cleansing & Standardization  
- Data quality checks  
- Removing inconsistencies  
- Standardizing customer, product, and sales fields  
- Preparing unified datasets

### 🟡 Gold Layer – Business-Ready Models  
- Fact & dimension tables  
- Designed for analytics workloads  
- Supports sales trends, customer behavior, and product performance analysis

---

# 📘 2. Project Purpose  

This repository is part of my learning journey in **Data Engineering and Data Warehousing**.  
The goal is to build a full pipeline from raw files → SQL Server warehouse → analytical datasets → insights.

It demonstrates skills in:

- Data architecture  
- SQL development  
- ETL pipeline design  
- Data modeling  
- Analytics and reporting  

---

# 🧩 3. Project Components  

### 1️⃣ Data Architecture  
- Warehouse built using Bronze, Silver, and Gold layers  
- Schema design and modeling using SQL  

### 2️⃣ ETL Pipelines  
- Ingestion scripts (Bronze)  
- Cleansing + transformation logic (Silver)  
- Dimensional modeling (Gold)  

### 3️⃣ Data Modeling  
- Fact and dimension tables  
- Star schema for analytical queries  

### 4️⃣ Analytics & Reporting  
- SQL queries for insights such as:  
  - Customer behavior patterns  
  - Product performance  
  - Sales trends  

---

# 🛠️ 4. Tools Used  

- **SQL Server Express** – Database engine  
- **SSMS (SQL Server Management Studio)** – Querying & DB management  
- **Draw.io** – Architecture & flow diagrams  
- **GitHub** – Version control  
- **Notion** – Planning and documentation  

---

## 📂 Repository Structure
```
data-warehouse-project/
│
├── datasets/                           # Raw datasets used for the project (ERP and CRM data)
│
├── docs/                               # Project documentation and architecture details
│   ├── etl.drawio                      # Draw.io file shows all different techniquies and methods of ETL
│   ├── data_architecture.drawio        # Draw.io file shows the project's architecture
│   ├── data_catalog.md                 # Catalog of datasets, including field descriptions and metadata
│   ├── data_flow.drawio                # Draw.io file for the data flow diagram
│   ├── data_models.drawio              # Draw.io file for data models (star schema)
│   ├── naming-conventions.md           # Consistent naming guidelines for tables, columns, and files
│
├── scripts/                            # SQL scripts for ETL and transformations
│   ├── bronze/                         # Scripts for extracting and loading raw data
│   ├── silver/                         # Scripts for cleaning and transforming data
│   ├── gold/                           # Scripts for creating analytical models
│
├── tests/                              # Test scripts and quality files
│
├── README.md                           # Project overview and instructions
├── LICENSE                             # License information for the repository
├── .gitignore                          # Files and directories to be ignored by Git

```
---

---

# 📈 6. Requirements & Objectives  

### Data Engineering  
- Load CRM and ERP data into SQL Server  
- Resolve quality issues and standardize formats  
- Create unified business-friendly structures  
- Build fact & dimension tables  
- Document the entire warehouse  

### Analytics  
Deliver insights on:  
- Customer purchasing behavior  
- Top-performing products  
- Sales performance and trends  

More details in `docs/requirements.md` (if added later)

---

# 🙌 7. Acknowledgment  

This project was created **with guidance and inspiration from DataWithBaraa**.  
His explanations, architecture notes, and overall teaching style helped shape how this project was structured and implemented.

Massive respect to him and his content.

---
## 🛡️ License
This project is licensed under the [MIT License](LICENSE). You are free to use, modify, and share this project with proper attribution.


Feel free to connect with me on the following platforms:
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/vishwajeet-padole/)

