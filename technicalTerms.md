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

### AWS
>Amazon Web Services (AWS) is a cloud computing platform provided by Amazon. It is a cloud services, computing power, storage, databases, machine learning, analytics, content delivery.

#### EC2 (Elastic Compute Cloud):

* What (If I have to talk about , I can say that)
Amazon EC2 is a web service that provides resizable compute capacity in the cloud. 
It allows users to run virtual servers, known as "instances," in the AWS cloud. 
EC2 instances come in various types and sizes, each optimized for different use cases.
#### S3 (Simple Storage Service):

* What (If I have to talk about , I can say that)
It is an object storage service that allows users to store and retrieve any amount of data at any time. 
It is designed for durability, scalability, and high-performance storage. 
Data is stored in containers called "buckets," and each object in a bucket is assigned a unique key.
#### CloudWatch:

* What (If I have to talk about , I can say that)
Amazon CloudWatch is a monitoring and observability service for AWS resources and applications.
It provides data and actionable insights for monitoring the performance of applications, resources, and services in real-time.

### DATABASE 

#### DB ACID property
* What (If I have to talk about Acid properties, I can say that ACID properties) Are an acronym that represents a set of properties that related to the reliability of databse transactions.
ACID stands for Atomicity, Consistency, Isolation, Durability.
> A transaction is a single logical unit of work that accesses and possibly modifies the contents of a database. Transactions access data using read and write operations. In order to maintain consistency in a database, before and after the transaction, certain properties are followed. are called ACID properties.
* **A stands for Atomicity**: The entire transaction takes place at once or does not happen at all.
* **C stands for Consistency**: The database must be consistent before an after transaction.
* **I stands for Isolation**: Multiple transactions can happen idependently.
* **D stands for Durabiltiy**: The changes of a succesful transaction occurs even if the system fails because of any issue.

#### Database Indexes
 * What (If I have to talk about Database Indexes, I can say that Database Indexes) Is a data structure technique used to locate and quickly access data in databases. 
* Why(The Biggets adavantage of Database Indexes) Are used to optimize query performance by reducing the number of rows that need to be scanned or sorted. They are particularly beneficial for tables with a large amount of data, as they speed up data retrieval operations.
* How (Lets Take an example,)
> If we have a table students, and we want to run the select query:
`SELECT * FROM STUDENTS WHERE NAME = 'BRUNO'`. It will be slower if there is no index on the table. But if we create and index on column **name**, it will become faster.

#### Connection pooling
* What (If I have to talk about connection pooling, I can say that connetcion pooling) Is a technique used in software development to efficiently manage and reuse database connections.
* Why (The main advantage of connection pooling) It is a way to reduce the cost of opening and closing connections.It passes connections from one database operation to another as needed. 
* How 
In one of my service we are using Hikari connection pooling.

##### SQL vs NoSQL
#### SQL

* What (If I have to talk about , I can say that)
Stands for Structured Query Language. 
Suitable for structured data with predefined schema.
Data is stored in tables with columns and rows. 
Follows ACID properties (Atomicity, Consistency, Isolation, Durability) for transaction management.
Supports JOIN and complex queries. Uses normalized data structure. 
Requires vertical scaling to handle large volumes of data. 
Examples: MySQL, PostgreSQL, Oracle, SQL Server, Microsoft SQL Server.   
    
#### NoSQL

* What (If I have to talk about , I can say that)
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

* What (If I have to talk about SOLID Principles, I can say that)
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

### Design patterns
* What (If I have to talk about design pattern, I can say that design pattern)  In Java are reusable solutions to common problems encountered in software design. They represent best practices for solving specific issues and provide a way to create more maintainable, flexible, and scalable software.
* Why (The biggest advantage of using design pattern) promtes code organization and maintainablity.
* How: There are several design patterns in Java:
Singleton Pattern: Ensures a class has only one instance and provides a global point of access to it.
Factory Method Pattern: Defines an interface for creating an object but lets subclasses alter the type of objects that will be created.
Abstract Factory Pattern: Provides an interface for creating families of related or dependent objects without specifying their concrete classes.

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
* What: (If I have to talk about garbage collection, I can say that garbage collection) In Java is the automatic process of reclaiming memory occupied by the objects that is no longer rechable or not in use by the program. 
* Why: (The biggest advantage of using garbage collection is that) To prevent memory leaks and improve the overall memory management of java programs.
* How: It operates in the background, and developers don't explicitly free memory as in languages like C++. Instead, the Java Virtual Machine (JVM) is responsible for managing memory and performing garbage collection.
Java has different garbage collection algorithms, such as Serial, Parallel, CMS (Concurrent Mark-Sweep), G1 (Garbage First), etc.

