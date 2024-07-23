# SQL-Queries

Employee Database Management
This README file provides details about SQL commands used for managing an employee database. These commands include inserting new employee records, updating existing records, deleting records, and retrieving specific data from the database.

SQL Commands
Inserting a New Employee Record
The following command inserts a new employee record into the EMPLOYE table.

## sql
```
INSERT INTO EMPLOYE(name, role, salary, age, address, phone)
VALUES("KASHISH PATIL", "ACCOUNTER", 70000, 18, "UMA NAGAR DINDOLI SURAT", 9879543212);
Updating an Employee Record

```
## sql
```
UPDATE EMPLOYE SET phone = "9765443321" WHERE id = 3;
Deleting an Employee Record

```
## sql
```
DELETE FROM EMPLOYE WHERE name = "KASHISH PATIL";
Retrieving All Employee Records

```
## sql
```
SELECT * FROM EMPLOYE;
Retrieving Distinct Employee Names

```
## sql
```
SELECT DISTINCT name FROM EMPLOYE;
Retrieving Distinct Employee Salaries

```
## sql
```
SELECT DISTINCT salary FROM EMPLOYE;
Retrieving Employees by Role

```
## sql
```
SELECT * FROM EMPLOYE WHERE role LIKE "MANAGER%";
Retrieving Employees by Name Pattern

```
## sql
```
SELECT * FROM EMPLOYE WHERE name LIKE "AN%";
Retrieving Employees by Age and Salary

```
## sql
```
SELECT * FROM EMPLOYE WHERE age > 19 AND salary > 60000;
