<div align="center">

# 👋 Hey, I'm Naveen Kumar K

### Data Engineer | Big Data | Real-Time Streaming | AWS | ETL | AL/LLM

<p>
  <a href="https://github.com/naveenkumark2830-spec">
    <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"/>
  </a>
  <a href="mailto:naveenkumark2830@gmail.com">
    <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/>
  </a>
  <a href="https://www.linkedin.com/">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/>
  </a>
</p>

<img
src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=20&duration=2800&pause=900&color=36BCF7&center=true&vCenter=true&width=750&lines=Data+Engineer;Real-Time+Data+Pipeline+Builder;Apache+Spark+%7C+Kafka+%7C+Airflow;AWS+%7C+Data+Lake+%7C+Lakehouse;Python+%7C+SQL+%7C+Big+Data;AI+%26+LLM+Engineering"
alt="Typing SVG"
/>

</div>

---

## 👨‍💻 About Me

I'm **Naveen Kumar K**, a passionate **Data Engineer** focused on building scalable data pipelines, real-time streaming systems, cloud data platforms, and AI-powered applications.

I enjoy working across the complete data engineering lifecycle:

```text
Raw Data
   ↓
Ingestion
   ↓
Streaming / Batch Processing
   ↓
Data Validation & Transformation
   ↓
Data Lake / Lakehouse
   ↓
Data Warehouse
   ↓
Analytics & BI
   ↓
Business Insights
```

### What I work with

* ⚡ Real-time data engineering
* 🔥 Apache Spark & PySpark
* 📨 Apache Kafka
* 🌬️ Apache Airflow
* ☁️ AWS Data Engineering
* 🏞️ Data Lakes & Lakehouse Architecture
* 🧱 Delta Lake & Medallion Architecture
* 📊 Data Warehousing & BI
* 🤖 RAG, NLP & LLM applications
* 🐍 Python & SQL

> **Build reliable pipelines. Transform data. Create systems that solve real problems.**

---

# 🛠️ Technical Stack

## 👨‍💻 Programming & Data

<p align="left">

<a href="https://www.python.org/">
<img src="https://skillicons.dev/icons?i=python" height="50" alt="Python"/>
</a>

<a href="https://www.mysql.com/">
<img src="https://skillicons.dev/icons?i=mysql" height="50" alt="MySQL"/>
</a>

</p>

**Python • Pandas • NumPy • SQL • PL/SQL**

---

## ⚡ Big Data & Streaming

<p align="left">

<img src="https://skillicons.dev/icons?i=kafka" height="50" alt="Apache Kafka"/>
<img src="https://skillicons.dev/icons?i=spark" height="50" alt="Apache Spark"/>

</p>

**Hadoop • HDFS • Hive • Apache Spark • PySpark • Spark Structured Streaming • Kafka • Airflow • Databricks**

---

## ☁️ AWS Cloud

<p align="left">

<img src="https://skillicons.dev/icons?i=aws" height="50" alt="AWS"/>

</p>

**EC2 • S3 • VPC • Redshift • Athena • Glue • EMR • Lambda • RDS • DynamoDB • EKS • IAM • CloudWatch**

---

## 🏞️ Data Architecture

<p align="left">

<img src="https://img.shields.io/badge/Data%20Lake-2E86C1?style=for-the-badge" alt="Data Lake"/>
<img src="https://img.shields.io/badge/Lakehouse-6C5CE7?style=for-the-badge" alt="Lakehouse"/>
<img src="https://img.shields.io/badge/Delta%20Lake-0F6CBD?style=for-the-badge" alt="Delta Lake"/>
<img src="https://img.shields.io/badge/ETL%20%2F%20ELT-34495E?style=for-the-badge" alt="ETL ELT"/>

</p>

**Data Warehouse • Data Lake • Lakehouse • Delta Lake • ETL/ELT • Star Schema • Snowflake Schema • Fact & Dimension Tables**

---

## 🐳 DevOps & Engineering

<p align="left">

<img src="https://skillicons.dev/icons?i=linux,docker,kubernetes,git,github,vscode" height="50" alt="DevOps Tools"/>

</p>

**Linux • Docker • Kubernetes • Git • GitHub • VS Code**