#### Functional Interface: 
* What: (If I have to talk about Fuctional Interface, I can say that Functional Interface) Is an interface that declares only one abstract method. 
Can still have multiple default or static methods, but one abstract method.
* Why: (The biggest adavantage of using Functional interfaces) Are crucial to use lambda expressions and functional programming features introduced in Java 8.
* How: (Lets take an example,)
>We created a functional interface with have one abstract method and additionally static method. 
```java
interface MyFunctionalInterface {
    void myMethod(); // Abstract method

    // Additional default or static methods are allowed
    default void anotherMethod() {
        // Implementation
    }
}

// Using a lambda expression to instantiate the functional interface
MyFunctionalInterface myObj = () -> {
    // Implementation of myMethod
};
```


#### Java Releases:
* The lastest java release is JAVA 21.

#### Multithreading in JAVA: 
* What:  (If I have to talk about Multithreading in java, I can say that M.Threading) In Java is a process of executing multiple threads simultaneously.
A thread is a lightweight sub-process, the smallest unit of processing.
* Why: (The biggest advantage of using M.T in Java)  Can Improved  system performance, can remain application more responsive. It enables parallelism and reduces processing time.
* How: (Lets take an example of extending a thread class ) 
>Create a new class that extends the Thread class.
Override the run() method with the code to be executed in the new thread.
Instantiate the new class and call its run() method to begin execution.
java.
```java
class MyThread extends Thread {
    public void run() {
        // Code to be executed in the new thread
    }
}

public class Main {
    public static void main(String[] args) {
        MyThread myThread = new MyThread();
        myThread.run();
    }
}
```

#### 
Hibernate vs JPA
### Hibernate
* What (If I have to talk about Hiebernate , I can say that) Hibernate is an Object-Relational Mapping (ORM) tool that is used to save the Java objects in the relational database system.
* Hibernate is described in org.hibernate package. 
* Hibernate is an implementation of JPA. Hence, the common standard which is given by JPA is followed by Hibernate.
* It is used in mapping Java data types with SQL data types and database tables.



### JPA
* described in javax.persistence package.
* It describes the handling of relational data in Java applications.                                                                        
* It is not an implementation. It is only a Java specification. 
* It is a standard API that permits to perform database operations.

#### JDK, JRE, and JVM

### JVM
JVM is an acronym for Java Virtual Machine; it is an abstract machine which provides the runtime environment in which Java bytecode can be executed. It is a specification which specifies the working of Java Virtual Machine. Its implementation has been provided by Oracle and other companies. Its implementation is known as JRE.

JVMs are available for many hardware and software platforms (so JVM is platform dependent). It is a runtime instance which is created when we run the Java class. There are three notions of the JVM: specification, implementation, and instance.

### JRE
JRE stands for Java Runtime Environment. It is the implementation of JVM. The Java Runtime Environment is a set of software tools which are used for developing Java applications. It is used to provide the runtime environment. It is the implementation of JVM. It physically exists. It contains a set of libraries + other files that JVM uses at runtime.

### JDK
JDK is an acronym for Java Development Kit. It is a software development environment which is used to develop Java applications and applets. It physically exists. It contains JRE + development tools. JDK is an implementation of any one of the below given Java Platforms released by Oracle Corporation:


### Spring 

#### Spring Modules:
* What (If I have to talk about spring modules, I can say that spring modules) 
refers to various components or extensions provided by the spring framework.
* Why (The biggest adavantage of using spring modules) Are that the modular nature of spring allows developers to use only the parts of the framework that are necessary for their applications. And this promotes a more lightweight and flexible approch to bulid software.
* How (Spring modules are organized to adress different concerns in application developement. For example, the Spring Core Container module provides essential functionalities such as dependency injection and aspect-oriented programming. Other modules, like Spring MVC (Model-View-Controller) or Spring Security, cater to specific aspects of web development and security, respectively. We can use or include these modules in our projects by configuring the dependencies in build systems and utilizing the relevant components provided by each module. This modular approach simplifies development, maintenance, and testing of complex enterprise applications.)

