### Service 
A service can be one of the java classes or it can also be a whole java service.

### Microservice Architecture
We divide our services into multiple smaller services known microservices. These micro services communicate to each other using REST apis.

There are many advantages of microservice architecture:
* It allows us to debug issues easily.
* If there is any issue with one service, other services keep running.
* They are easier to understand. So new joiners can quickly understand their logic.

But there are some disadvantages also:
* They are difficult to maintain.
* If there are multiple REST calls, the service can be slow sometimes.


### Monolithic Architecture
Monolithic architecture is the traditional approach to software design. In monolithic architecture entire application is developed as a single application/codebase. In this architecture components, modules, and functionalities are bundled together.

There are many advantages of monolithic architecture:
* It is easy to maintain.
* It is  very fast performance.

But there are some disadvantages also:
* If there is any issue with service. Entire application will stop.
* It is not easy to understand. When new joiner join company.

### Repository
Basically, we create a repo to store the data.
We create a Git repo for code review, and we also use a Spring repo.

### Framework
A framework is like a structure that provides a base for the application development process. 
With the help of a framework, you can avoid writing everything from scratch.

Frameworks provide many advantages such as:
* Easy to test our code and debug it.
* Clean code is much easy to understand and work with.
* Reduces the time and cost of the project with the enhanced application.
* Features and functionalities provided by the framework can be modified and extended.
* Such as Spring, Django, Flutter, Angular, Vue, PyTorch, Spring Boot, React Native, Apache Spark are the frameworks.


### Infrastructure
Cloud Infrasturcture, Operating Infrasturcture(macos, linux, windows), Networking Infrasturcture, Software Infrasturcture


### Shadowing
When we create a variable as a global and then we assign another value for this variable this process is known as shadowing in programming languages. The inner variable shadows the outer variable.
```java
# Outer scope variable.
x = 10

def shadowing_example():
    x = 5
    print("Inner x:", x)  # Prints the value of the inner variable.

# Call the function
shadowing_example()

# Outside the function, the outer variable is still accessible.
print("Outer x:", x)  # Prints the value of the outer variable.

```

### Hard coding
When we fixed the values of variables in our code.
```java
public class HardCodingExample {
    public static void main(String[] args) {
        String name = "Shikha";  // Hard-coded value
        System.out.println("The name of students is: " + name);
    }
}
```

### Generic

It is used in java. In generic type we can use String or Integer both or Double or any other 
type.
```java
class Test {
    // Driver method
    public static void main(String[] args)
    {
        // Calling generic method with Integer argument
        genericDisplay(11);
        genericDisplay("GeeksForGeeks");
        genericDisplay(1.0);
    }

     // A Generic method example
    static <T> void genericDisplay(T element)
    {
        System.out.println(element.getClass().getName()
                           + " = " + element);
    }
}
````

### Json format

Json is a way to write data. JSON data is represented as key-value pairs. 
Data is enclosed in curly braces '{}'. Key-value pairs are separated by colons.

```
{
  "firstname": "Shikha",
  "lastname": "Yadav",
  "age": 27
}
```

### Xml format

XML is a way to write data. It is also like HTML. It is a software tool for storing and transporting data.
We use xml format to write our pom file in java spring project.

stored as XML format:
```
<Person>
  <name>Shikha</name>
  <age>27</age>
