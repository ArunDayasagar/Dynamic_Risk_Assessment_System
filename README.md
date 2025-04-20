# Dynamic_Risk_Assessment_System

# 🛡️ Dynamic Risk Assessment System

This project is part of the **ML DevOps Engineer Nanodegree by Udacity** under **Unit 5: Model Scoring and Monitoring**.  
It automates the process of risk assessment using a Machine Learning model and includes monitoring, reporting, re-deployment, and re-training pipelines.

## 📌 Project Objective

Build a system that estimates the attrition risk of each client and supports:
- Model training and scoring
- Model evaluation and diagnostics
- Model reporting and deployment
- Automated pipeline execution
- Streamlit-based user interface for interaction

---

## 🏗️ Project Structure

```bash
📦Dynamic-Risk-Assessment-System
 ┣ 📂data
 ┃ ┣ 📂ingesteddata
 ┃ ┣ 📂practicedata
 ┃ ┣ 📂sourcedata
 ┃ ┗ 📂testdata
 ┣ 📂model
 ┃ ┣ 📂models
 ┃ ┣ 📂practicemodels
 ┃ ┗ 📂production_deployment
 ┣ 📂src
 ┃ ┣ ingestion.py
 ┃ ┣ training.py
 ┃ ┣ scoring.py
 ┃ ┣ diagnostics.py
 ┃ ┣ reporting.py
 ┃ ┣ deployment.py
 ┃ ┣ fullprocess.py
 ┃ ┗ streamlit_app.py
 ┣ 📜config.json
 ┣ 📜requirements.txt
┗ 📜README.md
