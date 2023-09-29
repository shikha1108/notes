# SQL commands

## Mysql


### How to install mysql on mac.
```shell
`$brew install mysql`                  # we use this command to install mysql database in our local machine.

`$brew services start mysql`           # we us ethis command to start mysql in our local machine.
```
### how to log in in mysql.
```shell
`$mysql -u root`                       # this command will log into mysql server.
```
### how to create database.
```shell
`mysql>create database student`          #this query will create a database.
```

 ### how to select data of the table.
 ```shell
`mysql>select * from student`        #
 ```

### how to create a table.
```shell
 CREATE TABLE student (
    StudentID INT PRIMARY KEY,
    Name VARCHAR(100),
    Age INT,
    Address VARCHAR(255)   #this query will create this table
);
```

### How to insert data in a table.
```shell
INSERT INTO student (StudentID, Name, Age, Address)
VALUES
    (1, 'Abhi', 20, '123 Main St, USA'),
    (2, 'Sara', 22, '456 Elm St, USA');   #this query will insert data in the above table
```
 
### how to drop DB.
```shell
 `drop database student`
 ```

### how to backup DB
```shell
 `backup database student
 to disk = ~/Downloads/backupstudentdata.txt` 
```
 

### how to find unique data(distinct)
```shell
`select distinct Name, Age from student;`                #this command will find and display distinct(unique)student deatils.


`select distinct Name, Age from student asc/desc;`      #this command will display find and distinct(unique)student deatils with asending or desending order.


```

### how to sort data(order by)
`select cloumn1, column2 from table_name
order by column1, column2`

### how to update exiting table data
`update tabel_name
set column1 = value1, column2
where customer_name = shi;`

### delete

* how to  delete all data of one person in a table
`delete from table_name where customer_name = ''shi;`
* delete all records
`delete from table_name;`
* delete a table 
`drop table tbale_name;`

### how to find min
`slesct min(column_name)
from table_name;`

### how to find max
`slesct max(column_name)
from table_name;`

### how to count 
`select count(*)
from products`
### count with where clause
`select count(colunm_name)
from tabel_name
where condition = any`
### count distinct in a column
`select count(distinct condition)
from tabel_name;`  






 