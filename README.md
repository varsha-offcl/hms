# hms
Hospital Management System Data Warehouse using Spark (RAW → STAGE → BASE)
# 🏥 Hospital Management System Data Warehouse

This project builds a **Data Warehouse for a Hospital Management System (HMS)** using **Apache Spark** on **Databricks**.

It follows the **Medallion Architecture** pattern with three layers:
- **RAW Layer:** Directly loads the dataset from GitHub.
- **STAGE Layer:** Cleans, transforms, and derives new fields (e.g., `show_flag`, `age_group`, `scheduled_to_visit_days`).
- **BASE Layer:** Aggregates data for analysis (KPIs by department, doctor, weekday).

---

## 📊 Dataset

File: [`appointments.csv`](data/appointments.csv)  
Raw URL (used in Databricks):

