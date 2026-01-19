# uidai-aadhaar-data-insights
### Unlocking Societal Trends in Aadhaar Enrolment, Demographic & Biometric Participation

This repository contains a complete data analysis project built for the **UIDAI Data Hackathon 2026**, focusing on extracting meaningful patterns, trends, anomalies, and predictive indicators from large-scale Aadhaar datasets. The project integrates **Enrolment**, **Demographic**, and **Biometric** datasets to deliver high-impact visual insights and administrative recommendations.

---

## 📌 Project Overview
Aadhaar is the world's largest digital identity ecosystem, and understanding enrolment, demographic behaviour, and biometric performance is essential for system improvement.  
This project performs:
- **Univariate Analysis** (State-wise enrolment, age groups)
- **Bivariate Analysis** (Enrolment vs Biometric)
- **Trivariate Analysis** (Age × Biometric × Total Enrolment)
- **Correlation Heatmaps** for pattern detection  
- **Administrative & Social Impact Assessment**

---

## 📂 Datasets Used
- **Aadhaar Enrolment Dataset**
- **Aadhaar Demographic Dataset**
- **Aadhaar Biometric Dataset**
_All datasets were provided by UIDAI for the hackathon._

Key columns:
- `age_0_5`, `age_5_17`, `age_18_greater`
- `demo_age_5_17`, `demo_age_17_`
- `bio_age_5_17`, `bio_age_17_`

---

## 🧠 Methodology
1. Data Extraction from ZIP files  
2. Cleaning & State-wise Aggregation  
3. Derived Metric Creation  
4. Exploratory Data Analysis (EDA)  
5. Visualisation using Matplotlib  
6. Insights & Recommendations  

---

## 📊 Visualisations Included
- Top 10 States by Enrolment  
- Age Group Distribution Pie Chart  
- Enrolment vs Biometric Scatter Plot  
- Trivariate Bubble Chart  
- Full Correlation Heatmap  

---

## 🧩 Key Insights
- Youth-heavy states show stronger biometric participation  
- Urban regions have higher Aadhaar activity density  
- Age 0–5 shows expected biometric drop  
- Northeastern states show operational anomalies  
- Strong correlation exists between demographic structure and biometric efficiency  

---

## 🛠️ Tech Stack
- **Python**
- **Pandas**
- **Matplotlib**
- **Zipfile**
- **Jupyter Notebook / Google Colab**

---

## 📁 Repository Structure
