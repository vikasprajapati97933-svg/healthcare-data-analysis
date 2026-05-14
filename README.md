# 🏥 Healthcare Data Analysis
## 🚀 Data Cleaning & Exploratory Data Analysis (EDA) using Python

---

## 📖 Project Overview

Raw healthcare data is often inconsistent and unstructured, leading to unreliable insights. This project demonstrates a complete **data cleaning and exploratory analysis pipeline** using Python to transform raw healthcare records into meaningful and actionable insights.

💡 The focus is on improving **data quality, patient understanding, and financial analysis.**

---

## 🎯 Key Objectives

- 🧹 Clean and standardize inconsistent patient records
- 🔄 Convert raw data into analysis-ready format
- 📊 Perform exploratory data analysis (EDA)
- 💊 Identify trends in medical conditions & medication usage
- 💰 Analyze billing patterns and financial impact
- 📈 Visualize insights using statistical charts

---

## 📊 Dataset Summary

| Detail | Info |
| ----------- | --------------------- |
| 📁 Dataset | Healthcare Dataset.csv |
| 📌 Records | 55,500+ patients |
| 📌 Features | 15 columns |

### 🔹 Data Categories

| Category | Columns |
| ------------- | ----------------------------------------------- |
| 👥 Demographics | Name, Age, Gender, Blood Type |
| 🏥 Clinical Info | Medical Condition, Doctor, Hospital, Test Results |
| 💰 Financials | Insurance Provider, Billing Amount |
| 🚑 Logistics | Admission Type, Admission Date, Discharge Date, Room Number |

---

## 🛠️ Tech Stack

| Tool | Purpose |
| ---------- | ------------------------- |
| Python | Data Cleaning & Analysis |
| Pandas | Data Manipulation |
| Matplotlib | Data Visualization |
| Seaborn | Statistical Visualization |

---

## 🧹 Data Cleaning Process

- 🗑️ Removed **534 duplicate records**
- 🔤 Standardized text data:
  - Converted names to **Title Case**
  - Cleaned column names (lowercase + underscores)
- 📅 Converted date columns to datetime format:
  - `date_of_admission`
  - `discharge_date`
- 🔍 Checked for missing values to ensure data quality

---

## 📊 Key KPIs

| Metric | Value |
| ----------------------- | ------- |
| 👥 Total Patients | 55,500+ |
| 👨 Male Patients | 27,496 |
| 👩 Female Patients | 27,470 |
| 💰 Avg Billing per Patient | ~$25,539 |

---

## 🔍 Key Insights

### 👥 Patient Demographics
- Gender distribution is **almost equal:**
  - 👨 Male: **27,496**
  - 👩 Female: **27,470**
- Majority of patients fall in the **50–65 age group**

### 💊 Medical & Medication Analysis

| Condition | Most Used Medication | Frequency |
| ------------ | -------------------- | --------- |
| Arthritis | Aspirin | 1,918 |
| Asthma | Paracetamol | 1,888 |
| Cancer | Lipitor | 1,922 |
| Diabetes | Lipitor | 1,893 |
| Hypertension | Ibuprofen | 1,893 |
| Obesity | Penicillin | 1,893 |

### 💰 Financial Insights
- Average billing per patient: **~$25,539**
- Patients with **Obesity** tend to have higher billing amounts

---

## 📈 Visualizations

The project includes multiple visual insights:

- 🔥 **Heatmaps** → Condition vs Medication correlation
- 📉 **Histograms** → Age & billing distribution

<img width="580" height="491" alt="Visualization 1" src="https://github.com/user-attachments/assets/8a428c3e-64ea-49f8-beae-f93e85299d53" />

<img width="589" height="455" alt="Visualization 2" src="https://github.com/user-attachments/assets/7242b112-60ab-48a3-b8d9-fbd65a852fca" />

<img width="627" height="455" alt="Visualization 3" src="https://github.com/user-attachments/assets/fd5fa355-8a93-4823-b1c4-f6f6248dcf09" />

<img width="869" height="547" alt="Visualization 4" src="https://github.com/user-attachments/assets/c8c1da6b-56ff-4898-b70f-aee522aefc48" />

<img width="580" height="455" alt="Visualization 5" src="https://github.com/user-attachments/assets/54a6a283-fdbc-4dfe-aea0-252c56f58d47" />

---

## 📁 Project Structure

```
📦 healthcare-data-analysis
 ┣ 📁 data/
 ┃  ┗ 📄 healthcare_dataset.csv
 ┣ 📁 notebooks/
 ┃  ┗ 📜 data_cleaning_eda.ipynb
 ┣ 📁 visualizations/
 ┃  ┗ 📊 charts/
 ┗ 📄 README.md
```

---

## 🚀 How to Run

```bash
# 1. Clone the repository
git clone https://github.com/sunitaprajapati6561-hue/healthcare-data-analysis

# 2. Install dependencies
pip install pandas matplotlib seaborn

# 3. Run the notebook
jupyter notebook notebooks/data_cleaning_eda.ipynb
```

---

## 🧠 Key Learnings

- Data cleaning is **critical** in healthcare analytics
- Small inconsistencies can lead to **misleading conclusions**
- EDA helps uncover **hidden patient and financial patterns**
- Visualization improves **decision-making clarity**

---

## 🏁 Conclusion

This project highlights the importance of transforming raw healthcare data into structured insights. By applying proper data cleaning and EDA techniques, we gained a clearer understanding of:

- 👥 Patient demographics
- 💊 Medication trends
- 💰 Financial patterns

---

## 🧑‍💻 Author

**Vikas Prajapati**
📌 Aspiring Data Analyst
📌 Python | SQL | Power BI | Excel

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/vikas-prajapati-0ba9302ba/)
[![Gmail](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:sunitaprajapati6561@gmail.com)

