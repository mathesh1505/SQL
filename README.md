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





