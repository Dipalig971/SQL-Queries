# SQL-Queries

Employee Database Management
This README file provides details about SQL commands used for managing an employee database. These commands include inserting new employee records, updating existing records, deleting records, and retrieving specific data from the database.

SQL Commands
Inserting a New Employee Record
The following command inserts a new employee record into the EMPLOYE table.

## sql
```
INSERT INTO EMPLOYE(name, role, salary, age, address, phone)
VALUES("DIPALI GUNJAL", "MANAGER", 60000, 19, "OM NAGAR DINDOLI SURAT", 8347910240);
VALUES("ANJALI PUROHIT", "MANAGER", 70000, 21, "MANGALAM DINDOLI SURAT", 9876543212);
VALUES("DRASHTI PATEL", "CEO", 90000, 19, "UMIYA NAGAR DINDOLI SURAT", 9765443321);
VALUES("MESHVA PATEL", "CEO", 10000, 20, "UMIYA PARK DINDOLI SURAT", 8976534211);
VALUES("KASHISH PATIL", "ACCOUNTER", 70000, 18, "UMA NAGAR DINDOLI SURAT", 9879543212);


```
## sql
```
Updating an Employee Record
UPDATE EMPLOYE SET phone = "9765443321" WHERE id = 3;

```
## sql
```
Deleting an Employee Record
DELETE FROM EMPLOYE WHERE name = "KASHISH PATIL";

```
## sql
```
Retrieving All Employee Records
SELECT * FROM EMPLOYE;

```
## sql
```
Retrieving Distinct Employee Names
SELECT DISTINCT name FROM EMPLOYE;

```
## sql
```
Retrieving Distinct Employee Salaries
SELECT DISTINCT salary FROM EMPLOYE;

```
## sql
```
Retrieving Employees by Role
SELECT * FROM EMPLOYE WHERE role LIKE "MANAGER%";

```
## sql
```
Retrieving Employees by Name Pattern
SELECT * FROM EMPLOYE WHERE name LIKE "AN%";

```
## sql
```
Retrieving Employees by Age and Salary
SELECT * FROM EMPLOYE WHERE age > 19 AND salary > 60000;
