# SQL commands

## Mysql


### How to install mysql on mac.
```shell
$brew install mysql                  # we use this command to install mysql database in our local machine.

$brew services start mysql           # we use this command to start mysql in our local machine.
```
### how to log in in mysql.
```shell
$mysql -u root                       # this command will login into mysql server.
```
### how to create database.
```shell
mysql>create database school;         #this query will create a database.
```

### how to create a table.
```shell
mysql>create table student (
    INT PRIMARY KEY,
    Name VARCHAR(100),
    Age INT,
    Address VARCHAR(255)   #this query will create this table
);
```

### How to insert data in a table.
```shell
mysql>insert into student (StudentID, Name, Age, Address)
VALUES
    (1, 'Elle', 20, '123 Main St, USA'),
    (2, 'Bob', 22, '456 Elm St, USA');   #this query will insert data in the above table
```

  ### how to select data of the table.
 ```shell
mysql>select * from student;      #this query will display the record of student table
 ```

### how to find unique data(`distinct`)
```shell
mysql>select distinct Name, Age from student;               #this command will find and display distinct(unique)student deatils.

mysql>select distinct Name, Age from student asc/desc;     #this command will display find and distinct(unique)student deatils with asending or desending order.


```

### how to sort data(`order by`)
```shell
mysql>select * from student            # we can also give column name here
order by Name asc, Age asc;      #  this query will order(sort)the student table by their column
```

### how to `update` exiting table data
```shell
mysql>update student
set Age = 25, Address = 'New Address'
where Name = 'Bob';      # this query will update bob record in this table.
```

### how to find `min`
```shell
mysql>select min(Age)
from student;        #this query will find min age from the student table 
```

### how to find `max`
```shell
mysql>select max(age)
from student;                  #this query will find max age from the student table 
```

### how to `count` 
```shell
mysql>select count(*) from products;     # count with where clause
mysql>select count(colunm_name) from student
where condition = any     # count distinct in a column
mysql>select count(distinct condition)from tabel_name;
``` 

### `delete`

```shell
* how to  delete all data of one person in a table
mysql>delete from student where Name = 'Sara';    #this query will delete all record(data) of the given student.

* delete all records
mysql>delete from student;  #this query will delete all ecords(data) from student table.

* delete a table
mysql>drop table student; #this query will delete student table.

* delete a column
mysql>alter table Students
drop column Address;    #this query will delete address column from student table
```

### how to `drop DB`.
```shell
mysql>drop database student;
 ```

### how to `backup DB`
```shell
backup database student
to disk = ~/Downloads/backupstudentdata.txt
```







 