# SQL Employee & Project Analytics

A PostgreSQL SQL project based on a **10K+ multi-sheet business dataset** covering employees, interns, projects, project teams, attendance, and assets.

## 📌 Project Overview

This project contains **45 SQL queries** designed to analyze employee information, project assignments, working hours, salaries, assets, attendance, project performance, and managerial workload.

The dataset contains **13,000+ records** across multiple tables and demonstrates practical SQL concepts used in real-world data analysis.

## 📊 Dataset

| Table | Records |
|---|---:|
| Employees | 5,000 |
| Interns | 800 |
| Projects | 500 |
| Project Team | 3,445 |
| Login & Logout | 3,000 |
| Assets Issued | 700 |
| **Total** | **13,445+** |

## 🗂️ Tables

- **employees** — Employee details, salary, department, joining and exit information
- **interns** — Intern details, domain, manager and internship dates
- **projects** — Project details, managers, budgets and revenue
- **project_team** — Employee project assignments and required days
- **login_logout** — Employee login, logout and working hours
- **assets_issued** — Company assets issued to employees and return information

## 🔍 SQL Analysis Covered

The 45 queries cover:

- Employee and department analysis
- Salary analysis
- Intern and manager analysis
- Project and team analysis
- Employee project assignments
- Working hours and overtime
- Late login analysis
- Employee attrition
- Employee tenure
- Asset utilization and late returns
- Project ROI and efficiency
- Managerial workload
- Employee 360° analysis
- Attendance analysis
- Ghost/overlapping login detection
- Intern-to-full-time conversion
- Window functions and ranking
- Correlated subqueries
- Self joins
- Aggregate functions
- Date and timestamp calculations

## 🛠️ Tools Used

- **PostgreSQL**
- **pgAdmin**
- SQL
- Excel

## 💡 SQL Concepts Used

- `SELECT`, `WHERE`
- `GROUP BY`, `HAVING`
- `ORDER BY`
- `JOIN`, `LEFT JOIN`
- Subqueries
- Correlated subqueries
- Self joins
- `UNION`
- Aggregate functions
- `CASE`
- `COUNT`, `SUM`, `AVG`
- `EXTRACT`
- Date and interval operations
- Window functions
- `RANK()` / `DENSE_RANK()`
- `CORR()`

## 📁 Project Structure

```text
SQL-Employee-Project-Analytics/
│
├── SQL_Queries.sql
├── Dataset.xlsx
└── README.md
```

## 🎯 Project Objective

The main objective of this project is to demonstrate practical PostgreSQL skills by converting a multi-table business dataset into meaningful employee, project, attendance, asset, and financial insights.

This project focuses on **writing SQL queries for real-world business analysis** rather than only basic SQL exercises.

## 👤 Author

**Koti Tarun**  
B.E. Artificial Intelligence & Data Science.
