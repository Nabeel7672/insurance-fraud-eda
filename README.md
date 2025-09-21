### Insurance Fraud EDA

#Project Overview
This project performs **Exploratory Data Analysis (EDA)** on an insurance claim fraud dataset sourced from Kaggle.  
The goal is to uncover fraud patterns, detect key indicators, and provide actionable insights to support fraud detection strategies.  

# Dataset
- Source: [Kaggle – EDA on Insurance Claim Fraud Detection](https://www.kaggle.com/code/arpan129/eda-on-insurance-claim-fraud-detection)  
- Contains insurance claims data with attributes such as claim amount, incident type, vehicle details, and fraud labels.  
- Used for data cleaning, pivot analysis, and dashboard creation in this project.  


# Tools Used
- **Microsoft Excel**
  - Data cleaning & preparation  
  - Pivot tables for summarization  
  - Charts and visualizations  
  - Interactive dashboard design  

# Analysis & Key Findings
- **Overall Fraud Prevalence:** 24.7% of total claim value flagged as fraudulent (~$131M out of $546M).  
- **State-wise Fraud:** Ohio had the highest fraud rate (43%), West Virginia the lowest (18%).  
- **Claim Amounts:** Fraudulent claims averaged **$60,302**, higher than non-fraudulent claims (**$50,289**).  
- **Incident Types:** Single vehicle collisions had higher fraud rates (29%) vs. theft or parked car incidents.  
- **Vehicle Brands:** Luxury vehicles (BMW, Mercedes) showed higher fraud rates than mainstream brands (Toyota, Honda).  
- **Police Reports:** Claims without police reports had a higher fraud rate (29.7%) compared to those with reports (25.9%).  

## Dashboard
An interactive Excel dashboard was created featuring:
- Overall Fraud Rate KPI  
- Fraud by Claim Type (Bar Chart)  
- Police Report Analysis (Comparative Chart)  
- Top States by Fraud (Horizontal Bar Chart)  

The dashboard allows quick insights with drill-down capability for deeper analysis.  

## Repository Contents
- `EDA_Insurance_Fraud_Report.pdf` → Full project report  
- `EDA_Insurance_Fraud_Analysis.xlsx` → Excel file (cleaned data, pivot tables, dashboard)  
- `Screenshots/` → Key visuals from analysis and dashboard  

## Recommendations
- Implement stricter verification for **high-value claims** and **single vehicle collisions**.  
- Require **police reports** for all claims to deter fraud.  
- Prioritize monitoring in **high-risk states** and for **luxury vehicles**.  
- Use **dashboards for real-time detection** to improve efficiency and reduce losses.  

---
*This project demonstrates beginner-level data analytics skills using Excel, focusing on fraud detection in the insurance domain.*
