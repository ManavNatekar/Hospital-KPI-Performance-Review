
# 🏥 Hospital KPI Performance Review
### End-to-End Data Analytics Project | Python | Pandas | NumPy | Excel | Data Visualization

![Project](https://img.shields.io/badge/Project-Hospital%20KPI%20Analysis-orange)
![Python](https://img.shields.io/badge/Python-3.x-blue)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-purple)
![Dataset](https://img.shields.io/badge/Dataset-500K%20Records-green)
![Status](https://img.shields.io/badge/Status-Completed-success)

---

## 📌 1. Project Overview

The **Hospital KPI Performance Review** is an end-to-end Data Analytics project designed to evaluate the operational performance of a fictional Mumbai-based multi-specialty hospital group consisting of four hospitals.

The project focuses on transforming large, inconsistent and unstructured hospital datasets into meaningful, reliable and actionable business insights that can help hospital management make informed decisions.

The analysis uses **500,000 synthetically generated records** covering January 2024 to December 2025.

The project involves data profiling, data cleaning, data transformation, KPI calculation, exploratory data analysis, performance comparison, cohort analysis, financial impact estimation and data visualization.

> **Data Disclaimer:** All hospital names, patient records, doctors and transactions are fictional and synthetically generated for educational and portfolio purposes. No real patient or hospital data has been used.

---

## 🎯 2. Project Objectives

The major objectives of this project are:

- Clean and standardize large hospital datasets.
- Identify and resolve missing values and inconsistent data formats.
- Create a trusted hospital admissions analysis table.
- Calculate important hospital operational KPIs.
- Compare performance across four hospitals.
- Analyze performance by department, doctor and patient cohort.
- Identify top and bottom-performing segments.
- Develop meaningful visualizations and an Excel KPI dashboard.
- Estimate potential financial and operational improvements.
- Provide data-driven recommendations to hospital management.

---

## 📊 3. Dataset Information

The project contains 500,000 records distributed across four datasets.

| Dataset | Number of Records |
|---|---:|
| OPD Visits | 240,000 |
| Hospital Admissions | 80,000 |
| Laboratory Tests | 130,000 |
| Billing Records | 50,000 |
| **Total** | **500,000** |

### Data Coverage

- Number of Hospitals: 4
- Geographic Context: Mumbai, India
- Reporting Period: January 2024 – December 2025
- Total Records: 500,000
- Data Type: Synthetic

### Data Quality Challenges

The datasets contain realistic data quality issues, including:

- Missing discharge dates.
- Inconsistent diagnosis descriptions.
- Age values stored in different formats.
- Missing laboratory test results.
- Incorrect billing entries.
- Missing billing amounts.
- Inconsistent data formats.

---

## 🧹 4. Data Cleaning and Preparation

Python and Pandas were used to perform data cleaning and transformation.

The following activities were performed:

1. Data profiling of all available columns.
2. Identification of missing values and inconsistent entries.
3. Standardization of diagnosis descriptions.
4. Conversion of date-of-birth values into age in years.
5. Imputation of missing discharge dates using department-level median length of stay.
6. Handling missing laboratory results.
7. Correction of incorrect billing amounts.
8. Creation of a detailed record-level cleaning log.
9. Creation of a trusted admissions analysis table.

A cleaning log was maintained to document the affected records, columns, identified issues and corrective actions.

**Cleaning Log Entries:** 277,992

All four source datasets retain their original row counts after cleaning.

---

## 📈 5. Key Performance Indicators (KPIs)

Three major hospital performance indicators were calculated.

### 1. Average Length of Stay (ALOS)

Measures the average number of days a patient stays in the hospital.

Purpose:
- Evaluate hospital efficiency.
- Monitor patient discharge patterns.
- Identify departments with prolonged stays.

### 2. Bed Occupancy Rate

Measures the percentage of available bed-days occupied by patients.

Purpose:
- Evaluate hospital capacity utilization.
- Support bed management decisions.
- Identify potential capacity constraints.

### 3. 30-Day Readmission Rate

Measures the percentage of admissions followed by another admission for the same patient within 30 days after discharge.

Purpose:
- Identify repeat hospital utilization.
- Support post-discharge follow-up planning.
- Highlight opportunities for better care coordination.

**Note:** The readmission metric is a simplified, unadjusted operational proxy and should not be interpreted as a risk-adjusted clinical quality measure.

---

## 📊 6. Key Analytical Findings

The overall analysis generated the following results:

| KPI | Overall Result |
|---|---:|
| Average Length of Stay | 4.30 Days |
| Bed Occupancy Rate | 62.44% |
| 30-Day Readmission Proxy | 8.86% |

### Illustrative Financial Impact

The project also estimates the potential operational value of improving the length of stay in high-LOS departments.

- Bottom-performing departments were identified using the highest quartile of average LOS.
- Their performance was compared against the median departmental LOS.
- An assumed value of ₹4,500 per bed-day was used.

**Estimated illustrative capacity opportunity: approximately ₹1.70 crore.**

This is a scenario-based estimate, not guaranteed cash savings. It requires clinical and financial validation.

---

## 📉 7. Data Visualization

Eight visualizations were developed using Matplotlib.

The visualizations include:

1. Monthly Average Length of Stay.
2. Monthly 30-Day Readmission Rate.
3. Monthly Bed Occupancy Rate.
4. Average LOS by Hospital.
5. Average LOS by Department.
6. Top Diagnoses by Admission Volume.
7. Patient Billing Distribution.
8. Monthly Admission Volume.

An Excel KPI dashboard was also developed to support performance monitoring and management reporting.

---

## 🔍 8. Advanced Analysis

Additional analysis was performed to understand performance differences across hospital operations.

- Hospital-wise KPI comparison.
- Department-wise performance analysis.
- Doctor-wise performance analysis.
- Patient utilization cohort analysis.
- Top and bottom performance deciles.
- Year-over-year monthly comparison.
- Patient billing contribution analysis.
- Illustrative financial impact estimation.

---

## 💡 9. Business Recommendations

Based on the analysis, three major recommendations were developed.

### Recommendation 1: Improve Data Quality

Implement standardized data-entry procedures and validation rules for patient admissions, discharge dates and diagnosis information.

### Recommendation 2: Optimize Bed Management

Introduce regular departmental performance reviews and improve discharge planning to support better utilization of hospital resources.

### Recommendation 3: Strengthen Patient Follow-Up

Develop a structured post-discharge follow-up process to identify patients with repeat admissions and improve care coordination.

---

## 🛠️ 10. Tools and Technologies Used

| Technology | Purpose |
|---|---|
| Python | Data analysis and processing |
| Pandas | Data cleaning and manipulation |
| NumPy | Numerical operations |
| Matplotlib | Data visualization |
| Microsoft Excel | KPI dashboard and reporting |
| Jupyter Notebook | Analysis and documentation |
| GitHub | Project version control and portfolio hosting |

---

## 📁 11. Project Structure

```text
Hospital_KPI_Performance_Review/
│
├── data/
│   ├── opd_visits_clean.csv
│   ├── admissions_clean.csv
│   ├── lab_tests_clean.csv
│   ├── billing_clean.csv
│   ├── trusted_admissions_analysis.csv
│   └── cleaning_log.csv
│
├── notebooks/
│   └── hospital_kpi_analysis.ipynb
│
├── outputs/
│   ├── hospital_kpi_dashboard.xlsx
│   ├── data_profile.csv
│   ├── monthly_kpi.csv
│   ├── hospital_kpi.csv
│   ├── department_kpi.csv
│   ├── doctor_kpi.csv
│   ├── patient_kpi.csv
│   ├── monthly_occupancy.csv
│   ├── year_over_year_monthly_comparison.csv
│   ├── reconciliation_manifest.json
│   └── [Eight visualization PNG files]
│
├── reports/
│   ├── Hospital_KPI_Project_Report.docx
│   └── Hospital_KPI_Insight_Deck.pptx
│
└── README.md
```

---

## ⚙️ 12. How to Run This Project

### Step 1: Clone the Repository

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
```

### Step 2: Navigate to the Project Folder

```bash
cd Hospital_KPI_Performance_Review
```

### Step 3: Install Required Libraries

```bash
pip install pandas numpy matplotlib jupyter openpyxl
```

### Step 4: Open Jupyter Notebook

```bash
jupyter notebook
```

### Step 5: Run the Analysis

Open:

`notebooks/hospital_kpi_analysis.ipynb`

Run the notebook cells to explore the cleaned datasets, KPI calculations and analytical results.

---

## 📦 13. Final Project Deliverables

The project includes:

- Four cleaned hospital datasets.
- One trusted admissions analysis dataset.
- Detailed data cleaning log.
- Python analysis notebook.
- Excel KPI dashboard.
- Eight data visualizations.
- Hospital performance analysis.
- Eight-slide management presentation.
- Comprehensive Word project report.

---

## 🎓 14. Learning Outcomes

Through this project, I gained practical experience in:

- Working with large datasets containing 500,000 records.
- Performing end-to-end data cleaning and preprocessing.
- Handling missing values and inconsistent formats.
- Developing and calculating business KPIs.
- Performing exploratory data analysis.
- Conducting cohort and comparative analysis.
- Building Excel dashboards.
- Creating data visualizations.
- Translating analytical findings into business recommendations.
- Documenting analytical workflows and presenting insights.

---

## 👨‍💻 Author

**Manav Natekar**
**Project Type:** End-to-End Data Analytics  
**Dataset Size:** 500,000 Synthetic Records