</Person>
```

### Redirection
It is used to take the data from one direction to another.
We used to take the data from our files in our computers. 

### Fetch
We use in git. When we use git fetch command than, 
it can downloads changes from a remote repository to your local repository without automatically merging them into your working branch.


### Merging
When we create two branch and merge them.
```
git merge
```

### Refactoring
It is the process of restructuring existing code without changing its external behavior.

### Append
 The process of attaching or combining data with another file or set of data. 
 It is also used to concatenating linked lists or arrays in programming languages. 

### Rest Api's 

Rest Api is a way of sharing information between two servers.
It has several methods.
* Get:It is used to retrieve data.
* Post:It is used to post data to server.
* Patch:It Applies partial modifications to a resource. It is often used to update specific fields of an existing resource.
* Put:It Updates a specified resource with new data. It replaces the existing representation of the resource.
* Delete: It is used to delete the data.

### Response status code.

When you interact with a RESTful API, the server responds with an HTTP status code to indicate the success or failure of the request.
These status codes are three-digit numbers that provide information about the status of the HTTP request.
* 200 OK.
* 401 Unauthorized. 
* 400 Bad Request. 
* 404 Not Found. 
* 500 Internal Server Error.
* 503 Service Unavailable.

### Machines and ports
Machines are our computers and It is also a local server.
When a machine communicates with a network, It uses a port number to establish connections and exchange data with other machines. 


### Flyway
It is uesd to migrate datbase in DB.
It represents a specific change to the DB schema, such as creating a table, altering a column, or adding data.

### Null pointer Exception

Null pointer exception is a runtime exception. Null is a special kind of value that can be assigned to the reference of an object. Whenever one tries to use a reference that has the Null value, the NullPointerException will raise.

 ```java
