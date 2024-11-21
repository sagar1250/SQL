# SQL

At the end of the course, I will learn SQL concepts like SQL Queries, SQL joints, SQL Injection, SQL Insert and creating tables in SQL.

To learn SQL no prior experience is required. Anyone can learn easily. 

## SQL -- > Structured query Language

SQL is a standard database language used to access and manipulate data in the database.

IBM computer scientists develop SQL in the 1970s

based on executing SQL queries  we can Create, update, Delete, and retrieve Data in the database like MySQL, Oracle, PostgreSQL, etc.

Finally, SQL is a query language that communicates with databases.

### What is a Database?

Before going into what is database we should know that Data is unrecognised information, so to organise that data we make a Database.

if we split Database into two parts we get

Data - information of a particular person or a thing.
Base - base is like a backbone, i would explain you clearly with an example, when we construct a building we first make sure that basement is strong so that our building can be constructed in a proper and last longer from external vulnerabilities.

from the above context we came to some conclusion that to store any thigng or to stay any where we require shelter, to protect ourselfs and to be organised.

in the same way, to store data we are using a base which is a DBMS which we can call as Database Management System. this DBMS will controlled the structured data.

Database helps us to easily store, access, and manipulate data on a computer.


### Date: 21-11-2024

SQL example:

we will take a real world example and understad clearly about it.
t
We are taking Employee data with in a database, we will create a table and store employee information and other fields like 

Employeee_id, Name, Age, Department, Salary.

1 Sagar   23  SDE-1 5000000
2 Karthik 21  SDE-1 1cr
3 raju    23  DS    5000000
4 ravi    23  QA    4500000
5 Sunny   22  CEO   5cr

If we want to retrieve data foe the above example, the employee whos salary is grater than 5000000

So, we will use SELECT Statement.

Query:

SELECT * from employees WHERE Salary > 5000000.00;

based on the above query we will get as below

2 Karthik 21 SDE-1 1cr
5 Sunny   22 CEO   5cr

we will explain in detailed way on the above Query:

"SELECT *from Employees WHERE Salary > 5000000.00;"

SELECT, it tries to retrieve the records from the salary column which is greater than 5000000.00 in the Employees table.

*, It will tell that it wants to retrieve all columns for matching records in the Employees table.

WHERE clause, This WHERE clause filters the results based on the specified condition.






