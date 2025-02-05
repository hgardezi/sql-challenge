# sql-challenge
1. Data Modeling (ERD)
First, I need to inspect the CSV files to determine the structure and relationships.
Then, I'll create an Entity Relationship Diagram (ERD) that includes entities, attributes, and relationships.

2. Data Engineering
Define table schemas for each CSV file.
Set primary keys (PKs) and foreign keys (FKs) to maintain relationships.
Ensure data types match the expected values.
Create SQL tables in the correct order (handling FK dependencies). Example title, employees, departments, salaries, then department_manger and last department_employees
Import the CSV files into SQL(PgAdmin) in same order.
Now we have data for each Table and we are able to answer each question.

4. Data Analysis (SQL Queries)
Get employee details with salaries.
Employees hired in 1986.
List managers and their department info.
Employee department information.
Employees with first name Hercules and last name starting with B.
Employees in the Sales department.
Employees in Sales & Development.
Count of employees sharing the same last name.
