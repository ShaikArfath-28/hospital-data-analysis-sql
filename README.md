# 🏥 Hospital Data Analysis Using SQL

This project is part of a 30-day SQL micro-course challenge. It focuses on analyzing hospital data to uncover patterns related to patient volume, departmental performance, and medical expenses using SQL queries.

---

## 📌 Project Overview

This case study involves performing data analysis on hospital records to answer real-world business questions using SQL.  
The queries are designed to be simple, clean, and easy to understand, making them accessible for stakeholders and learners alike.

---

## 🧠 Key Insights Extracted

- Total and average number of patients across hospitals
- Most visited departments and busiest cities
- Monthly medical expenses breakdown
- Longest hospital stays and average duration by department
- Hospitals with highest expenses
- Department with the lowest number of patients

---

## 📁 Files Included

- **`Hospital_Dataset.xlsx`** – Raw hospital data used for SQL queries  
- **`SQL_Assignment_Solutions.pdf`** – PDF containing 10 SQL queries and answers

---

## 🛠 Tools Used

- SQL (PostgreSQL / MySQL-style queries)
- Excel (for initial data review)
- PDF for structured output documentation

---

## 🧾 Sample Query

```sql
-- Top 3 Departments with the Highest Number of Patients
SELECT department, SUM(patients_count) AS total_patients
FROM hospital
GROUP BY department
ORDER BY total_patients DESC
LIMIT 3;
```
---
## 🔍 Project Purpose
This assignment was completed as part of a learning challenge and demonstrates how SQL can be applied to analyze real-world healthcare data.
The queries are structured to be beginner-friendly while solving meaningful business questions.
---
## 🤝 Connect with Me

I'm actively building my portfolio in SQL and data analytics.  
🔗 [LinkedIn – Shaik Arfath](https://www.linkedin.com/in/shaik-arfath-a66318284/)

