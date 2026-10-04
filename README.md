# 🧬 Cancer Data Analysis Dashboard (Power BI)

An interactive, multi-page Power BI dashboard that analyzes a global dataset of
**50,000 cancer patients** across 10 countries and 8 cancer types. It explores how
survival, treatment cost, and lifestyle and genetic risk factors vary by cancer
type, stage, year, and region.

## 📌 Project Overview
The goal of this project is to turn raw patient records into clear, actionable
insights. The dashboard helps users spot patterns in survival outcomes, understand
treatment cost trends, and compare risk factors across countries.

## 📊 Dashboard Pages

### 1. Global Overview
- KPI cards: Total Patients (50K), Total Treatment Cost (2.62bn), Average Survival Years (5.01), Severity Score vs. Goal
- Average survival years by cancer type (pie chart)
- Survival years by cancer stage (Stage 0 to IV)
- Survival years vs. smoking trend by year
- Treatment cost by year and cancer type (ribbon chart)
- Cancer type slicer for dynamic filtering

### 2. Country Comparison: China vs. India
- Patient counts per country (China: 4,913 | India: 5,040)
- Survival years and severity score by year (combo chart)
- Treatment cost and genetic risk trends by year
- Survival years vs. alcohol use (bubble/scatter plot)
- Slicers for cancer stage and cancer type

### 3. Geographic and Risk Factor Analysis
- Map of average survival by country
- Waterfall chart of year-over-year treatment cost by cancer stage
- Country-level table: air pollution, alcohol use, smoking, genetic risk, obesity level, and average survival years

## 🔍 Key Insights
- Average survival is nearly uniform across cancer types (~5 years), each contributing ~12.5%
- Survival years and smoking levels follow a similar trend over 2015 to 2024
- Treatment cost stays fairly consistent year over year, with notable shifts between stages
- Average survival ranges from **4.93 years (China)** to **5.06 years (UK and USA)**

## 🛠️ Tools & Techniques
- **Power BI Desktop**: data modeling, DAX measures, interactive visuals
- Slicers, drill-downs, cross-filtering, KPI cards, map visuals
- Data cleaning and preparation (Power Query / Python: Pandas, NumPy)

## 📁 Repository Structure
├── cancer_dashboard_dipti.pbix # Power BI dashboard file
├── global_cancer_patients_2015_2026.csv # Dataset (CSV)
├── cancer_dashboard_pdf_file.pdf # Dashboard preview images
└── README.md
