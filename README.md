# JOINS-PRACTICE
COMPANY: CODTECH IT SOLUTION

NAME: BHAVESH PRAKASH BOREKAR 

INTERN ID: CT08UQG 

DOMAIN: SQL

DURATION: 4 WEEKS

MENTOR: MEELA SANTOSH

This SQL script demonstrates various types of JOIN operations between two tables: EMPLOYEE and DEPARTMENT.
1. Creating Tables and Inserting Data:
•	EMPLOYEE Table: The EMPLOYEE table has columns for empId, name, and dept_id. 
o	Five employee records are inserted.
•	DEPARTMENT Table: The DEPARTMENT table has columns for dept_id and dept_name. 
o	Five department records are inserted.
2. SELECT Queries:
•	INNER JOIN: This query selects employees and their respective department names by matching dept_id in both tables. Only employees who have a matching department are included in the result.
•	LEFT JOIN: This query selects all employees and their respective department names. If an employee does not have a corresponding department (NULL dept_id), the result will still include the employee with a NULL department name.
•	RIGHT JOIN: This query selects all departments and their respective employees. If a department does not have any employees, the result will still include the department with a NULL employee name.
•	FULL OUTER JOIN: This query selects all employees and all departments. If an employee does not belong to any department, their dept_name will be NULL, and if a department does not have any employees, the employee information will be NULL.
Summary of JOIN Types:
•	INNER JOIN: Returns only matching rows from both tables.
•	LEFT JOIN: Returns all rows from the left table (EMPLOYEE) and matching rows from the right table (DEPARTMENT).
•	RIGHT JOIN: Returns all rows from the right table (DEPARTMENT) and matching rows from the left table (EMPLOYEE).
•	FULL OUTER JOIN: Returns all rows when there is a match in one of the tables, with NULLs where there is no match.

This script helps demonstrate the different types of joins and how they affect the output when combining data from two related tables.

OUTPUT:
![1ST](https://github.com/user-attachments/assets/beebf63e-e5fc-42a1-b959-cbd337183a69)

![2ND](https://github.com/user-attachments/assets/c080c507-f196-473d-91c0-9f2ce0d5d8df)

![3RD](https://github.com/user-attachments/assets/b83e2bb6-ed9d-488d-a02c-07f003536f79)

![4RH](https://github.com/user-attachments/assets/7e68423b-61da-44fc-bfff-6ef80c313615)


![5TH](https://github.com/user-attachments/assets/e3bef85b-4639-42dc-aa5e-ad516d7253ed)


![6TH](https://github.com/user-attachments/assets/d29cab14-d75f-4198-95e5-d24aa9cb3789)


