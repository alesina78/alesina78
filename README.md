# Alessandro Lesina Giordano

**Senior Data Engineer & Analytics Specialist**  
*Bridging 25+ years of enterprise data architecture with modern Data Engineering, Analytics and AI*

[![LinkedIn](https://img.shields.io/badge/LinkedIn-alessandrolesina-0077B5?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/alessandrolesina/)
[![Email](https://img.shields.io/badge/Email-giordano.dba@gmail.com-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:giordano.dba@gmail.com)
[![Location](https://img.shields.io/badge/📍_Brazil_·_Portugal_·_Spain-Remote-blue?style=flat-square)](https://www.linkedin.com/in/alessandrolesina/)

---

## About

I am a Senior Data & Integration professional with over 25 years building and operating **mission-critical data systems** across the Financial, Retail, and Industrial sectors.

My foundation is deep Oracle/SQL/PL-SQL enterprise architecture — applied to large-scale environments at **Banco do Brasil (PREVI) · Santander · Sicredi · Walmart · Lojas Renner · Engie**. That foundation now drives my work in **modern Data Engineering**: Medallion pipelines, Analytics Engineering with dbt, Data Quality governance, and AI-assisted development.

What sets me apart: I don't just study these tools — I apply them in **GATE4**, a production SaaS platform I designed and built from scratch for equestrian facility management, covering operations, animal health, finance, inventory and predictive analytics.

> *"I build data systems that actually run in production — not just notebooks."*

---

## 🔭 Currently Building

| What | Where | Status |
|:--|:--|:--|
| **GATE4 Data Platform** — Medallion DW, dbt models, churn prediction pipeline | [`gate4-data-platform`](https://github.com/alesina78/gate4-data-platform) | 🟢 Active |
| **AI Engineering** — Agents, RAG, MCP, Spec-Driven Development | [`FundamentosIA`](https://github.com/alesina78/FundamentosIA) | 🟢 Active |
| **Power BI Portfolio** — DAX, Star Schema, executive dashboards | [`PBI`](https://github.com/alesina78/PBI) | 🟢 Active |
| **Data Science Lab** — EDA, ML, Python studies | [`dsc`](https://github.com/alesina78/dsc) | 🟢 Active |

---

## 🚀 Featured Projects

### 🐎 GATE4 — Intelligent Equestrian Management Platform
> *Proprietary SaaS · Founder & Technical Architect · Live in Production*

**The problem:** Equestrian facilities in Latin America manage horses, students, lessons, health, inventory and finances using spreadsheets and WhatsApp. No integrated system exists for this market.

**What I built:** A fully multi-tenant SaaS platform on Oracle Cloud Infrastructure, covering the complete operational cycle — from lesson scheduling and horse health monitoring to financial management and predictive analytics.

**Data & ML layer:**
- Medallion Data Warehouse (Bronze → Silver → Gold) on PostgreSQL
- Feature store in Python/Pandas feeding a **churn prediction model** (LightGBM)
- **EOQ Intelligent Inventory** — Economic Order Quantity calculation using 12 operational variables, generating supplier purchase orders via WhatsApp API in 1 click
- Executive Power BI dashboard (3 pages, DAX, multi-tenant RLS) integrated with ML output

**Stack:** `Python` · `Django` · `PostgreSQL` · `dbt Core` · `OCI` · `Nginx` · `Tailwind CSS` · `WhatsApp API` · `Power BI`

---

### 🐴 Equine Health Observatory — End-to-End Data Engineering Pipeline
> [`desafio_eng_jr`](https://github.com/alesina78/desafio_eng_jr) · `Completed`

A complete, production-grade data pipeline built on the **UCI Horse Colic** clinical dataset — applying strict software engineering and data quality standards from ingestion to dashboard.

- **Medallion Architecture:** Automated Bronze ingestion → Silver semantic cleaning → Gold analytics via **DuckDB**
- **Data Contracts & Quarantine:** Physiological boundary validation with **Pandera**, traceable quarantine folders and structured `quality_report.json` observability logs
- **Executive Cockpit:** Interactive **Streamlit + Plotly** dashboard — clinical triage zones, surgical decision profiles, real-time pipeline monitoring
- **Testing:** In-memory **Pytest** unit test suite + single-command cross-platform automation (`Python` / `.bat` / `Makefile`)

**Stack:** `Python` · `DuckDB` · `Pandera` · `Pytest` · `Streamlit` · `Plotly` · `SQL` · `Parquet`

---

### ⚡ AI-Driven Python Template
> [`ai-driven-python-template`](https://github.com/alesina78/ai-driven-python-template) · `Active`

Production-ready Python project template structured for AI-assisted development (Claude/Cursor), clean architecture, automated testing and Streamlit dashboards. Built for reuse across data and ML projects.

---

## 🛠️ Tech Stack

### Data Engineering & Analytics
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![dbt](https://img.shields.io/badge/dbt-FF694B?style=flat-square&logo=dbt&logoColor=white)
![DuckDB](https://img.shields.io/badge/DuckDB-FFF000?style=flat-square&logo=duckdb&logoColor=black)
![Pandera](https://img.shields.io/badge/Pandera-2E8B57?style=flat-square&logo=python&logoColor=white)
![Pytest](https://img.shields.io/badge/Pytest-0A9EDC?style=flat-square&logo=pytest&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)
![Plotly](https://img.shields.io/badge/Plotly-3F4F75?style=flat-square&logo=plotly&logoColor=white)
![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=flat-square&logo=powerbi&logoColor=black)

### Databases & Cloud
![Oracle](https://img.shields.io/badge/Oracle_Database-F80000?style=flat-square&logo=oracle&logoColor=white)
![PL/SQL](https://img.shields.io/badge/PL%2FSQL-F80000?style=flat-square&logo=oracle&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![SQL Server](https://img.shields.io/badge/SQL_Server-CC292B?style=flat-square&logo=microsoftsqlserver&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=flat-square&logo=supabase&logoColor=white)
![OCI](https://img.shields.io/badge/Oracle_Cloud-F80000?style=flat-square&logo=oracle&logoColor=white)

### Enterprise Integration & ETL
![Oracle ODI](https://img.shields.io/badge/Oracle_ODI-F80000?style=flat-square&logo=oracle&logoColor=white)
![Pentaho](https://img.shields.io/badge/Pentaho_PDI-0E5A8A?style=flat-square&logo=hitachivantara&logoColor=white)
![Oracle APEX](https://img.shields.io/badge/Oracle_APEX-F80000?style=flat-square&logo=oracle&logoColor=white)
![Oracle Forms](https://img.shields.io/badge/Oracle_Forms_6i–14c-F80000?style=flat-square&logo=oracle&logoColor=white)
![REST APIs](https://img.shields.io/badge/REST_APIs-0055E5?style=flat-square&logo=json&logoColor=white)

### AI & LLMs
![LLM Agents](https://img.shields.io/badge/AI_Agents-000000?style=flat-square&logo=openai&logoColor=white)
![RAG](https://img.shields.io/badge/RAG-412991?style=flat-square)
![MCP](https://img.shields.io/badge/MCP-412991?style=flat-square)
![Prompt Engineering](https://img.shields.io/badge/Prompt_Engineering-412991?style=flat-square)

### Infrastructure & DevOps
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/Linux_Ubuntu-FCC624?style=flat-square&logo=linux&logoColor=black)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![Django](https://img.shields.io/badge/Django-092E20?style=flat-square&logo=django&logoColor=white)

---

## 📂 Repository Map

| Repository | Focus | Status |
|:---|:---|:---:|
| 🐴 [**desafio_eng_jr**](https://github.com/alesina78/desafio_eng_jr) | End-to-End Medallion Pipeline · Pandera contracts · DuckDB · Pytest · Streamlit cockpit | `Completed` |
| 🏗️ [**gate4-data-platform**](https://github.com/alesina78/gate4-data-platform) | Data Engineering · dbt · Dimensional DW · ETL pipelines · Feature Store · Churn model | `Active` |
| 🤖 [**FundamentosIA**](https://github.com/alesina78/FundamentosIA) | AI Agents · RAG · MCP · Prompt Engineering · Tool Use · Spec-Driven Development | `Active` |
| ⚡ [**ai-driven-python-template**](https://github.com/alesina78/ai-driven-python-template) | Production Python template · AI-assisted dev · Clean architecture · Streamlit | `Active` |
| 📊 [**PBI**](https://github.com/alesina78/PBI) | Power BI · DAX · Star Schema · Dimensional modeling · Executive dashboards | `Active` |
| 🔬 [**dsc**](https://github.com/alesina78/dsc) | Data Science lab · EDA · Machine Learning · Python | `Active` |

---

## 🎓 Education & Certifications

**In Progress**
- Postgraduate — Data Engineering & AI *(Anhanguera · expected Nov/2027)*

**Completed Postgraduate & MBA**
- MBA in Data Science · MBA in Business Intelligence · Big Data & Data Science · Big Data & Cloud Computing · Artificial Intelligence — *FACPRISMA (640–720h each)*
- Technologist in Systems Analysis & Development — *Universidade Feevale, 2024*

**Certification**
- Oracle Certified: Introduction to Oracle9i SQL — Exam 1Z0-007 *(OCA track)*

---

## 📫 Open to Opportunities

Available for **Data Engineering · Analytics Engineering · Database Engineering · AI/LLM Integration** roles in **Brazil, Portugal, and Spain** — remote, hybrid or on-site.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Let's_Connect-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/alessandrolesina/)
[![Email](https://img.shields.io/badge/Email-Get_in_Touch-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:giordano.dba@gmail.com)