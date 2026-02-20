# Employee-Management-System-SQL-Project

A complete relational database project designed to simulate real-world HR operations using SQL.  
This system manages employees, departments, salaries, bonuses, qualifications, leaves, and payroll processing within a structured and normalized database model.

---

## 📌 Project Overview

This project demonstrates the design and implementation of a multi-table relational database to support core Human Resource (HR) operations.

The system enables:

- Centralized employee record management
- Department and job role structuring
- Salary and performance bonus tracking
- Leave monitoring and deduction handling
- Payroll computation and analysis
- Business-driven HR insights using SQL queries

---

## 🗂 Database Architecture

The database follows normalization principles (up to 3NF) to ensure:

- Reduced redundancy
- Data consistency
- Referential integrity
- Scalable schema design

### Core Tables

| Table Name        | Purpose |
|-------------------|----------|
| Employee          | Stores employee personal and employment details |
| JobDepartment     | Maps employees to departments and job roles |
| Salary_Bonus      | Tracks base salary, increments, and bonus details |
| Qualification     | Stores educational and skill-based information |
| Leaves            | Records leave history and leave counts |
| Payroll           | Calculates final payroll including deductions |

---

## 🧠 SQL Concepts Applied

- Primary & Foreign Key Constraints
- Data Normalization (1NF, 2NF, 3NF)
- INNER, LEFT, RIGHT Joins
- GROUP BY & HAVING Clauses
- Aggregate Functions (SUM, AVG, COUNT, MAX, MIN)
- Subqueries
- Payroll Calculations using derived values
- Referential Integrity Enforcement

---

## 📊 Business Insights Generated

### 👥 Employee Insights
- Highest earning employees (Salary + Bonus)
- Employees with maximum leave usage
- Qualification-based employee segmentation
- Department-wise employee distribution

### 💰 Compensation Insights
- Highest bonus recipients
- Salary comparison across departments
- Role-based salary analysis
- Bonus contribution to total payroll

### 📅 Leave Analysis
- Frequent leave patterns
- Department-wise leave breakdown
- Leave impact on payroll deductions

### 🏢 Department Analytics
- Most populated departments
- High payroll cost departments
- Workforce distribution trends

---

## 📁 Project Structure

```
EMS_Datasets/
 ├── Employee.csv
 ├── JobDepartment.csv
 ├── Salary_Bonus.csv
 ├── Qualification.csv
 ├── Leaves.csv
 └── Payroll.csv

EMS_WorkBench/
 └── SQL_WORKBENCH.sql

EMS_Reports/
 └── SQL_PPT.pptx

README.md
```

---

## ▶️ How to Run the Project

### Step 1: Import CSV Files
Import each dataset into its corresponding MySQL table.

### Step 2: Execute SQL Script
Run the SQL script in MySQL Workbench:

```
EMS_WorkBench/SQL_WORKBENCH.sql
```

### Step 3: Analyze Results
Execute analytical queries to generate HR insights and payroll reports.

---

## 🛠 Tools & Technologies

- MySQL
- MySQL Workbench
- ER Modeling
- SQL Query Optimization
- Git & GitHub

---

## 🚧 Technical Challenges Solved

- Designing normalized multi-table schema
- Implementing foreign key relationships
- Handling complex JOIN operations for payroll computation
- Automating leave-based salary deductions
- Maintaining scalable relational structure

---

## 📈 Project Significance

This project reflects how structured relational database design can improve HR operations through:

- Accurate payroll processing
- Transparent compensation management
- Efficient leave tracking
- Data-driven workforce decision-making

It serves as a strong portfolio project for:
- Data Analyst roles
- SQL Developer roles
- Business Intelligence positions
- Entry-level Data Engineering roles

---

## 📌 Conclusion

The Employee Management System showcases the practical application of SQL in solving real-world business problems through structured database design, relational modeling, and analytical querying.

This project highlights strong fundamentals in:
- Database architecture
- SQL query writing
- Data modeling
- Analytical thinking

---

⭐ If you found this project useful, feel free to explore, fork, or provide feedback.