---

## 🤖 AI / ML / LLM

<p align="left">

<img src="https://skillicons.dev/icons?i=python" height="50" alt="Python"/>

<img src="https://img.shields.io/badge/FAISS-00A98F?style=for-the-badge" alt="FAISS"/>
<img src="https://img.shields.io/badge/RAG-7B61FF?style=for-the-badge" alt="RAG"/>
<img src="https://img.shields.io/badge/LLM-111827?style=for-the-badge" alt="LLM"/>

</p>

**Machine Learning • NLP • Embeddings • RAG • MCP • Vector Databases • LightGBM • SHAP • FAISS • Sentence Transformers**

---

# 🚀 Featured Projects

## 🏭 Production-Grade Event-Driven Data Lakehouse on AWS

**Kafka • Spark • PySpark • Airflow • AWS • S3 • Delta Lake • Athena • Glue • Power BI • Terraform • Docker**

A production-oriented real-time e-commerce data platform designed around an event-driven architecture.

### 🔥 Key Engineering Features

* ⚡ Real-time e-commerce event generation
* 📨 Kafka → Spark Structured Streaming
* 🔍 Data validation & schema handling
* 💧 Watermarking & late-data handling
* ♻️ Deduplication & incremental processing
* 📌 Checkpointing for fault tolerance
* 🪟 Window-based streaming analytics
* 🥉 Bronze → Silver → Gold architecture
* 🏞️ Delta Lake on Amazon S3
* 🌬️ Airflow orchestration
* 🔎 Athena analytics
* 📊 Power BI dashboards
* 🐳 Docker deployment
* 🏗️ Terraform infrastructure

### Architecture

```text
                    E-COMMERCE EVENTS
                           │
                           ▼
                        KAFKA
                           │
                           ▼
              SPARK STRUCTURED STREAMING
                           │
              ┌────────────┴────────────┐
              ▼                         │
        BRONZE LAYER                    │
              │                         │
              ▼                         │
        SILVER LAYER                    │
              │                         │
              ▼                         │
         GOLD LAYER                     │
              │                         │
        ┌─────┴──────┐                  │
        ▼            ▼                  │
     ATHENA       POWER BI              │
                                         │
              AIRFLOW → ORCHESTRATION    │
              AWS S3  → DATA LAKE        │
              DOCKER  → DEPLOYMENT       │
              TERRAFORM → INFRASTRUCTURE │
```

---

# ⚡ On-Premise Real-Time Retail Data Platform

**Kafka • PySpark • Spark Structured Streaming • Delta Lake • Docker • Power BI**

Built a real-time retail data platform for continuous event ingestion, processing, validation, and analytics.

### Key Features

* 📨 Kafka-based real-time order ingestion
* ⚡ Spark Structured Streaming
* 📌 Checkpointing
* 🔄 Incremental processing
* 🥉 Bronze → Silver → Gold architecture
* 🔍 Data validation
* ♻️ Deduplication
* 🧹 Data cleansing
* 🔧 Business transformations

### Gold Data Marts

| Domain        | Analytics            |
| ------------- | -------------------- |
| 💰 Revenue    | Revenue metrics      |
| 📦 Orders     | Order analytics      |
| 💳 Payments   | Payment analytics    |
| 🛍️ Products  | Product performance  |
| 🌎 States     | Geographic analytics |
| 📊 Operations | Operational KPIs     |

---

# 🤖 LLM Ranking System

**Python • LightGBM • SHAP • NLP • Embeddings**

Built an intelligent ranking system for evaluating and selecting high-quality LLM responses.

### Highlights

* 🧠 LightGBM ranking model
* ⚙️ 10+ engineered evaluation features
* 📝 Prompt classification
* 🔎 NLP & embedding-based features
* 📊 SHAP model explainability
* 🔍 Transparent ranking decisions
* 🖍️ Keyword highlighting
* 🤖 Automated best-response selection

---

# 🌍 Global Terrorism Analysis — 1970–2021

**Python • Pandas • Scikit-learn • Cartopy**

Analyzed a large-scale global terrorism dataset to identify historical patterns, geographic hotspots, and attack trends.

### Highlights

