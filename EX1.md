# EXP NO 1: DATA DEFINITION LANGUGE COMMANDS IN RDBMS

## AIM:
To create a student database and execute DDL queries using SQL.
## DDL (Data Definition Language)
<div align="justify">
DDL or Data Definition Language actually consists of the SQL commands that can be used to define the database schema. It simply deals with descriptions of the database schema and is used to create and modify the structure of database objects in the database. DDL is a set of SQL commands used to create, modify, and delete database structures but not data. These commands are normally not used by a general user, who should be accessing the database via an application.
</div>
 
## List of DDL commands: 
<div align="justify">
CREATE: This command is used to create the database or its objects (like table, index, function, views, store procedure, and triggers).
DROP: This command is used to delete objects from the database.
ALTER: This is used to alter the structure of the database.
TRUNCATE: This is used to remove all records from a table, including all spaces allocated for the records are removed.
RENAME: This is used to rename an object existing in the database.
</div>

## Query:
```
Developed by :Kowsalya M
Register no: 212222230069
```
### 1) Create a table student with the following fieds rollno,name,age,address,phoneno.
### SQL QUERY: 
```
create table student(rollno int,name char(20),age int,addr varchar(20),phoneno int);
```
### OUTPUT:
![270861020-d4078461-29d3-4714-aa2b-d859b4552fa6](https://github.com/Kowsalyasathya/G2_DBMS/assets/118671457/62f638ee-ed52-48f4-ac2e-b07f7eb3927f)

### 2) Change the above student table by adding another attribute department
### SQL QUERY: 
```
alter table student add department char(30);
```
### OUTPUT:
![270861141-2c22e52a-f697-4647-8c27-19b5dbb87d15](https://github.com/Kowsalyasathya/G2_DBMS/assets/118671457/41d7d9e8-5514-4453-a090-802d1c2ea72e)

### 3) Drop the student table
### SQL QUERY: 
```
drop table student;
```
### OUTPUT:
![270861215-d0c90400-b82a-4d48-898f-1d18b60f2f8a](https://github.com/Kowsalyasathya/G2_DBMS/assets/118671457/4b1d163d-29c2-4958-87aa-24335dd20e06)
### 4) Delete the student table using truncate keyword
### SQL QUERY: 
```
truncate table student;
```
### OUTPUT:
![270861260-a7cf6059-f7e7-4b7f-9db9-8e45b0246324](https://github.com/Kowsalyasathya/G2_DBMS/assets/118671457/77bde348-71a4-423f-be44-aeaa878d2a57)
### 5) Rename the student table to mystudent
### SQL QUERY: 
```
alter table student rename to mystudent;
```
### OUTPUT:
![270861345-9d838847-3a92-4ec4-a2e6-a98d06085ad0](https://github.com/Kowsalyasathya/G2_DBMS/assets/118671457/8bc62eb3-d15d-4284-a195-cb150f267fc1)
## RESULT:
To create a student database and execute DDL queries using SQL is executed successfully.
