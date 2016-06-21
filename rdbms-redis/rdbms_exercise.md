## RDBMS Exercises

1. What do you mean by database constraint? Describe all different types of database constrants.

2. Consider the following relational schema and briefly answer the question that follow
   * Employees(id: integer, name: string, age: integer, salary: real, department_id: integer)
   * Works(id: integer, employee_id: integer, department_id: integer, pct_time: integer)
   * Departments(id: integer, budget: real, managerid: integer)
   Create and Define foreign key constraints. Consider the same relational schema for Question no 3 to 7.

3. Write SQL Query to find second highest salary of Employee.

4. Write SQL Query to find Max Salary from each department.

5. Write SQL Query to print the name of the distinct employee whose DOB is between 01/01/1960 to 31/12/1975.

6. Write SQL Query to find an employee whose Salary is equal or greater than 10000.

7. find all Employee records containing the word "Joe", regardless of whether it was stored as JOE, Joe, or joe.

8. What are Advantages and Disadvantages of DBMS?

9. A software contract and consultancy firm maintains details of all the various projects in which its employees are currently involved.
These details comprise:
   * Employee Number
   * Employee Name
   * Date of Birth
   * Department Code
   * Department Name
   * Project Code
   * Project Description
   * Project Supervisor

  Assume the following:
   * Each employee number is unique.
   * Each department has a single department code.
   * Each project has a single code and supervisor.
   * Each employee may work on one or more projects.
   * Employee names need not necessarily be unique.
   * Project Code, Project Description and Project Supervisor are repeating fields.
Normalise this data to Third Normal Form. and writedown required SQL for creating the schema.

10. Write an SQL Query to find  the year from date.

11. What is indexing and what are the different kinds of indexing?

12. What are the types of join and explain each?
