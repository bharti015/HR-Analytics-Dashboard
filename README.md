
# HR Analytics Dashboard

This repository contains an end-to-end **Power BI HR Analytics Dashboard** that analyzes employee attrition and workforce trends. It demonstrates the complete workflow: loading raw data, preparing it, creating DAX measures, and building interactive visuals.

---

## Dataset

**File:** `HR_Analytics.csv`
**Rows:** 1481
**Columns:** 36

The dataset includes:

* Employee demographics
* Compensation details
* Performance metrics
* Job roles
* Attrition information

---

## Tools Used

* Power BI Desktop
* Power Query
* DAX

---

## Data Cleaning & Preparation

Performed using **Power Query**:

1. Loaded the `.csv` file
2. Formatted data types
3. Removed null/blank values
4. Removed duplicate records
5. Ensured consistent structure for analysis

---

## DAX Measures

Custom DAX measures created:

* Total Employees
* Attrition Count
* Attrition Rate
* Average Age
* Average Salary
* Average Years at Company
* Attrition by Gender

---

## Dashboard Visuals

The dashboard includes:

* KPI cards
* Donut chart: Attrition by Education
* Bar chart: Attrition by Age Group
* Stacked bar: Attrition by Salary Brackets
* Stacked bar: Attrition by Job Role
* Area chart: Attrition by Years at Company
* Matrix table: Job Satisfaction Ratings

### Dashboard Screenshots

![Dashboard](HRDashboard'.png)

---

## Key Insights

* Lab Technician has the highest attrition
* 141 males and 79 females left
* Age group 26–35 shows the most attrition
* Employees earning up to 5K show highest attrition
* Most employees leave within 1 year
* Life Sciences (37%) and Medical (27%) show highest attrition by education

---

## Repository Structure

```
│── dashboard.pbix
│── README.md
│── HR_Analytics.csv
│── images/
│     ├── dashboard1.png
│     ├── dashboard2.png
```

---

## How to Use

1. Download `dashboard.pbix`
2. Open it in Power BI Desktop
3. Explore the visuals and DAX measures

---

## Conclusion

This project demonstrates a complete HR analytics workflow, from raw data to meaningful insights. Future extensions may include attrition forecasting, role-based analysis, and integrating additional datasets.

---

