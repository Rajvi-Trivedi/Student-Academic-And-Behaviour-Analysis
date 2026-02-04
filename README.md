# 📊 Student Academic and Behaviour Analysis – Power BI Dashboard

## Project Overview

This project focuses on analyzing **student academic performance and behavioral patterns** using Microsoft Power BI.
The dashboard provides a consolidated view of scores, attendance, and behavior data to help identify performance trends, areas of improvement, and overall student outcomes.

The solution emphasizes **data modeling, DAX calculations, interactive visualizations, and storytelling**.

---

## Dataset Description

The project uses multiple datasets sourced from Google Sheets / Excel:

* **Students** – Student demographic details (StudentID, Name, Class, Section, Gender)
* **Scores** – Subject-wise exam scores, max scores, terms
* **Attendance** – Attendance percentage and status by date
* **Behavior** – Student behavior records and behavior types

All datasets are connected using **StudentID** as the primary key.

---

## Data Modeling

* A **star-schema–like model** was implemented
* **Students** table acts as the dimension table
* **Scores, Attendance, and Behavior** act as fact tables
* One-to-many relationships were created from Students to all fact tables
* Proper data types and cleaned column names were applied

---

## Key DAX Measures

The following measures were created using DAX:

* Total Students
* Total Score
* Total Max Score
* % Score
* Average Score
* Attendance %
* Behavior Count
* Performance Category (High / Medium / Low using SWITCH)

These measures support dynamic filtering and interactivity across visuals.

---

## Dashboard Visualizations

The dashboard includes:

* **KPI Cards**: Total Students, % Score, Avg Score, Attendance %, Performance Category
* **Bar Chart**: Average Score by Subject and Class
* **Line Chart**: Performance Trend by Term
* **Donut Chart**: Student Behavior Distribution
* **Table**: Student-wise performance with conditional formatting
* **Slicers**: Class, Section, Subject, Term for interactive analysis

Conditional formatting highlights high and low performers for quick insights.

---

## Key Insights

* Higher attendance generally correlates with better academic performance
* Certain subjects show lower average scores and may need intervention
* Medium-performing students exhibit higher behavioral incidents
* Performance trends vary across academic terms

---

## Tools & Technologies Used

* Microsoft Power BI Desktop
* DAX (Data Analysis Expressions)
* Google Sheets / Excel
* Data Modeling & Visualization Techniques

---

## Deliverables

* **Student_performance_dashboard.pbix**
* README documentation (this file)

---

## Conclusion

This dashboard demonstrates end-to-end Power BI capabilities, including data preparation, modeling, DAX calculations, visualization, and interactive reporting.
It provides actionable insights into student performance and behavior in a clear and professional manner.

---