public static void main(String[] args) {
    String name = null;
    System.out.println(name.length());
}
//Here, the variable 'name' is assigned the value null, and when we attempt to access the length of the name, the outcome will be a NullPointerException.
```


### Stacktrace
It is a list of the method calls that the application was in the middle of when an Exception was thrown.

### Exception handling
It is two types: 
Compile time exception and run time exception.

#### Compile time exception 
When we do the code. then it is occured
```java
string name = "shikha";
```

### Run time exception.
```java
public static void main(String[] args) {
    String name = null;
    System.out.println(name.length());
        System.out.println(name.read());

}
```

### Docker
It is a software platform that allows you to build, test, and deploy applications quickly using containers. 

### Kubernetes
It is used in deploying, managing, and scaling containerized applications.

### Jenkins
It is an used for building, testing, and deploying code.

### Client server architecture
Client is a user interface or application that requests services or resources, while the server is a powerful computer or set of computers that provide these services or resources.

### Heroku
It is used for developing and deploying apps that immediately start producing value.

### Ngnix
It is a web server.
Nginx is like a smart traffic manager for websites. 
It efficiently handles lots of visitors, prevent slowdowns, and can speed up websites by serving content quickly. and web applications can run smoothly.


### Webserver
It servees the request of the HTTP to the clients. Some webserves are the Apache web server, Apache Tomcat, Nginx, NodeJS.

### Domain Name
It is used to identify a specific IP address or a set of IP addresses on the internet. 
It provides a way for people to easily navigate to websites and other resources on the web.

### IP address
It is a unique number identifier that for each computer to connect the interet for communication data. There are IPv4 addresses like 192.168.11 and IPv6 addresses It is a lond unique number.


### Epoch
Epoch in computing can mean the starting point for measuring time (like January 1, 1970, in Unix) or a full cycle through a dataset during machine learning training.

### Design patterns
They are reusable in multiple projects.
They provide the solutions that help to define the system architecture.
They capture the software engineering experiences.
They provide transparency to the design of an application.
They are well-proved and testified solutions since they have been built upon the knowledge and experience of expert software developers.


### Hibernate and Jvm

### AWS
>Amazon Web Services (AWS) is a cloud computing platform provided by Amazon. It is a cloud services, computing power, storage, databases, machine learning, analytics, content delivery.

#### EC2 (Elastic Compute Cloud):
Amazon EC2 is a web service that provides resizable compute capacity in the cloud. 
It allows users to run virtual servers, known as "instances," in the AWS cloud. 
EC2 instances come in various types and sizes, each optimized for different use cases.
#### S3 (Simple Storage Service):
It is an object storage service that allows users to store and retrieve any amount of data at any time. 
It is designed for durability, scalability, and high-performance storage. 
Data is stored in containers called "buckets," and each object in a bucket is assigned a unique key.
#### CloudWatch:
Amazon CloudWatch is a monitoring and observability service for AWS resources and applications.
It provides data and actionable insights for monitoring the performance of applications, resources, and services in real-time.

### DATABASE 

#### DB ACID property
ACID stands for Atomicity, Consistency, Isolation, Durability.
> A transaction is a single logical unit of work that accesses and possibly modifies the contents of a database. Transactions access data using read and write operations. In order to maintain consistency in a database, before and after the transaction, certain properties are followed. are called ACID properties.
* **A stands for Atomicity**: The entire transaction takes place at once or does not happen at all.
* **C stands for Consistency**: The database must be consistent before an after transaction.
* **I stands for Isolation**: Multiple transactions can happen idependently.
* **D stands for Durabiltiy**: The changes of a succesful transaction occurs even if the system fails because of any issue.

#### Database Indexes
* Indexes are created to improve the speed of reading the data from a database table.
* We can create indexes on one or more columns of a table.
* Indexes use data structures like B+ trees.

> For example, if we have a table students, and we want to run the select query:
`SELECT * FROM STUDENTS WHERE NAME = 'BRUNO'`. It will be slower if there is no index on the table. But if we create and index on column **name**, it will become faster.

#### Connection pooling
DB maintains a “pool” of open connections.
It is a way to reduce the cost of opening and closing connections.
It passes connections from one database operation to another as needed. 
In one of my service we are using Hikari connection pooling.

##### SQL vs NoSQL
#### SQL
Stands for Structured Query Language. 
Suitable for structured data with predefined schema.
Data is stored in tables with columns and rows. 
Follows ACID properties (Atomicity, Consistency, Isolation, Durability) for transaction management.
Supports JOIN and complex queries. Uses normalized data structure. 
Requires vertical scaling to handle large volumes of data. 
Examples: MySQL, PostgreSQL, Oracle, SQL Server, Microsoft SQL Server.   
    
#### NoSQL
Stands for Not Only SQL.  
Suitable for unstructured and semi-structured data. 
Data is stored in collections or documents. 
Does not necessarily follow ACID properties.
Does not support JOIN and complex queries. 
Uses denormalized data structure. 
Horizontal scaling is possible to handle large volumes of data. 
Examples: MongoDB, Cassandra, Couchbase, Amazon DynamoDB,Redis.

##### Relational vs Non-Relational DB's

#### Relational DB
#### Non-Relational DB

##### Normalized vs Denormalized Data




### SOLID Principles
>It reduces the dependencies so that a block of code can be changed without affecting the other code blocks.
The principles intended to make design easier, understandable.
By using the principles, the system is maintainable, testable, scalable, and reusable.
It avoids the bad design of the software. 
* **S stands for Single Responsibility principle (SRP)**: Every Java class must perform a single functionality.
* Let's understand the single responsibility principle through an example.
* Suppose, Student is a class having three methods called printDetails(), calculatePercentage(), and addStudent(). Hence, the Student class has three responsibilities to print the details of students, calculate percentages, and add student. By using the single responsibility principle, we can separate these functionalities into three separate classes to fulfill the goal of the principle.
* **O stands for Open Closed Principle (OCP)**: The module should be open for extension but closed for modification.
* Suppose, Here, the Student class is closed for modification (you can add new grade calculators without changing Student), but it's open for extension by allowing different ways to calculate the average grade.
* **L stands for Lischov Substitude Principles (LSP)**:The objects of a superclass should be replaceable with objects of a subclass without affecting the correctness of the program.
* **I stands for Interface Segregation principles(ISP)**: A class should not be forced to implement interfaces it does not use.
* **D stands for Dependency Inversion Principle(DIP)**: High-level modules should not depend on low-level modules, but both should depend on abstractions.
 

### JAVA

#### Generics: 

* What: (If I have to talk about generics, I can say that Generics) provide a way to create classes, interfaces, and methods with type parameters.
* Why: (The biggest advantage of using generics is that) we can work with different types without sacrificing type safety.
* How: (Lets take an example, )
> if we write a method to search an element, then we can write like this:
```java
private static Boolean search(List<String> list, String key) {}
//we can write this using generics
private static <T> Boolean search(List<T> list, T key) {}
``` 

#### Garbage collection: 
* In Java is the process by which the Java Virtual Machine (JVM) automatically reclaims memory that is no longer in use by the program. Java uses an automatic garbage collector to manage memory, and this helps in preventing memory leaks and simplifies memory management for developers.

#### Functional Interface: 
* A functional interface is an interface that declares only one abstract method. 
It can still have multiple default or static methods, but it must have exactly one abstract method.

#### Java Releases:
* The lastest java release is JAVA 21.

#### Multithreading in JAVA: 
Multithreading in Java is a process of executing multiple threads simultaneously.
A thread is a lightweight sub-process, the smallest unit of processing. Multiprocessing and multithreading, both are used to achieve multitasking.


#### 
Hibernate vs JPA
### Hibernate
* Hibernate is described in org.hibernate package.
* Hibernate is an Object-Relational Mapping (ORM) tool that is used to save the Java objects in the relational database system. 
* Hibernate is an implementation of JPA. Hence, the common standard which is given by JPA is followed by Hibernate.
* It is used in mapping Java data types with SQL data types and database tables.
*
*

### JPA
* described in javax.persistence package.
* It describes the handling of relational data in Java applications.                                                                        
* It is not an implementation. It is only a Java specification. 
* It is a standard API that permits to perform database operations.
*


### Spring 

#### Spring Modules:
The Spring framework comprises of many modules such as core, beans, context, expression language, AOP, Aspects, Instrumentation, JDBC, ORM, OXM, JMS, Transaction, Web, Servlet, Struts etc. These modules are grouped into Test, Core Container, AOP, Aspects, Instrumentation, Data Access / Integration, Web (MVC / Remoting).


#### Spring vs Spring Boot:
* Spring
is a widely used Java EE framework for building applications.
The primary feature of the Spring Framework is dependency injection.
Developers manually define dependencies for the Spring project in pom.xml.
No embedded server.
* Spring Boot
Framework is widely used to develop REST APIs.
The primary feature of Spring Boot is Autoconfiguration. It automatically configures the classes based on the requirement.
It reduces boilerplate code.
This application have jar file.
Embedded server such as Jetty and Tomcat.


#### Spring Boot vs Spring MVC:
* Spring Boot
It is a module of spring for packaging the spring based applications.
It provides default configurations to build Spring-powered framework.
No need to configration manually.
It avoid boilerpate codes.
it reduces development time and increases productivity.

* Spring MVC
It is a model view controller-based web framework under the Spring framework.
It provides ready to use features for building a web application.
It specifies each dependency is separately.
It requires build configuration manually.
It takes more time to achieve the same.


#### Dependency Injection:
It is a design pattern that removes the dependency of the programs. 
In such case we provide the information from the external source such as XML file. 
It makes our code loosely coupled and easier for testing. 
```java
public static void main(String[] args) {
    List<String> list = new ArrayList<>(); // list is dependency and we inject ArrayList here
    list = new LinkedList<>();
    printList(list);
  }

  private static void printList(List<String> list) {

  }
```

### Rabbit MQ vs Kafka 

### Rabbit
* RabbitMQ through clustering and high available queues provides high-performance data replication. 
it also provides high availability.
* It can also process millions of messages within a second, but it needs more number of the hardware.
* Queues are not automatically replicated. The configuration is mandatory.
* Although messages are routed to various queues, only one consumer from a queue can process the message.
* RabbitMQ carries mature client libraries that support Java, PHP, Python, Ruby, and many more.
* It Does not support complex routing scenarios.

### Kafka
* With the help of zookeeper, it manages the state of the Kafka cluster and supports high availability.
* It can process millions of messages in a second with less number of the hardware.
* There are replicated brokers available in Kafka, which works when the master broker is down.
* Multiple consumer types can subscribe to many messages to Kafka.
* With high growth, it led to a good experience. But, it only supports Java clients.
* It supports complex routing scenarios.




















