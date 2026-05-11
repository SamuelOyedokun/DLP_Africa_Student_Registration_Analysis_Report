# DLP Africa — Student Registration Analysis

![Excel](https://img.shields.io/badge/Tool-Microsoft%20Excel-217346?style=flat&logo=microsoft-excel&logoColor=white)
![Python](https://img.shields.io/badge/Tool-Python-3776AB?style=flat&logo=python&logoColor=white)
![Jupyter](https://img.shields.io/badge/Notebook-Jupyter-F37626?style=flat&logo=jupyter&logoColor=white)
![Colab](https://img.shields.io/badge/Platform-Google%20Colab-F9AB00?style=flat&logo=googlecolab&logoColor=white)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)
![Students](https://img.shields.io/badge/Students%20Analysed-40-blue)

---

## Project Overview

This project is a complete data analysis of student registration records
for DLP Africa's May 2026 cohort. The analysis covers enrollment patterns,
course popularity, gender distribution, age demographics, and registration
trends across 40 students and 8 courses.

The analysis was conducted in **two environments** — Microsoft Excel and Python (Jupyter Notebook) —
demonstrating the same insights using both tools end to end.

The submission was prepared as part of a Role Activation Task for a
Data Analysis position at DLP Africa.

---

## Problem Statement

Given a raw student registration dataset, the goal was to:
- Identify the most popular courses
- Analyse gender and age distribution
- Spot registration trends over time
- Deliver actionable recommendations
- Demonstrate data analysis skills across Excel and Python

---

## Tools and Techniques Used

| Tool / Function | Purpose |
|---|---|
| Microsoft Excel | Primary analysis tool |
| COUNTIF / COUNTIFS | Course and gender counts |
| VLOOKUP | Student lookup by ID |
| HLOOKUP | Course lookup by name |
| INDEX / MATCH | Student lookup by name (Excel 2013 compatible) |
| Pivot Tables | Cross analysis of Course vs Gender |
| Dashboard | Visual summary of all KPIs |
| Charts | Bar, line and pie charts for storytelling |
| Python (pandas) | Data loading, cleaning and analysis |
| Python (matplotlib) | Chart and dashboard creation |
| ipywidgets | Interactive lookup system in Jupyter |
| Google Colab | Cloud notebook execution |

---

## Key Findings

- **40 students** registered across **8 courses**
- **Data Analysis** is the most popular course with **11 enrollments (27.5%)**
- Gender split: **60% Male (24 students)** vs **40% Female (16 students)**
- Average student age: **23.3 years** (range: 20 to 28)
- Peak registration day: **5 May 2026** with 8 registrations
- Largest age group: **20 to 24 years** representing 68% of students

---

## Recommendations

1. Open additional Data Analysis cohorts to meet demand
2. Launch targeted female enrollment campaigns to close the gender gap
3. The peak registration period on 5th of May 2026 offers a clear opportunity for timed marketing campaigns
4. Invest in promoting courses with low registration rate such as UI/UX Design

---

## Files in This Repository

| File | Description |
|---|---|
| `DLP AFRICA STUDENT REGISTRATION REPORT.xlsx` | Full Excel workbook with raw data, analysis sheets, dashboard, pivot table and lookup system |
| `DLP_Africa_Student_Registration_Analysis.ipynb` | Python Jupyter Notebook replicating the full Excel analysis with interactive charts and executive dashboard |
| `DLP AFRICA Student Registration Analysis Presentation Slide.pdf` | Professional slide deck summarising all findings |
| `DLP AFRICA Student Registration Analysis Teaching Note.pdf` | Written report including facilitator section and beginner data thinking framework |

---

## Excel Workbook Structure

The workbook contains the following sheets:

| Sheet | Contents |
|---|---|
| Registration Report | Raw data of all 40 students |
| Pivot Table | Course vs Gender cross analysis |
| Course Count Analysis | Enrollment counts, percentages and rankings |
| Gender Analysis | Male vs Female breakdown per course |
| Age Analysis | Age distribution and age group summary |
| Lookup Analysis | VLOOKUP, HLOOKUP and INDEX/MATCH systems |
| Dashboard | Full KPI dashboard with charts |
| Executive Summary | One page written summary of findings |

---

## Python Notebook Structure

The Jupyter Notebook mirrors every Excel sheet in Python:

| Notebook Section | Excel Equivalent |
|---|---|
| Load & Clean Data | Registration Report sheet |
| Data Overview | dtypes, nulls, basic stats |
| Pivot Table | PIVOT TABLE sheet (Course × Gender) |
| Course Count Analysis | COURSE COUNT ANALYSIS sheet |
| Gender Analysis | GENDER ANALYSIS sheet |
| Age Analysis | AGE ANALYSIS sheet |
| Interactive Lookup System | LOOKUP ANALYSIS (VLOOKUP / XLOOKUP / HLOOKUP) |
| Charts | Bar, pie, grouped bar, line charts |
| Executive Dashboard | Full KPI dashboard combining all visuals |

---

## Skills Demonstrated

- Data cleaning and formatting in Excel and Python
- Formula driven analysis using COUNTIF, VLOOKUP, HLOOKUP, INDEX/MATCH
- Pandas groupby, crosstab, pivot and aggregation
- Pivot table construction and sorting
- Interactive lookup widgets with ipywidgets
- Dashboard design in both Excel and matplotlib
- Chart creation and data storytelling across two tools
- Written communication of data insights
- Structured thinking and recommendation writing

---

## How to Run the Notebook

1. Open [Google Colab](https://colab.research.google.com)
2. Upload `DLP_Africa_Student_Registration_Analysis.ipynb`
3. Upload `DLP AFRICA STUDENT REGISTRATION REPORT.xlsx` when prompted
4. Run all cells from top to bottom (`Runtime → Run all`)

---

## Author

**Samuel Oyedokun**
Data Analysis | Microsoft Excel | Python | Data Storytelling

[GitHub Profile](https://github.com/SamuelOyedokun)

---

*Submitted as part of the DLP Africa Role Activation Task — May 2026*
