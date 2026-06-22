# JOINS-PRACTICE

## Project Overview

This project demonstrates the use of SQL JOIN operations to combine data from multiple tables in a relational database. The objective is to understand how different JOIN types retrieve related information from tables and present meaningful results.

## Technologies Used

- SQL
- MySQL

## Database Tables

### Employees
Contains employee information.

| Column | Description |
|----------|-------------|
| emp_id | Employee ID |
| emp_name | Employee Name |
| dept_id | Department ID |

### Departments
Contains department information.

| Column | Description |
|----------|-------------|
| dept_id | Department ID |
| dept_name | Department Name |

## JOIN Operations Performed

### 1. INNER JOIN
Returns records that have matching values in both tables.

### 2. LEFT JOIN
Returns all records from the Employees table and matching records from the Departments table.

### 3. RIGHT JOIN
Returns all records from the Departments table and matching records from the Employees table.

### 4. FULL JOIN
Returns all records when there is a match in either the Employees or Departments table.

## Output Summary

The queries successfully demonstrated:

- Data retrieval using INNER JOIN
- Inclusion of unmatched employee records using LEFT JOIN
- Inclusion of unmatched department records using RIGHT JOIN
- Combined results using FULL JOIN

## Learning Outcomes

- Understanding relational database concepts
- Working with multiple tables
- Implementing various SQL JOIN operations
- Analyzing query results and data relationships

## Conclusion

This project successfully demonstrates the implementation of INNER JOIN, LEFT JOIN, RIGHT JOIN, and FULL JOIN operations in SQL and their practical use in combining related data across multiple tables.
