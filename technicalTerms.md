### Service 


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

### Framework
A framework is like a structure that provides a base for the application development process. With the help of a framework, you can avoid writing everything from scratch.

Frameworks provide many advantages such as:
* Easy to test our code and debug it.
* Clean code is much easy to understand and work with.
* Reduces the time and cost of the project with the enhanced application.
* Features and functionalities provided by the framework can be modified and extended.
* Such as Spring, Django, Flutter, Angular, Vue, PyTorch, Spring Boot, React Native, Apache Spark are the frameworks.


### Infrastructure

### shadowing

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
* Generic
It is used in java. In generic type we can use String or Integer both or Double or any other type.
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
XML is a way to write data. It is also like HTML. It is a software tool for storing and transporting data. We use xml format to write our pom file in java spring project.

stored as XML format:
```
<Person>
  <name>Shikha</name>
  <age>27</age>
</Person>
```

### Redirection

### fetch
It is used totake the data from the database.

### merging
When we create two branch and merge them.
```
git merge
```

### Refactoring
Refactoring is the process of restructuring existing code without changing its external behavior.

### append

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
* 200 OK, 
* 401 Unauthorized, 
* 400 Bad Request, 
* 404 Not Found, 
* 500 Internal Server Error,
* 503 Service Unavailable.

### Machines and ports

### flyway

### Null pointer Exception

 Null pointer exception is a runtime exception. Null is a special kind of value that can be assigned to the reference of an object. Whenever one tries to use a reference that has the Null value, the NullPointerException is raised.

 ```java
public static void main(String[] args) {
    String name = null;
    System.out.println(name.length());
}
```
Here, the variable name is assigned the value null, and then we try to access the name , in result NullPointerException will come here. 


### Stacktrace

### Exception handling
It is two types: 
Compile time exception and run time exception.

#### Compile time exception 
When we do the code. then it is occured
```java
string name = "shikha";
```
#here the compile type exception will come.

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
It is used in in deploying, managing, and scaling containerized applications.

### AWS
Amazon Web Services (AWS) is a comprehensive and widely used cloud computing platform provided by Amazon. AWS is a cloud services, computing power, storage, databases, machine learning, analytics, content delivery.

### Jenkins
It is an used for building, testing, and deploying code.

### Zookeeper

### client server architecture

