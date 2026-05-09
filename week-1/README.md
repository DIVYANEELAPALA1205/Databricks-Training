🚀 Week 1 - Day 1 SQL Basics

---

📌 What I Learned Today

Today I practiced fundamental SQL concepts using DB Fiddle as part of my Data Engineering learning journey.

The session focused on:

- Database creation
- Table creation
- Inserting records
- Writing basic SQL queries
- Filtering and sorting data
- Aggregate functions
- Basic joins

---

📚 Topics Covered

SQL Basics

- SELECT
- WHERE
- ORDER BY
- DISTINCT
- LIMIT

Aggregate Functions

- COUNT()
- AVG()
- MAX()
- MIN()
- SUM()

Joins

- INNER JOIN
- Introduction to LEFT JOIN

Database Concepts

- Primary Key
- Foreign Key
- NULL values

---

🛠 Practice Files

File Name| Description
"datacreation.sql"| Database schema and sample data
"basic_queries.sql"| Basic SQL practice queries
"joins_practice.sql"| Join-related practice queries

---

📂 Folder Structure

Week1/
└── Day1_SQL_Basics/
    ├── README.md
    ├── datacreation.sql
    ├── sql-queries.txt
    ├── outputs

---

💡 Key Learnings

- Learned how relational databases work
- Understood relationships using foreign keys
- Practiced retrieving filtered data
- Learned how joins combine data from multiple tables
- Improved confidence in writing SQL queries

---

🔥 Platforms Used

- DB Fiddle
- GitHub
- SQL YouTube Playlist

---

✅ Status

Completed Day 1 SQL Basics practice and uploaded all practice files to GitHub.
🚀 Week 1 - Day 2 SQL Clauses & Operators Practice
📌 What I Learned Today
Today I practiced important SQL clauses and operators using an Employee table as part of my Data Engineering learning journey.
The session focused on:


Retrieving data using different SQL queries


Filtering records with conditions


Grouping and analyzing data


Using aggregate functions


Working with logical and comparison operators


Pattern matching using LIKE operator



📚 Topics Covered
SQL Clauses


SELECT


WHERE


GROUP BY


HAVING


DISTINCT


TOP / LIMIT


Aggregate Functions


COUNT()


AVG()


MAX()


MIN()


SUM()


SQL Operators


Comparison Operators (=, >, <, >=, <=, <>)


Logical Operators (AND, OR, NOT)


IN & NOT IN


BETWEEN


LIKE Operator



🛠 Practice Files
File NameDescriptionemployee_table.sqlEmployee table creation and sample datasql_practice_queries.sqlSQL clause and operator practice queriesoutputs.txtQuery outputs and results

📂 Folder Structure
Week1/ └── Day2_SQL_Clauses_Operators/      ├── README.md      ├── employee_table.sql      ├── sql_practice_queries.sql      └── outputs/

💡 Key Learnings


Learned how to filter and retrieve specific records


Practiced grouping data using GROUP BY


Understood aggregate functions for data analysis


Learned how logical operators work in SQL queries


Improved understanding of pattern matching with LIKE


Gained confidence in writing SQL queries independently



🔥 Platforms Used


DB Fiddle


GitHub


SQL YouTube Playlist



✅ Status
Completed Day 2 SQL Clauses & Operators practice and uploaded all practice files to GitHub.

Day-3 SQL JOINS
# SQL JOIN Operations Assignment

## Overview
This project contains SQL queries demonstrating different types of JOIN operations using a Student Management Database.

The assignment covers:

- LEFT JOIN
- RIGHT JOIN
- FULL OUTER JOIN
- INNER relationship handling
- Finding unmatched records
- Generating combined reports from multiple tables

---

## Tables Used

### Students
Contains student details.

### Courses
Contains course information.

### Enrollments
Stores student course enrollment details.

### Instructors
Contains instructor information.

---

## Topics Covered

1. Display students and their enrolled courses
2. Find courses with no enrolled students
3. Display instructors and assigned courses
4. Find courses without instructors
5. RIGHT JOIN usage
6. Find students not enrolled in any course
7. FULL OUTER JOIN implementation
8. Find courses never enrolled
9. FULL OUTER JOIN between instructors and courses
10. Generate combined student-course-instructor report

---

## Important Note

MySQL does not directly support:

```sql
FULL OUTER JOIN
```

Therefore, FULL OUTER JOIN operations were implemented using:

```sql
LEFT JOIN
UNION
RIGHT JOIN
```

---

## Technologies Used

- MySQL
- SQL JOIN Operations

---

## Learning Outcomes

Through this assignment, the following concepts were understood:

- Relationship handling between tables
- JOIN operations in SQL
- Handling NULL values
- Combining data from multiple tables
- Simulating FULL OUTER JOIN in MySQL

---
🚀 Week 1 - Day 4 SQL Window Functions & CTE Practice

📌 What I Learned Today

Today I practiced advanced SQL concepts including Window Functions and Common Table Expressions (CTEs) as part of my Data Engineering learning journey.

The session focused on:

* Ranking and analytical SQL functions
* Using Window Functions for advanced calculations
* Working with Common Table Expressions (CTEs)
* Recursive CTEs
* Running totals and moving averages
* Customer and sales analysis queries

📚 Topics Covered

🔹 Window Functions

* ROW_NUMBER()
* RANK()
* DENSE_RANK()
* NTILE()
* LAG()
* LEAD()

🔹 Analytical Functions

* Running Totals
* Moving Averages
* Cumulative Sales
* Department-wise Salary Analysis
* Percentage Contribution Calculations

🔹 Common Table Expressions (CTEs)

* Simple CTEs
* Multiple CTEs
* Recursive CTEs

🔹 Advanced SQL Concepts

* Employee Salary Ranking
* Department Payroll Analysis
* Customer Spending Rankings
* Monthly Sales Trends
* Employee Hierarchy Queries

🛠 Practice Files

File Name | Description

* employees.sql → Employee table creation and sample data
* customers.sql → Customer table creation and sample data
* orders.sql → Orders table creation and sample data
* sql_window_functions.sql → Window Functions practice queries
* sql_cte_queries.sql → CTE and Recursive CTE practice queries
* outputs.txt → Query outputs and results

📂 Folder Structure

Week1/
└── Day3_SQL_WindowFunctions_CTEs/
├── README.md
├── employees.sql
├── customers.sql
├── orders.sql
├── sql_window_functions.sql
├── sql_cte_queries.sql
└── outputs/

💡 Key Learnings

* Learned advanced SQL analytical functions
* Practiced ranking and partitioning data
* Understood how to use LAG() and LEAD()
* Learned cumulative calculations using window functions
* Practiced recursive queries using CTEs
* Improved understanding of real-world business reporting queries
* Gained confidence in writing complex SQL queries independently

🔥 Platforms Used

* DB Fiddle
* GitHub
* MySQL 8.0
* SQL YouTube Playlist

✅ Status

Completed Day 3 SQL Window Functions & CTE practice and uploaded all practice files to GitHub.

# Author
Divyasree Neelapala
BTECH IT

