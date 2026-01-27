# 🚀 ChurnGuard: End-to-End Data Engineering & Predictive Pipeline

Winning a customer is hard; keeping them is harder. In the hyper-competitive telecom industry, customer attrition (churn) is the ultimate metric for success.

This project is a mid-level, production-ready pipeline designed to ingest, process, and analyze customer behavior to predict and mitigate churn. It transitions from raw data to a cloud-based SQL infrastructure, concluding with automated insights and machine learning.

##🛠️ The Tech Stack
* Language: Python 3.x

*Data ingestion: Kaggle API (Automated)

* Engineering & ETL: Pandas, Pathlib (Dynamic file discovery)

* Database: PostgreSQL (Cloud-native via Neon.tech)

* OR/M: SQLAlchemy

* Analysis: ydata-profiling (Automated EDA)

* Environment: Google Colab & GitHub (Version Control)

##🏗️ Project Architecture
The pipeline is built on four robust pillars:
1. Automated data ingestion: Direct retrieval from Kaggle's API into a structured environment, ensuring data freshness and reproducibility.

2. Dynamic ETL & cleaning: A flexible preprocessing script using pathlib that handles dynamic filenames, standardizes schema to snake_case, and performs critical data-type casting (e.g., addressing the infamous TotalCharges string-to-float issue).

3. Cloud-native storage: Cleaned data is injected into a serverless PostgreSQL instance on Neon.tech, creating a "Source of Truth" for downstream analytics.

4. Automated EDA: Generation of comprehensive, interactive HTML reports to identify key churn drivers like contract types, payment methods, and tenure correlations.

📈 Key insights (Ongoing)

* Coming soon: Identification of top 3 churn risk factors.

* Coming soon: Predictive model performance metrics (F1-Score, Recall).
