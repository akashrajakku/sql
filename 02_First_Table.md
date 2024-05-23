## Creating my First Table in MYSQL Workbench

### STEP 1 : Create a Database
```
CREATE DATABASE db;

```
> note:  SQL is generally case-insensitive. That means you could write your SQL keywords in any case and the database engine will interpret them correctly. All of these will produce the same result, regardless of the case used in the keywords. But in general we use "caps" for ease and uniformity across code.

### STEP 2 : specify which Database we are using 
```
USE db;

```

### STEP 3 : Create a Table
```
CREATE TABLE dbTable(
    attribute_name attribute_type
);
```

```
CREATE TABLE student(
    id int PRIMARY_KEY,
    name VARCHAR(255)
);
```

### STEP 4 : Insert Values
```
INSERT INTO student 
    VALUES(1, 'Akash');

```

### STEP 5 : Selecting and printing whole table
```
SELECT * from student ;

```

>NOTE: We can also use sql queries via CLI (Command Line Interface), it will work the same and all queries remains the same as while using MYSQL workbench