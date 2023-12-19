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

Null pointer exception is a runtime exception. Null is a special kind of value that can be assigned to the reference of an object. Whenever one tries to use a reference that has the Null value, the NullPointerException is raised.

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

### AWS
Amazon Web Services (AWS) is a cloud computing platform provided by Amazon. It is a cloud services, computing power, storage, databases, machine learning, analytics, content delivery.

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