#### Spring vs Spring Boot:
* Spring
is Java framework for building enterprise edition applications.
The primary feature of the Spring Framework is dependency injection.
Developers manually define dependencies for the Spring project in pom.xml.
No embedded server.
* Spring Boot
Framework is widely used to develop REST APIs.
The primary feature of Spring Boot is Autoconfiguration. It automatically configures the classes based on the requirement.
* Why (The biggest adavntage of using spring boot) is useful for quickly setting up and deploying applications without spending much time on boilerplate code and configuration. Spring Boot simplifies the development process, making it easier to get started with Spring-based projects.
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
* What(If I have talk about Dependency Injection. I can say that Dependency Injection) Is a design pattern in software development where the components of a system are provided with their dependencies (external services, objects, or resources) rather than creating or managing them internally.
* Why(The biggest adavantage of using Dependency Injection)promotes loose coupling between components, making the code more modular, testable, maintainable. 
* How (There are three common types of dependency injection: Constructor D.I, Setter, Method)
```java
public static void main(String[] args) {
    List<String> list = new ArrayList<>(); // list is dependency and we inject ArrayList here
    list = new LinkedList<>();
    printList(list);
  }

  private static void printList(List<String> list) {

  }
```
### Class vs Object
What is a Class?
Definition: In object-oriented programming (OOP), a class is a blueprint or template for creating objects. It defines the properties (attributes) and behaviors (methods) that objects of that class will have.
Purpose: Classes serve as a blueprint from which individual objects are created. They encapsulate the common characteristics and behaviors shared by multiple objects.
Example: In Java, a class might represent a "Car" and define attributes like "make", "model", and "color", as well as behaviors like "drive" and "stop".

What is an Object?
Definition: An object is an instance of a class. It is a concrete entity that exists in memory and has specific values for the attributes defined in its class. Objects are created based on the structure provided by classes.
Purpose: Objects represent individual entities or instances in a program. They encapsulate state and behavior and can interact with each other through method calls.
Example: Using the "Car" class example, an object would be an actual car instance created based on the "Car" class blueprint, such as a specific car with a make of "Toyota", model of "Camry", and color of "blue".


### Static vs NonStatic
Definition: In Java, static is a keyword used to declare members (variables or methods) that belong to the class itself, rather than to instances of the class. When a member is declared static, it is shared among all instances of the class.
Purpose: Static members are commonly used for constants, utility methods, or variables that should be shared across all instances of a class.
Access: Static members can be accessed directly using the class name, without needing to create an instance of the class.
Example:
```java
Copy code
public class MyClass {
    public static int staticVariable;
    public static void staticMethod() {
        // Method implementation
    }
}
```
# Nonstatic
Definition: Non-static (or instance) members belong to individual instances (objects) of the class. Each object has its own copy of non-static members.
Purpose: Non-static members represent the properties or behaviors specific to each instance of the class. They can vary in value from one object to another.
Access: Non-static members are accessed through object references and are specific to each object.
Example:
```java
Copy code
public class MyClass {
    public int instanceVariable;
    public void instanceMethod() {
        // Method implementation
    }
}
```

### Concurrent Hashmap
What: Thread-safe implementation of a hash table in Java.
Why: Ensures thread safety for concurrent access without external synchronization.
How: Use it for high concurrency scenarios where multiple threads read and write concurrently.

### Collections
What are Collections?
Definition: Collections in Java are objects that group multiple elements into a single unit. They provide a way to store, manipulate, and retrieve groups of objects efficiently.
Purpose: Collections are used to manage and manipulate groups of objects, providing operations like adding, removing, searching, and iterating over elements.
Types of collections are list, set, map, queue.


### Inherritance
* What()
It is concept that allows a class methods and feilds of another class.
The idea behind inheritance in Java is that you can create new classes that are built upon existing classes. When you inherit from an existing class, you can reuse methods and fields of the parent class. Moreover, you can add new methods and fields in your current class also.
Inheritance represents the IS-A relationship which is also known as a parent-child relationship.
* Why()
For Method Overriding (so runtime polymorphism can be achieved).
For Code Reusability.
* How()


