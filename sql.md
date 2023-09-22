# SQL commands

## Mysql


* How to install mysql on mac.
`brew install mysql`
`brew services start mysql`

* how to log in in mysql.
`mysql -u root`

 * how to select data of the table.
 `select * from table_name`

 * how to create database.
 `create database database_name`

 * how to drop DB.
 `drop database database_name`

 * how to backup DB
 `backup database batabase_name
 to disk = ~/Downloads/file_name`
 
 * how to create a table.
 `CREATE TABLE table_name (
    column1 datatype,
    column2 datatype,
    ...
);`

* How to insert data in a table.
INSERT INTO table_name (column1, column2, ...)
VALUES (value1, value2, ...);

* how to find unique data(distinct)
`select distinct column1, cloumn2
from table_name; or from tabel_name asc/desc;`

* how to sort data(order by)
`select cloumn1, column2
from table_name
order by column1, column2`

* how to update exiting table data
`update tabel_name
set column1 = value1, column2
where customer_name = shi;`

## delete

* how to  delete all data of one person in a table
`delete from table_name where customer_name = ''shi;`
* delete all records
`delete from table_name;`
* delete a table 
`drop table tbale_name;`

* how to find min
`slesct min(column_name)
from table_name;`

* how to find max
`slesct max(column_name)
from table_name;`

* how to count 
`select count(*)
from products`
* count with where clause
`select count(colunm_name)
from tabel_name
where condition = any`
* count distinct in a column
`select count(distinct condition)
from tabel_name;`  






 