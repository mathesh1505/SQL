# SQL
# 1 Relational Database Sysytem:
A Relational Database Management System (RDBMS) is a type of database that stores data in the form of tables (rows and columns) and allows you to define relationships between those tables.
# 2 Database Management System:
It is software that helps you store, organize, and manage data efficiently in a structured way.
# 3 SQL Syntax:
SQL syntax is the set of rules that define how SQL statements are written and executed to interact with a database.It’s like grammar for the SQL language.
# 4 DDL:
DDL stands for Data Definition Language.It deals with defining and managing the structure of database objects.
# 4.1 CREATE	
Creates a new database or table
<img width="1104" height="627" alt="Screenshot 2025-10-23 103847" src="https://github.com/user-attachments/assets/6b4d1147-6400-4fd1-9ac4-742e88b5d195" />
 
# 4.2 ALTER	
Modifies an existing database object
<img width="1104" height="628" alt="Screenshot 2025-10-23 103952" src="https://github.com/user-attachments/assets/3bc461cf-2dd8-4d37-913f-89c6d04743d5" />

# 4.3 DROP	
Deletes a database or table permanently
<img width="1064" height="494" alt="Screenshot 2025-10-23 103719" src="https://github.com/user-attachments/assets/0a3c8192-775f-4d95-8449-bde2c90dc599" />