### Constructor


### Thread pool

* What() Is a collection of worker threads that are managed by a thread pool manager.It is a design pattern used to manage and control the number of threads that execute concurrently in an application.
* Why()Resource Management: Thread pools manage the creation and destruction of threads, reducing the overhead associated with creating new threads. Performance: Thread pools can improve performance by reusing threads for multiple tasks, avoiding the overhead of creating and destroying threads frequently.
* How()
```java

```

### Stalk pool


### Lambda expression

* What() A lambda expression is a short block of code which takes in parameters and returns a value. Lambda expressions are similar to methods, but they do not need a name and they can be implemented right in the body of a method.
  

* Why(The biggest adavantage of using) Lambda expressions offer several benefits:
Conciseness: They allow you to write compact code, especially when working with functional interfaces that require only a single abstract method.
Readability: Lambda expressions often make code more readable by reducing boilerplate code, particularly when passing behavior as parameters.
Flexibility: They enable more flexible and expressive programming constructs, such as functional programming paradigms like map-reduce operations.
Improved APIs: Lambda expressions facilitate the use of functional interfaces, enabling more streamlined APIs in libraries and frameworks.
* How()
// Lambda expression to square a number
Function<Integer, Integer> square = (num) -> num * num;

// Using the lambda expression
int result = square.apply(5); // Returns 25


#### Throw and Throws

# Throw
* What () Statement in Java is used to throw an exception. We can throw exception in any try catch (Block : Some pice of which is return together ) or if else. It is followed by an instance of the Throwable class (usually an exception object) that represents the error or exceptional condition.

* Why () Statement when we want to create and throw a custom exception or signal that something unexpected or exceptional has occurred during program execution.

# Throws

* What () Is used in the method signature to indicate that a method might throw one or more types of exceptions. When a method includes a throws clause, it means that the method is not handling the exceptions within itself, and the responsibility of handling those exceptions is delegated to the calling method or, ultimately, to the Java runtime environment.
* Why () The throws clause is used to declare the exceptions that a method might throw. It allows the method to indicate to the calling code the types of exceptions it can throw, so that the calling code can choose to handle those exceptions or let them propagate up the call stack.



### Static

* What () In Java is used to declare members (fields, methods, and nested classes) that belong to the class rather than instances of the class. When a member is declared as static, it means there is only one copy of that member shared by all instances of the class, and it can be accessed without creating an instance of the class.
* Why () 
* Fields (Static Variables):
static fields are shared among all instances of the class. They are typically used for constants or variables that should be common to all instances.
* Methods (Static Methods):
static methods are associated with the class rather than with instances. They are often used for utility methods that don't depend on the state of any particular instance.
* Nested Classes (Static Nested Classes):
When a class is declared as static within another class, it is a static nested class. It can be instantiated without an instance of the outer class and can access the static members of the outer class.

### Imutable 

* What () Immutability refers to the state of an object that cannot be modified after it is created. Once an immutable object is instantiated, its state (the values of its fields) cannot be changed. WE use final keyword to declare a object immutable.

* Why () Consistency, Thread safety, Hashcode Stability Here consistency means immutability ensures that an object's state remains constant throughout its lifetime, making it easier to reason about and preventing unexpected changes. 



### Rabbit MQ vs Kafka 

### Rabbit

* What (If I have to talk about , I can say that)
* RabbitMQ through clustering and high available queues provides high-performance data replication. 
it also provides high availability.
* It can also process millions of messages within a second, but it needs more number of the hardware.
* Queues are not automatically replicated. The configuration is mandatory.
* Although messages are routed to various queues, only one consumer from a queue can process the message.
* RabbitMQ carries mature client libraries that support Java, PHP, Python, Ruby, and many more.
* It Does not support complex routing scenarios.

### Kafka

* What (If I have to talk about , I can say that)
* With the help of zookeeper, it manages the state of the Kafka cluster and supports high availability.
* It can process millions of messages in a second with less number of the hardware.
* There are replicated brokers available in Kafka, which works when the master broker is down.
* Multiple consumer types can subscribe to many messages to Kafka.
* With high growth, it led to a good experience. But, it only supports Java clients.
* It supports complex routing scenarios.

