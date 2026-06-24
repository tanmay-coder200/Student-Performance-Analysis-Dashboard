# Education Performance Analytics Dashboard

## Project Overview

The **Education Performance Analytics Dashboard** is an interactive business intelligence project built using Microsoft Power BI to analyze the factors influencing student academic performance.

The objective of this project was to identify how **academic habits, lifestyle behaviors, demographic background, and risk-related factors** impact student performance and to derive actionable insights that educational institutions can use for student intervention and performance improvement.

This dashboard transforms raw student performance data into meaningful analytical insights through data modeling, DAX calculations, KPI design, and multi-page interactive reporting.

---

## Business Problem

Educational institutions often struggle to identify the underlying factors affecting student academic performance.

This project aims to answer critical questions such as:

* Does study time significantly improve academic performance?
* How do alcohol consumption and social habits affect grades?
* Which students are academically at risk?
* Do demographic factors such as parental education or commute time influence performance?
* Which student groups require academic intervention?

---

## Dashboard Pages

### 1. Executive Overview

<img width="1421" height="784" alt="image" src="https://github.com/user-attachments/assets/1e48ee53-bf0d-402d-a812-dc654b6b3167" />

Provides a high-level summary of student academic performance through key metrics and behavioral analysis.

Key Metrics:

* Average Final Grade
* Students Pursuing Higher Education (%)
* Top Performers Percentage
* Students At Risk Percentage

Key Insights:

* Students studying **5–10 hours score 22.5% higher** than students studying less than 2 hours.
* Students with low study time report the highest alcohol consumption patterns.

---

### 2. Academic Performance Analysis

<img width="1425" height="784" alt="image" src="https://github.com/user-attachments/assets/f1852a66-2728-4f73-9e72-a95a723c5695" />

Analyzes behavioral factors affecting student grades.

Analysis Included:

* Study Time vs Final Grade
* Weekend Alcohol Consumption vs Grades
* Weekday Alcohol Consumption vs Grades
* Going Out Frequency vs Grades
* Extra Educational Support Impact

Key Insights:

* Students with very low weekday alcohol consumption score **20% higher** than students with very high weekday alcohol consumption.
* Moderate social activity correlates with better academic performance compared to extremely low social engagement.

---

### 3. Risk Analysis
<img width="1441" height="790" alt="image" src="https://github.com/user-attachments/assets/c433bdc8-cc63-483d-a800-b4a96fc89788" />

Designed a custom academic risk scoring model to identify students potentially vulnerable to poor academic outcomes.

Risk Factors Used:

* Study Time
* Alcohol Consumption
* Absences
* Going Out Frequency
* Past Academic Failures

Custom Risk Categories:

* Low Risk
* Medium Risk
* High Risk

Analysis Included:

* Family Support vs Grade
* Past Failures vs Grade
* Absences vs Final Grade
* Student Risk Distribution

Key Insights:

* A single past academic failure significantly reduces average academic performance.
* Over **55% of students fall under Medium Risk category**, while approximately **28% are classified as High Risk**.

---

### 4. Demographic Analysis
<img width="1404" height="756" alt="image" src="https://github.com/user-attachments/assets/992a0113-def3-454b-ad76-579e393d48e8" />

Examines how background and family environment influence academic outcomes.

Analysis Included:

* School-wise Performance Comparison
* Father Education Level vs Grade
* Mother Education Level vs Grade
* Commute Time vs Grade
* Decomposition Tree Analysis for performance breakdown

Key Insights:

* Students with highly educated parents consistently score higher.
* School type shows stronger performance variation than commute time.
* Parental educational background positively correlates with student academic performance.

---

## Technical Skills Demonstrated

### Data Modeling

Implemented a star-schema style relational model using dimension tables for categorical variables:

* Study Time
* Free Time
* Alcohol Consumption
* Family Support
* Travel Time
* Health Status

---

### Power BI Skills Used

* Data Cleaning and Transformation using Power Query
* Data Modeling and Relationship Building
* DAX Measures and Calculated Columns
* KPI Cards and Dynamic Metrics
* Multi-page Dashboard Design
* Interactive Filters and Slicers
* Decomposition Tree Visual
* Insight-driven Reporting

---

## Custom DAX Logic Implemented

### Risk Score Calculation

Created a custom scoring model using behavioral and academic risk indicators.

Factors considered:

* Low Study Time
* High Weekend Alcohol Consumption
* High Weekday Alcohol Consumption
* High Absences
* Frequent Social Activity
* Past Failures

Students were categorized into:

* Low Risk
* Medium Risk
* High Risk

---

## Key Business Insights

* Study time is one of the strongest positive predictors of academic success.
* Alcohol consumption shows a negative relationship with academic performance.
* Past academic failures act as the strongest academic risk indicator.
* Students with stronger family support tend to achieve higher grades.
* Higher parental education levels positively influence student performance.
* Attendance patterns strongly correlate with academic outcomes.

---

## Tools & Technologies

* Microsoft Power BI
* Power Query
* DAX (Data Analysis Expressions)
* Data Modeling
* Data Visualization
* Business Intelligence Reporting

---

## Project Outcome

This dashboard demonstrates the ability to move beyond simple visualization and perform **data-driven analytical storytelling**.

The project focuses on extracting actionable insights rather than only displaying charts, simulating a real-world business intelligence workflow used in educational analytics and decision making.

---

## Dashboard Preview

(Add screenshots here)

* Executive Overview
* Academic Performance Analysis
* Risk Analysis
* Demographic Analysis

---

## Learning Outcomes

Through this project I strengthened my understanding of:

* Analytical Thinking
* Business Problem Solving
* KPI Design
* Feature Engineering
* Power BI Data Modeling
* Dashboard Storytelling
* Insight Extraction from Data

---

## Future Improvements

Possible future enhancements:

* Predictive modeling using Machine Learning
* Student performance forecasting
* Drill-through pages for individual student analysis
* Automated intervention recommendations for at-risk students

---
