# 📊 Data Warehouse and Analytics Project  

Welcome to the **Data Warehouse and Analytics Project repository! 🚀**  
This project demonstrates a comprehensive **data warehousing and analytics solution**, from building a data warehouse to generating actionable insights.  
Designed as a **portfolio project**, it highlights industry best practices in **data engineering and analytics**.  

---

## 🏗️ Data Architecture  

The data architecture for this project follows **Medallion Architecture** with Bronze, Silver, and Gold layers:  

- **Bronze Layer**: Stores raw data as-is from the source systems. Data is ingested from CSV files into SQL Server Database.  
- **Silver Layer**: Data cleansing, standardization, and normalization processes to prepare data for analysis.  
- **Gold Layer**: Houses business-ready data modeled into a **star schema** for reporting and analytics.  

---

## 📖 Project Overview  

This project involves:  

- **Data Architecture**: Designing a Modern Data Warehouse using Medallion layers.  
- **ETL Pipelines**: Extracting, transforming, and loading data from source systems into the warehouse.  
- **Data Modeling**: Developing fact and dimension tables optimized for analytical queries.  
- **Analytics & Reporting**: Creating SQL-based reports and dashboards for actionable insights.  

---

## 🎯 Skills Highlighted  

This repository is an excellent resource to showcase expertise in:  

- SQL Development  
- Data Architecture  
- Data Engineering  
- ETL Pipeline Development  
- Data Modeling  
- Data Analytics  

---

## 🛠️ Tools & Resources  

Everything in this project is **free to use**:  

- **Datasets**: Provided as CSV files.  
- **SQL Server Express**: Lightweight server for hosting your SQL database.  
- **SQL Server Management Studio (SSMS)**: GUI for managing and interacting with databases.  
- **GitHub Repository**: Version control and project collaboration.  
- **Draw.io**: For data architecture, data models, flows, and diagrams.  
- **Notion**: Project template & steps documentation.  

---

## 🚀 Project Requirements  

### 1. Building the Data Warehouse (Data Engineering)  
**Objective**: Develop a modern data warehouse using SQL Server to consolidate sales data for analytical reporting and decision-making.  

**Specifications**:  
- Import data from **ERP** and **CRM** (CSV files).  
- Cleanse and resolve data quality issues.  
- Integrate sources into a single analytical model.  
- Build a **star schema** (fact & dimension tables).  
- Provide clear documentation of the data model.  

---

### 2. BI: Analytics & Reporting (Data Analysis)  
**Objective**: Deliver SQL-based analytics to provide insights into:  

- Customer Behavior  
- Product Performance  
- Sales Trends  

These insights enable **data-driven decision-making** for stakeholders.  

📄 See detailed requirements in: `docs/requirements.md`  

---

## 📂 Repository Structure  

```bash
data-warehouse-project/
│
├── datasets/                           # Raw datasets (ERP and CRM data)
│
├── docs/                               # Project documentation & diagrams
│   ├── etl.drawio                      # ETL techniques & flows
│   ├── data_architecture.drawio        # Project architecture
│   ├── data_catalog.md                 # Dataset catalog & metadata
│   ├── data_flow.drawio                # Data flow diagram
│   ├── data_models.drawio              # Star schema data models
│   ├── naming-conventions.md           # Naming guidelines
│
├── scripts/                            # SQL scripts for ETL & transformations
│   ├── bronze/                         # Raw data ingestion scripts
│   ├── silver/                         # Data cleaning & transformations
│   ├── gold/                           # Star schema & analytics scripts
│
├── tests/                              # Test scripts & data quality checks
│
├── README.md                           # Project overview & instructions
├── LICENSE                             # License information
├── .gitignore                          # Ignored files for Git
└── requirements.txt                    # Project dependencies
````

##🛡️ License

This project is licensed under the MIT License.
You are free to use, modify, and share this project with proper attribution.

---

##🌟 About Me

Hi there! 👋 I’m Mohamed Rabea Mohamed, a passionate Data Analyst & Aspiring Data Engineer.
I enjoy building data pipelines, warehouses, and analytical dashboards that transform raw data into meaningful insights.

🔹 Skills: SQL, Python, ETL, Data Modeling, Tableau, Power BI, and Cloud Data Engineering.
🔹 Background: Computer Science student (Cairo University), Microsoft Certified Data Analyst, and Freelance Data Engineer/Analyst.
🔹 Goal: To leverage data in solving business challenges and create impactful analytics solutions.

---

## Stay Connected
- Mail: mhmdrby769@gmail.com
- Phone: +201070391523
- LinkedIn: https://www.linkedin.com/in/mohamed-rabea-991373261/
