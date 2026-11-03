Q1. Write a query to list the number of jobs available in the employees table.
SQL Query:
SELECT COUNT(DISTINCT job_id) AS Total_Jobs
FROM employees;
