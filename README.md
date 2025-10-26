📘 Project Overview
This project is part of an Excel Capstone Project focused on analyzing healthcare data to uncover insights about BMI, HBA1C, age, and medical charges.
The dataset combines information from multiple sources — Customer Details, Medical Examinations, and Hospitalisation Records — to explore health patterns and relationships between patient attributes.
🎯 Objectives
Clean and transform raw healthcare datasets.
Derive Weight Status (from BMI) and Diabetes Status (from HBA1C).
Calculate Age and format Date of Birth.
Analyze relationships between age, BMI, HBA1C, and healthcare charges.
Generate visual insights and summaries for better interpretation.
🧩 Dataset Components
Customer Names: Customer ID and full name.
Medical Examinations: BMI, HBA1C, Heart Issues, Transplants, Cancer History, Surgeries, Smoker status.
Hospitalisation Details: Year, Month, Date of Birth, Charges, Hospital Tier, City Tier, and State ID.
🧹 Data Cleaning & Transformation
Replaced missing “?” values with blanks or appropriate substitutes.
Filled missing fields using averages or most frequent values:
Month → Sep
Year → 1983
Smoker → No
Hospital Tier → tier - 2
City Tier → tier - 2
State ID → Unknown
Derived:
Weight Status from BMI
Diabetes Status from HBA1C
Date of Birth (formatted as DD-MMM-YYYY)
Age (as of 8 June 2023)
Converted and formatted numeric values (e.g., charges in currency).
📊 Key Analyses and Visuals
Cancer History vs Smoking Status — Pie charts
Transplant History vs Surgeries & HBA1C — Bar + Line chart
Average Charges by Weight Status & Diabetes Status — Bar charts
Charges by State & Hospital Tier — Grouped bar chart
Age vs BMI and HBA1C — Scatterplots
Age vs Charges — Scatter + Trendline
💡 Insights Summary
BMI vs Age
Average BMI (30–33) indicates obesity across all age groups (18–65).
No major trend — BMI remains consistent across ages.
Slight dip at age 65 (BMI ≈ 26.89) due to fewer data points.
HBA1C vs Age
Two main clusters:
5.0–5.5: Normal / Prediabetic
8.7–9.8: Poor diabetes control
High HbA1C appears at all ages, including young adults (20–40 years).
Indicates chronic diabetes across all age groups, not only older individuals.
📂 Deliverables
Healthcare_Combined_Cleaned.xlsx — Final merged dataset.
Charts (PNG):
cancer_by_smoker_pies.png
surg_and_hba1c_by_transplant.png
charges_by_weight.png
charges_by_diabetes.png
avg_charges_state_hospital_tier_top_states.png
age_vs_bmi_hba1c.png
age_vs_charges.png
Summary CSVs:
surg_hba1c_by_transplant.csv
avg_charges_by_state_hospital_tier.csv
🧠 Key Takeaways
Obesity is consistent across all ages.
Diabetes prevalence spans both young and old populations.
Medical charges rise with higher BMI and diabetes levels.
Transplant patients show lower average HBA1C but higher surgery counts.
Data-driven insights can support early detection and preventive health strategies.
⚙ Tools Used
Microsoft Excel (Data Cleaning, Transformation)
Power BI(Data Visualization and Analysis )
📅 Author & Credits
Author: Malathy Padmanabhan

Location: Chennai

Year: 2025
