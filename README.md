# Joins-Practice

COMPANY : CODTECH IT SOLUTIONS

NAME : KALPANA A

INTERN ID : COD1234

DOMAIN : SQL

DURATION : 4 WEEKS 

MENTOR : NEELA SANTOSH

Description of SQL Joins with Employee and Branch Tables

INNER JOIN:

Retrieves only the matching records between employee and branch tables.
If an employee is assigned to a branch, their details are included in the result.
Employees without a branch and branches without employees are excluded.

LEFT JOIN:

Retrieves all employees and their corresponding branch details.
If an employee is not assigned to any branch, the branch details appear as NULL.
Ensures that no employee data is lost, even if they do not belong to a branch.

RIGHT JOIN:

Retrieves all branches and their assigned employees.
If a branch has no employees, the employee details appear as NULL.
Ensures that all branches are represented, even if they do not have any employees.


FULL JOIN (Simulated using UNION in MySQL):

Combines the results of LEFT JOIN and RIGHT JOIN.
Retrieves all employees and all branches, even if they are not related.
Employees without a branch and branches without employees both appear with NULL values in the missing columns.
