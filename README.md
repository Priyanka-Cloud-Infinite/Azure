# Azure
Azure Data Factory Assignment

------------- Table creation-------------
create table employee (EmployeeId INT,  fname VARCHAR(64),lname VARCHAR(64),num int);
create table payroll(EmployeeId INT,  fname VARCHAR(64),lname VARCHAR(64), payrate int);

create table destination(EmployeeId INT,  fname VARCHAR(64),lname VARCHAR(64));

---------------list of table------------------

SELECT * from employeedb.INFORMATION_SCHEMA.tables where table_type='BASE TABLE'
