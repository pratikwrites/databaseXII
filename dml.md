# Data Manipulation Language (DML)
---

## Background

Data Manipulation Language (DML) is a subset of SQL used for managing and manipulating existing data in a relational database. It is that component of SQL which controls the access to the data and database.

## Key Concept

**DML** commands are used to alter the data and database. These commands are necessary to ensure the relevancy of using database and to manipulate data as per the need.

### Some of the key DML statements:
* INSERT 
* UPDATE
* DELETE  

## 1. INSERT Statement
> It is used to add or insert new data into the database table.

### Syntax
```sql
INSERT INTO table_name (column1,column2,...)
VALUES (value1,value2,...);
```
### Example
```sql
INSERT INTO library (Name,Author,Price)
VALUES ("Muna Madan","Laxmi Prasad Devkota",135);
```

## 2. UPDATE Statement
> It is used to update or modify the existing data from the database table.

### Syntax
```sql
UPDATE table_name SET column1=value1, column2=value2
WHERE condition;
```
### Example
```sql
UPDATE library SET Name="LXD"
WHERE Price=135;
```

## 3. DELETE STATEMENT
> It is used to delete data from the database.

### Syntax
```sql
DELETE FROM table_name
WHERE Condition;
```

### Example
```sql
DELETE FROM library
WHERE Price=135;
```
---

## CONCLUSION
Data Manupulation Language (DML) commands and statments are the fundamental tools for manupulating and managing the data in the database which is the key component of a relevant database.