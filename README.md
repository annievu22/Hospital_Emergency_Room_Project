# 🏥 Hospital Emergency Room Analysis Project  
![Language](https://img.shields.io/badge/Language-Excel-16A085)
![Tool](https://img.shields.io/badge/Visualization-Excel%20Dashboard-F39C12)
![Status](https://img.shields.io/badge/Project-Completed-brightgreen)
![Data](https://img.shields.io/badge/Data-Hospital--ER--Synthetic-red)

> An Excel-based interactive dashboard analyzing hospital emergency room metrics to support faster service, better resource planning, and improved patient outcomes.

---

## 1. Overview

This project uses Microsoft Excel to transform synthetic hospital ER data into actionable insights through pivot tables, charts, slicers, and conditional formatting. The dashboard enables users to track key KPIs such as admission status, wait time efficiency, referral trends, and demographic distribution.

---

## 2. Business Objectives

### 2.1. Business Problem

Hospitals face growing pressure to reduce wait times and optimize ER resource usage. This project aims to help stakeholders identify operational bottlenecks, monitor daily patterns, and improve service delivery based on patient data.

> **Key questions addressed:**
> - How many patients are admitted vs. not admitted?
> - What are the most common referral departments?
> - How efficiently are patients seen within 30 minutes?
> - What trends exist across age and gender groups?

### 2.2. Business Impact & Insights

- Most ER patients are seen within target timeframes, but some departments have slower response patterns.  
- Certain departments receive disproportionately high referrals.  
- Younger patients and males appear more frequently in specific categories.  
- Age and gender trends can inform staffing strategies and triage decisions.

---

## 3. Data Sources

The dataset was provided as part of a data analytics training project and loaded into Microsoft Excel for cleaning, transformation, and visualization. It includes emergency room visit records across different hospitals, covering patient flow, wait times, and visit outcomes.

🔗 **Dataset Links**  
📁 [Download Dataset (Google Drive)](https://drive.google.com/file/d/1I_20JL8KP-muDr5hxVLW_2rjiobIIdiV/view?usp=sharing)
---

## 4. Methodology & Excel Analysis

This section outlines the full Excel-based workflow, leveraging **Power Query**, **Data Modeling**, and **DAX** to clean raw patient data, build metrics, and deliver an interactive emergency room dashboard.

### 4.1. Data Cleaning with Power Query

- Standardized date and time formats for consistent time tracking  
- Handled missing values in key columns such as `Gender` and `Wait Time`  
- Cleaned categorical fields (e.g., department names, status codes)  
- Removed duplicates and filtered irrelevant records  
- Automated transformation steps with Power Query for reusability  

### 4.2. Data Modeling & KPI Design using DAX

- Created calculated columns for age group, seen-time classification, and visit type  
- Built key measures using DAX, including:
  > - Average Wait Time  
  > - % of Patients Seen Within 30 Minutes  
  > - Daily Visit Count and Referral Trends  
- Established relationships between tables to support interactive filtering and dynamic KPIs  

### 4.3. Excel Dashboard Design

This Excel dashboard enables hospital staff and analysts to explore emergency room performance trends across departments, demographics, and timeframes using interactive charts, KPIs, and slicers.

🔗 **[View Full Dashboard in Excel](https://project.novypro.com/ud876F)**

### Dashboard Snapshot

![Hospital Emergency Dashboard](https://github.com/yourusername/project-folder/hospital_dashboard_snapshot.png)

---

### Walkthrough of Key Visuals:

* **Admission Status by Gender (Pie Chart):**  
  Visualizes the gender distribution among admitted and non-admitted patients.

* **Referral Count by Department (Bar Chart):**  
  Shows how many patients were referred from each hospital department.

* **Average Wait Time by Triage Level (Column Chart):**  
  Highlights which patient categories experienced the longest or shortest delays.

* **Daily Wait Time Trends (Line + Sparklines):**  
  Tracks how average wait time fluctuates each day across the observation period.

* **Age Group Breakdown (Stacked Bar Chart):**  
  Displays patient volume by age bracket and gender for targeted planning.

* **KPI Cards with DAX Logic:**  
  Key metrics like average wait time, % seen within 30 minutes, and total visits are calculated using DAX and update dynamically with slicer filters.

* **Interactive Slicers (Date, Department, Triage Level):**  
  Allow real-time filtering of visuals to focus on specific groups or timeframes.

This dashboard provides an accessible, Excel-native solution for emergency room analysis, combining DAX-powered insights with a clean and interactive interface for strategic hospital decision-making.


---

## 5. Final Conclusion

This project demonstrates the power of Excel as a standalone tool for business intelligence and reporting. Without the need for coding or external platforms, we created a dashboard that allows hospital teams to make faster, more informed decisions in emergency care environments.

**Key takeaways:**
- Age, gender, and referral patterns reveal pressure points in ER operations  
- Sparklines and slicers make trend monitoring fast and intuitive  
- Excel dashboards offer a low-barrier way to enable data-driven healthcare planning

**Future Enhancements:**
- Automate data refresh using Power Query or VBA  
- Add satisfaction survey data for deeper quality-of-care metrics  
- Include department-specific wait benchmarks for comparison

Overall, this practical Excel dashboard project showing strong analytical thinking and the ability to turn healthcare data into operational insight.
