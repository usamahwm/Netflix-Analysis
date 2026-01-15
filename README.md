# 🎬 Full-Stack Netflix Business Intelligence Pipeline
**Bridging the Gap Between Raw Data and Executive Strategy**

## 📌 Project Overview
This project demonstrates a full-stack data engineering and BI pipeline. It transforms a fragmented Kaggle dataset (8,700+ titles) into a centralized "God View" dashboard. This architecture allows stakeholders to stop "tab-hopping" and see their entire content library’s health in one place.

### 🛠 The Tech Stack
* **Language:** Python (Pandas, NumPy)
* **Database:** MySQL (Relational Storage)
* **Infrastructure:** SQLAlchemy & PyMySQL (ETL Pipeline)
* **Visualization:** Power BI (Interactive Intelligence)

## 🚀 The Data Pipeline

### 1. Extraction & Cleaning (Python)
Raw data is rarely "ready." I utilized Python to:
* Standardize date formats for time-series analysis.
* Handle thousands of missing values to ensure the dashboard reflects the truth.
* Convert text-based durations into numeric integers to calculate averages and growth trends.

### 2. Warehousing (SQL)
Instead of relying on flat files, I engineered a relational database in MySQL. This ensures:
* **Data Integrity:** Validating records before they reach the visual layer.
* **Scalability:** Ready to handle thousands of new data points daily.

### 3. Business Insights (Power BI)
The final "God View" focuses on high-impact metrics:
* **The Cancellation Gap:** Visualizing why 67% of TV shows never make it to Season 2.
* **Global Footprint:** Mapping content distribution across 197 countries.
* **Growth Trends:** Identifying why library expansion peaks in Quarter 3.

## 💡 Business Value
This pipeline isn't just for entertainment data. The same logic applies to **Legal Practices** and **Web Agencies**:
* **Stop the Waste:** Identify which marketing channels are "bouncing" clients.
* **Save Time:** Automate the reporting that usually takes hours of manual work.
* **God View:** See LinkedIn, Meta, and Website traffic in one single, curated window.

---
**Looking to unify your business data?**
I am currently offering a **2-month free trial** of this BI Pipeline service for qualifying businesses. 
[Contact Me via LinkedIn/Email]
