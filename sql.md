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
    (1, 'Elle', 20, '123 Main St, USA'),
    (2, 'Bob', 22, '456 Elm St, USA');   #this query will insert data in the above table
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
```shell
`select * from student            # we can also give column name here
order by Name asc, Age asc;`       #  this query will order(sort)the student table by their column
```

### how to update exiting table data
```shell
`UPDATE Students
SET Age = 25, Address = 'New Address'
WHERE Name = 'Bob';`      # this query will update bob record in this table.
```
### delete

* how to  delete all data of one person in a table
```shell
`delete from student where Name = 'Sara';`  #this query will delete all record(data) of the given student.

* delete all records
`delete from student`  #this query will delete all ecords(data) from student table.

* delete a table
`drop table student;` #this query will delete student table.

* delete a column
`alter table Students
drop column Address`    #this query will delete address column from student table
```

### how to find min
```shell
`slect min(Age)
from student;`        #this query will find min age from the student table 
```

### how to find max
```shell
`slect max(age)
from student;`                #this query will find max age from the student table 
```

### how to count 
```shell
`select count(*)
from products`    # count with where clause
`select count(colunm_name)
from tabel_name
where condition = any` # count distinct in a column
`select count(distinct condition)
from tabel_name;`
```  






 