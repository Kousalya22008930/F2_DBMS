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
### 1) Create a table student with the following fieds rollno,name,age,address,phoneno.

### SQL QUERY: 
```sql
create table studenttable(rollno number,name varchar(25),age number,address varchar(25),phno varchar(20));
```

### OUTPUT:
![image](https://github.com/Kousalya22008930/F2_DBMS/assets/119389108/a580bf71-26c1-4b11-993f-7e1968591a33)


### 2) Change the above student table by adding another attribute department

### SQL QUERY: 
```sql
alter table studenttable add dept varchar(25);
```

### OUTPUT:
![image](https://github.com/Kousalya22008930/F2_DBMS/assets/119389108/50acdd9a-82d9-403c-a5f3-2cc70caeedfe)



### 3) Drop the student table
 
### SQL QUERY: 
```sql
drop table mystudenttable;
```

### OUTPUT:
![image](https://github.com/Kousalya22008930/F2_DBMS/assets/119389108/324eef61-a62b-459a-b189-43d8f8a92a31)


### 4) Delete the student table using truncate keyword

### SQL QUERY: 
```sql
truncate table studenttable;
```

### OUTPUT:
![image](https://github.com/Kousalya22008930/F2_DBMS/assets/119389108/37fd363a-6b60-4d37-809d-a95aa9aa3172)



### 5) Rename the student table to mystudent

### SQL QUERY: 
```sql
alter table studenttable
rename to mystudenttable;
```
### OUTPUT:
![image](https://github.com/Kousalya22008930/F2_DBMS/assets/119389108/7bb52aca-4cec-49e3-8790-d0976bd7b7c0)
