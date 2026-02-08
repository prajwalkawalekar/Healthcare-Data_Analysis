# Healthcare Data Analysis Project

## Project Overview

This project focuses on analyzing **healthcare patient admission and billing data** to uncover insights related to **patient demographics, medical conditions, hospital performance, doctor efficiency, admission patterns, billing trends, insurance coverage, medications, and test outcomes**.

The dataset contains **55,000 rows and 15 columns**, representing real-world hospital operational data.
The project demonstrates an **end-to-end data analytics workflow**, starting from data cleaning to SQL-based analysis and interactive dashboard creation.

---
---
---
---
---

## Dataset Description

**Rows:** 55,000
**Columns:** 15

### Column Details:

* **Name** – Patient name (used as unique identifier)
* **Age** – Age of the patient
* **Gender** – Male / Female
* **Blood_Type** – Patient blood group
* **Medical_Condition** – Diagnosis or condition
* **Admission_Date** – Date of hospital admission
* **Doctor** – Attending doctor
* **Hospital** – Hospital name
* **Insurance_Provider** – Insurance company (if applicable)
* **Billing_Amount** – Total billing amount for the admission
* **Room_Number** – Room assigned during stay
* **Admission_Type** – Emergency / Routine / Elective
* **Discharge_Date** – Date of discharge
* **Medication** – Prescribed medication
* **Test_Result** – Normal / Abnormal test outcome

---

## 🛠️ Tech Stack Used

| Tool         | Purpose                                          |
| ------------ | ------------------------------------------------ |
| **Excel**    | Data cleaning, preprocessing, validation         |
| **SQL**      | Data analysis, aggregations, insights extraction |
| **Power BI** | Interactive dashboards & data visualization      |

---

## 🧹 Data Cleaning (Excel)

The raw dataset contained inconsistencies and formatting issues.
The following cleaning steps were performed using **Microsoft Excel**:

* Removed duplicate patient records
* Standardized column naming conventions
* Handled missing and null values
* Corrected inconsistent date formats
* Ensured correct data types (numeric, date, text)
* Validated billing amounts and age ranges
* Created derived fields such as **Age Group** and **Length of Stay**

## SQL Analysis

SQL was used to perform **deep analytical queries** and answer business-critical questions such as:

### Key Analysis Areas:

* Patient demographics analysis
* Medical condition frequency and severity
* Admission trends and seasonal patterns
* Average length of hospital stay
* Doctor and hospital performance
* Billing and revenue analysis
* Insurance coverage impact
* Medication usage trends
* Test result outcome analysis
* Identification of high-risk and high-cost cases

## Power BI Dashboards

Interactive dashboards were created in **Power BI** to visualize insights and support data-driven decision-making.

### Dashboard Pages:

1. **Executive Overview**
2. **Patient Demographics**
3. **Medical Condition Analysis**
4. **Admission & Length of Stay**
5. **Hospital & Doctor Performance**
6. **Billing & Insurance Analysis**
7. **Medication & Test Results**

## Key Insights & Findings

* Emergency admissions contribute disproportionately to higher billing and longer stays
* Certain medical conditions consistently result in abnormal test outcomes
* Senior patients (60+) show longer average hospital stays
* A small number of insurance providers account for a large portion of revenue
* Some hospitals handle high patient volume but generate lower average revenue
* Medications linked with abnormal test results tend to increase length of stay and cost

## Business Impact

This analysis helps healthcare stakeholders to:

* Optimize hospital resource utilization
* Improve emergency response efficiency
* Identify cost-inefficient treatment patterns
* Enhance doctor workload management
* Support insurance negotiations
* Improve patient outcome monitoring

## Future Enhancements

* Predictive modeling for readmission risk
* Integration with real-time hospital data
* Advanced DAX measures for forecasting
* Patient outcome scoring system
* Department-level performance analysis

## Author

**Prajwal Kawalekar**
Data Analyst | SQL | Power BI | Excel
