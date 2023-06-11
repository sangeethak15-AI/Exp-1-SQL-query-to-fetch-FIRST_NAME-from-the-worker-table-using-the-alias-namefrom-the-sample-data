# Exp-1-SQL-query-to-fetch-FIRST_NAME-from-the-worker-table-using-the-alias-namefrom-the-sample-data

## AIM:
To fetch first name from sample work table using alias naming in SQL.

## ALGORITHM:

STEP 1: Create a sample table in SQL using CREATE TABLE syntax

STEP 2: Insert all the values and Titles respectively using INSERT INTO syntax

STEP 3: Now check whether all the rows are affected or not by fetching the table

STEP 4: After checking, now we can use alias naming for fetching First_Name 
column from the EMPLOYEE table

STEP 5: We can use its syntax ,SELECT Alias_name AS Alias_variable_name for 
fetching the column.The results will be displayed accordingly.

## PROGRAM:
```
create table Employee(
  First_name varchar(50),
  Last_name varchar(50),
  Age int
);
insert into Employee (First_name, Last_name,Age)
values ('Wade','Smith',25);
insert into Employee (First_name, Last_name,Age)
values ('Dave','Johnson',27);
insert into Employee (First_name, Last_name,Age)
values ('Williams','Brown',28);
insert into Employee (First_name, Last_name,Age)
values ('Walker','Jones',24);
insert into Employee (First_name, Last_name,Age)
values ('Scott','Garcia',30);
insert into Employee (First_name, Last_name,Age)
values ('Alberta','Miller',35);
insert into Employee (First_name, Last_name,Age)
values ('Lynda','Rodriguez',32);
insert into Employee (First_name, Last_name,Age)
values ('Sandra','Martinez',29);
insert into Employee (First_name, Last_name,Age)
values ('Rosie','Davis',24);
insert into Employee (First_name, Last_name,Age)
values ('Atalie','Williams',25);

select First_name as fn from Employee;
```
## OUTPUT:
![image](https://github.com/sangeethak15-AI/Exp-1-SQL-query-to-fetch-FIRST_NAME-from-the-worker-table-using-the-alias-namefrom-the-sample-data/assets/93992063/445a1808-ec71-4bc4-bbb5-18d8a45fb76c)


## RESULT:
Thus we have obtained the required column using alias.