* 📊 214K+ terrorism records analyzed
* 🧹 198,280-row analysis-ready dataset
* 🌎 Geospatial visualization
* 📈 Historical trend analysis
* 🔎 Regional hotspot identification
* 🧠 Attack-pattern analysis

---

# 💼 Experience

## AI/ML Intern — ComedKares Innovation Hub

**May 2026 – June 2026 | Bengaluru**

Worked on an AI-powered government scheme recommendation system using Retrieval Augmented Generation.

### Contributions

* 🤖 Built an AI-powered government scheme recommendation system
* 🔎 Implemented semantic search using **Sentence Transformers + FAISS**
* 🧠 Integrated **Groq Llama 3** for context-aware responses
* ⚡ Developed a **FastAPI** backend
* 🔗 Designed scalable API communication

---

# 🎓 Education

### St. Joseph's University — Bengaluru

**M.Sc. in Big Data Analytics**
2025 – 2027 *(Expected)*

**SGPA: 8.71**

### St. Joseph's University — Bengaluru

**BCA in Data Analytics**
2022 – 2025

**CGPA: 8.7**

---

# 🧠 Data Engineering Focus

```text
                    DATA ENGINEERING
                           │
       ┌───────────────────┼───────────────────┐
       │                   │                   │
       ▼                   ▼                   ▼
     INGESTION          PROCESSING          STORAGE
       │                   │                   │
     Kafka              Spark/PySpark       S3
       │                   │                   │
       ▼                   ▼                   ▼
   Streaming          Transformations      Delta Lake
       │                   │                   │
       └───────────────────┼───────────────────┘
                           │
                           ▼
                    ORCHESTRATION
                           │
                        Airflow
                           │
                           ▼
                      ANALYTICS
                           │
                    Athena / Power BI
```

---

# 📈 Currently Learning

* 🔥 Advanced Apache Spark
* 📨 Advanced Kafka
* 🌬️ Apache Airflow
* ☁️ AWS Data Engineering
* 🏞️ Lakehouse Architecture
* 🧱 Delta Lake
* 🐳 Docker & Kubernetes
* 🏗️ Terraform
* 🤖 RAG & LLM Systems
* 🔌 MCP & AI Agents
* 📊 Advanced Data Warehousing

---

# 🌱 Leadership

### President — National Service Scheme (NSS)

**2024 – 2025**

* Led **50+ volunteers**
* Organized multiple outreach initiatives
* Managed a successful **7-day rural camp**

### First Coordinator — MetaMinds 1.0

**2025 – 2026**

* Managed a **2-day inter-collegiate fest**
* Coordinated cross-functional teams
* Managed an event with **1,200+ participants**

---

# 📊 GitHub

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=naveenkumark2830-spec&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" height="165" alt="GitHub Stats"/>

<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=naveenkumark2830-spec&layout=compact&theme=tokyonight&hide_border=true" height="165" alt="Top Languages"/>

</div>

---

# 🐍 Contribution Snake

<div align="center">

<picture>

<source
media="(prefers-color-scheme: dark)"
srcset="https://raw.githubusercontent.com/naveenkumark2830-spec/naveenkumark2830-spec/output/github-contribution-grid-snake-dark.svg">

<source
media="(prefers-color-scheme: light)"
srcset="https://raw.githubusercontent.com/naveenkumark2830-spec/naveenkumark2830-spec/output/github-contribution-grid-snake.svg">

<img
src="https://raw.githubusercontent.com/naveenkumark2830-spec/naveenkumark2830-spec/output/github-contribution-grid-snake.svg"
width="90%"
alt="GitHub Contribution Snake">

</picture>

</div>

---

# 🤝 Let's Connect

<div align="center">

### Interested in Data Engineering, Big Data, Cloud, Real-Time Systems or AI?

**Let's build something meaningful.**

<p>

<a href="https://github.com/naveenkumark2830-spec">
<img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"/>
</a>

<a href="mailto:naveenkumark2830@gmail.com">
<img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/>
</a>

</p>

### ⚡ Data → Systems → Insights → Impact

<sub>© Naveen Kumar K · Data Engineer · Big Data · Cloud · AI/LLM</sub>

</div>
