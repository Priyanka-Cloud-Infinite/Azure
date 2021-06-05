# Azure
Azure Data Factory Assignment

------------- Table creation-------------<br/>
create table employee (EmployeeId INT,  fname VARCHAR(64),lname VARCHAR(64),num int);<br/>
create table payroll(EmployeeId INT,  fname VARCHAR(64),lname VARCHAR(64), payrate int);<br/>
create table destination(EmployeeId INT,  fname VARCHAR(64),lname VARCHAR(64));<br/>

---------------list of table------------------<br/>

SELECT * from employeedb.INFORMATION_SCHEMA.tables where table_type='BASE TABLE'
