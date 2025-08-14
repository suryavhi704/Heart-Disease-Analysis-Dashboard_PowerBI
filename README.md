# Heart Disease Survival Analysis Dashboard

## 📌 Project Overview
This project analyzes heart disease clinical records to uncover patterns affecting patient survival.  
Using **Power BI**, I developed an interactive dashboard to help healthcare professionals identify high-risk groups and monitor survival trends.

## 🏥 Business Problem
Hospitals often struggle to:
- Identify patient segments with low survival rates.
- Understand how clinical metrics and lifestyle factors impact outcomes.
- Allocate resources efficiently for high-risk patients.

This dashboard addresses these gaps by providing **clear, data-driven insights**.

## 📊 Dataset Details
- **Records:** 299 patients
- **Key Fields:** Age, Gender, Anaemia, Diabetes, Smoking, High Blood Pressure, Ejection Fraction, Serum Creatinine, Serum Sodium, Platelets, CPK Enzyme Levels, Follow-up Time, Death Event.

## ⚙️ Methodology
1. **Data Preparation**:
   - Cleaned and transformed data in Power Query.
   - Created derived fields like Age Groups, EF Bands, Creatinine Bands.
2. **DAX Measures**:
   - Survival Rate, Avg Age of Survivors, Missing Data %, Risk Factor Segments.
3. **Visualization Design**:
   - KPI cards for key stats.
   - Combo charts (Survival vs Clinical Metrics).
   - Sankey diagram for lifestyle/comorbidity impact.
4. **Insights Extraction**:
   - Identified age, EF, and creatinine as strongest survival predictors.

## 💡 Key Insights
- Overall survival rate: **67.89%**, Avg Age of Survivors: **58.76 years**.
- Survival drops sharply for patients aged **71+**.
- EF < 30% and Creatinine > 1.6 mg/dL are high mortality indicators.
- Comorbidities (Diabetes + High BP) drastically reduce survival in older patients.

## 📌 Recommendations
- Prioritize monitoring for high-risk age & EF groups.
- Implement kidney function monitoring for at-risk patients.
- Create targeted care programs for multiple comorbidity groups.

## 🛠️ Tools Used
- **Power BI** for visualization & DAX.
- **Excel** for initial dataset handling.
- **Power Query** for data cleaning.

## 📷 Dashboard Preview
*(Insert dashboard screenshot here)*

## 📂 Repository Structure
- `/data` – Raw Dataset
- `/pbix` – Power BI Report file
- `/images` – Dashboard Screenshots
- `README.md` – Project Documentation
- `Certificate` – Project Certificate by Organization
- - `Project Report` – Project Report Documentation
---
**Author:** [Suryavhi Das]  
**Contact:** [dassuryavhi123@gmail.com] | [www.linkedin.com/in/suryavhi-das-a95094351]
