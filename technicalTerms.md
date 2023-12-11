### Service  It is a class also It is also

### Microservice Architecture
It is a modern architecture. We can divide our services into multiple smaller services known microservices. These micro services communicate to each other using REST apis.
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
* Its performance is very fast.
But there are some disadvantages also:
* If there is any issue with service entire application will stop.
* It is not eas to understand. When new joiner join company.

### Repository
* Framework
* Infrastructure
* shadowing
* Hard coding
* Generic
### Json format

Json is a way to write data. JSON data is represented as key-value pairs. 
Data is enclosed in curly braces '{}'. Key-value pairs are separated by colons.

```
{
  "name": "John Doe",
  "age": 30
}

```
* Xml format
* Redirection
* fetch
* merging
* Refactoring
* append

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


* Stacktrace
* Exception handling:Compile time exception and run time exception.
* 