# 4.4 TRUNCATE	
Removes all data from a table (structure remain
<img width="1147" height="596" alt="Screenshot 2025-10-23 104840" src="https://github.com/user-attachments/assets/cd0dfd9c-0b8a-4c26-bd59-46b6c7dfa1f5" />


# 5 DML:
DML stands for Data Manipulation Language.It is used to manipulate the data stored inside database tables that means adding, changing, and deleting records.

# 5.1 INSERT	
Adds new records to a table.
<img width="1039" height="556" alt="Screenshot 2025-10-23 105918" src="https://github.com/user-attachments/assets/b7ece8e0-22eb-4f2f-a8e5-f1f4bd4995f0" />

# 5.2 UPDATE
Modifies existing records.
<img width="1233" height="594" alt="Screenshot 2025-10-23 110659" src="https://github.com/user-attachments/assets/48e3f0fe-3f8b-47e0-866d-bb814f5a1cda" />

# 5.3 DELETE	
Removes records from a table.

<img width="978" height="604" alt="Screenshot 2025-10-23 110912" src="https://github.com/user-attachments/assets/57ff8391-28ac-4345-ac8d-358b1897cb29" />

# 5.4 SELECT  
Statement retrieves data from one or more tables.

<img width="618" height="212" alt="Screenshot 2025-10-23 111110" src="https://github.com/user-attachments/assets/6db04363-d02a-46b3-8bff-167e8c278923" />
# 6 DCL (Data Control Language):
It is used to control access to the data in the database who can view, modify, or manage data.In simple words, DCL commands deal with database security and user permissions.

# 6.1 GRANT	
Gives permission to a user to perform actions
# 6.2 REVOKE	
Removes permission from a user
# 7 DQL (Data Query Language):
It is used to fetch or retrieve data from the database.
* SELECT 	Used to retrieve data from one or more tables
# 7.1 Aggregating data
# 7.1.1 COUNT()	
Counts the number of rows	COUNT(id)
<img width="775" height="477" alt="Screenshot 2025-10-23 180632" src="https://github.com/user-attachments/assets/5bfd4ddf-626a-46e5-9a29-d10124f3a66f" />

# 7.1.2 SUM()	
Adds up numeric values	SUM(marks)

<img width="704" height="475" alt="Screenshot 2025-10-23 180605" src="https://github.com/user-attachments/assets/a70c2fc9-f0c7-4bfc-a8d3-763cec578118" />

# 7.1.3 AVG()	
Returns the average value	AVG(marks)
<img width="787" height="474" alt="Screenshot 2025-10-23 180651" src="https://github.com/user-attachments/assets/85b958f0-c5a8-448d-8be9-5a7a065a29a6" />

# 7.1.4 MIN()
Returns the smallest value	MIN(marks)
<img width="759" height="493" alt="Screenshot 2025-10-23 180450" src="https://github.com/user-attachments/assets/f20d14fc-c8b0-442a-ab25-d1c204bf2e20" />

# 7.1.5 MAX()	
Returns the largest value MAX(marks)
<img width="767" height="521" alt="Screenshot 2025-10-23 180535" src="https://github.com/user-attachments/assets/38af0f97-9852-4cd5-8b2f-a76a9e78cf8a" />

# 7.2 Group by:
The GROUP BY clause is used to group rows that have the same values in one or more columns.It is usually used with aggregate functions like SUM(), COUNT(), AVG(), MAX(), MIN() to summarize data.
<img width="922" height="572" alt="Screenshot 2025-10-23 180325" src="https://github.com/user-attachments/assets/b4e1db80-4d80-4f15-924c-7bcde1701085" />
# 7.3 Having clause:
The HAVING clause in SQL is used to filter groups of records created by the GROUP BY clause.Unlike WHERE, which filters individual rows, HAVING filters aggregated data (like SUM, COUNT, AVG, MAX, MIN).
<img width="814" height="517" alt="Screenshot 2025-10-23 182210" src="https://github.com/user-attachments/assets/b59f2505-27f7-4f59-a53e-f7bcdcf0e759" />

# 7.4 Order by:
The ORDER BY clause is used to sort the result set of a query.By default, it sorts in ascending order (ASC). You can also sort in descending order (DESC).It can sort by one or more columns.

<img width="668" height="606" alt="Screenshot 2025-10-23 180753" src="https://github.com/user-attachments/assets/4fc5ee6d-387d-42e4-ad54-d855e4fa1f7e" />

# 8 TCL(Transcation Control Language):
TCL stands for Transaction Control Language.It is used to manage transactions in SQL.

# 8.1 COMMIT	
Saves all the changes made in the current transaction permanently.
<img width="1017" height="717" alt="Screenshot 2025-10-24 103628" src="https://github.com/user-attachments/assets/939eb848-e5bb-41b5-a7ff-3a56e43caf4c" />

# 8.2 ROLLBACK	
Undoes all the changes made in the current transaction.
<img width="851" height="665" alt="Screenshot 2025-10-24 104352" src="https://github.com/user-attachments/assets/236e8f6b-e414-4e23-a7d3-c9386cf40ac0" />

# 8.3 SAVEPOINT	
Creates a point within a transaction to which you can later roll back.
<img width="857" height="683" alt="Screenshot 2025-10-24 104858" src="https://github.com/user-attachments/assets/2daf0ace-9a9d-4950-8b7d-292417f4b15c" />

# 9 Constraints: 
Constraints are rules applied to table columns to enforce data integrity.They ensure the accuracy and reliability of the data in the database.Constraints can be applied when creating a table or altering a table.

# 9.1 NOT NULL	
Ensures that a column cannot have NULL values.
# 9.2 UNIQUE	
Ensures that all values in a column are unique.
# 9.3 PRIMARY KEY	
Uniquely identifies each row in a table. Cannot be NULL.
# 9.4 FOREIGN KEY	
Ensures the value in a column matches a value in another table, enforcing referential integrity.
# 9.5 CHECK	
Ensures that column values meet a specific condition.
# 10 JOINS:
A JOIN in SQL is a clause that retrieves data by linking rows from multiple tables based on a common column.To combine related data from different tables,avoid data duplication (normalize the database) and retrieve meaningful results by connecting tables.
# We using these two tables:
<img width="882" height="852" alt="Screenshot 2025-10-24 223057" src="https://github.com/user-attachments/assets/4b30b2c9-6abb-4d90-9187-31cd4783472b" />

# 10.1 INNER JOIN:
Returns only the rows that have matching values in both tables.
<img width="1069" height="644" alt="Screenshot 2025-10-24 182039" src="https://github.com/user-attachments/assets/d4144c2c-d259-40b7-ba6d-1dc1d77333cb" />
# 10.2 LEFT JOIN:
Returns all rows from the left table and matching rows from the right table. If there’s no match, it shows NULL for the right table columns.
<img width="935" height="688" alt="Screenshot 2025-10-24 182125" src="https://github.com/user-attachments/assets/3d55915b-5e3a-49a9-b6a6-f9633abd9fb9" />
# 10.3 RIGHT JOIN:
Returns all rows from the right table and matching rows from the left table. If there’s no match, it shows NULL for the left table columns.
<img width="974" height="686" alt="Screenshot 2025-10-24 182159" src="https://github.com/user-attachments/assets/a22c0210-2b77-44a8-a924-dadfbcaa5d89" />
# 10.4 FULL JOIN:
Returns all rows from both tables. Rows without a match in the other table will show NULL.
<img width="857" height="657" alt="Screenshot 2025-10-24 182237" src="https://github.com/user-attachments/assets/532cc4a5-7342-4bd9-9999-a53fac0296c9" />
# 10.5 CROSS JOIN:
Returns all possible combinations of rows from both tables (Cartesian product).
<img width="987" height="864" alt="Screenshot 2025-10-24 182926" src="https://github.com/user-attachments/assets/8b17ad76-f6b2-4cfb-8aa7-39f05eb8e621" />
# 11 SQL Operator:
An SQL operator is a symbol or keyword used to perform operations on data in SQL queries. Operators are used in conditions, calculations, and logical expressions to filter, compare, or manipulate data.
# 11.1 Arithmetic Operators:
Used for mathematical calculations like Addition,Subtraction,Multiplication and Division .
<img width="992" height="735" alt="Screenshot 2025-10-24 185346" src="https://github.com/user-attachments/assets/0626846b-5b91-432d-b43b-3d1a39c858f4" />

# 11.2 Comparison Operators:
Used to compare values in conditions.
* =	Equal to	WHERE Salary = 50000
* != or <>	Not equal to	WHERE Salary <> 50000
* >	Greater than	WHERE Salary > 50000
* <	Less than	WHERE Salary < 50000
* >=	Greater than or equal to	WHERE Salary >= 50000
* <=	Less than or equal to	WHERE Salary <= 50000
<img width="750" height="571" alt="Screenshot 2025-10-24 190128" src="https://github.com/user-attachments/assets/c6704ba3-202e-4e78-ab8a-7310593ad7d2" />
<img width="781" height="590" alt="Screenshot 2025-10-24 190111" src="https://github.com/user-attachments/assets/ecb6e478-453f-4cfa-9008-a1747fcb419c" />
<img width="851" height="588" alt="Screenshot 2025-10-24 185857" src="https://github.com/user-attachments/assets/18202d8b-ee28-43ee-8287-63fe9d2362e1" />

# 11.3 Logical Operator:
Used to combine multiple conditions.
# AND
Both conditions must be true	WHERE DeptID = 101 AND Salary > 50000
<img width="970" height="624" alt="Screenshot 2025-10-24 190722" src="https://github.com/user-attachments/assets/27a11a0a-e1df-4f8c-af6f-263bb149b820" />
# OR
Either condition can be true	WHERE DeptID = 101 OR Salary > 50000
<img width="923" height="616" alt="Screenshot 2025-10-24 190743" src="https://github.com/user-attachments/assets/3ce37dca-ad8a-4e93-991f-9946a23361d8" />
# NOT
Negates the condition	WHERE NOT DeptID = 101
<img width="957" height="633" alt="Screenshot 2025-10-24 190833" src="https://github.com/user-attachments/assets/85f18419-cde9-4abc-8234-6c19dca601ac" />
# CONCAT
<img width="900" height="658" alt="Screenshot 2025-10-24 223507" src="https://github.com/user-attachments/assets/b5907c21-4637-4f9b-ae1b-dd9a728651d3" />

# 12 Procedures:
A Stored Procedure in SQL is a precompiled group of SQL statements (like SELECT, INSERT, UPDATE, etc.) that are stored in the database and can be executed whenever needed.It helps improve performance, reusability, security, and modularity in database operations.
# Create prcedure:
Used to create a new stored procedure for the first time.
# ALTER PROCEDURE:
Used to modify or update an existing stored procedure (instead of dropping and recreating it).
# DROP PROCEDURE:
Used to delete (remove) an existing stored procedure permanently.
# EXECUTE Procedure:
Used to run (or call) a stored procedure.
# 13 Subquery:
A subquery is a query inside another query — it can be in the SELECT, FROM, or WHERE clause.
<img width="1255" height="883" alt="Screenshot 2025-10-27 174412" src="https://github.com/user-attachments/assets/fdc66708-51bc-4e93-a6cb-63b099ec51cb" />
# CTE:
A CTE is like a named temporary result set that exists only for the duration of a single query.It makes queries cleaner, reusable, and easier to read compared to subqueries.
# Views:
A View is a virtual table that is based on the result of an SQL query.It doesn’t store data physically, but instead stores a query that pulls data from one or more tables.So, when you query a view, SQL runs the query behind the scenes and shows you the result like a table.
# Create view:
The CREATE VIEW command is used to create a virtual table based on the result of a SQL query.
# DROP VIEW:
Used to delete a view permanently from the database.
