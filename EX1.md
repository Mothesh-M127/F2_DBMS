# EXP NO 1: DATA DEFINITION LANGUGE COMMANDS IN RDBMS
### DATE:
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
### 1) Create a table student with the following fieds rollno,name,age,address,phoneno.

### SQL QUERY: 
```sql
create table student1 (rollno int,name char(20),age int,addr varchar(20),phoneno int);
```

### OUTPUT:
![11](https://github.com/Mothesh-M127/F2_DBMS/assets/94170892/0cbf9ab8-5f39-4440-9b3c-750d0709ba77)

### 2) Change the above student table by adding another attribute department

### SQL QUERY: 
```sql
 alter table student1 add department char(90);
```
### OUTPUT:
![12](https://github.com/Mothesh-M127/F2_DBMS/assets/94170892/3aae4d7e-f313-4f5c-b9b8-2bbcc00223b7)


### 3) Drop the student table
 
### SQL QUERY: 
```sql
drop table student1;
```

### OUTPUT:

![13](https://github.com/Mothesh-M127/F2_DBMS/assets/94170892/6a0a5f85-7cde-4d69-a8f7-0ddd7756327b)

### 4) Delete the student table using truncate keyword

### SQL QUERY: 
```sql
truncate table student1;
```

### OUTPUT:

![14](https://github.com/Mothesh-M127/F2_DBMS/assets/94170892/9699a92e-979a-48ca-9bdd-15a68c1502eb)


### 5) Rename the student table to mystudent

### SQL QUERY: 
```sql
alter table student rename to mystudent1;
```

### OUTPUT:
![15](https://github.com/Mothesh-M127/F2_DBMS/assets/94170892/67ea1553-e71b-4b0a-815c-10dfbd34349e)


### Result:
Thus the student database has been created and executed in DDL queries using SQL.
