# java
### Java variables.
`String`  stores text
for example  
```java
String myText = "Hello";
```
`int` stores integer(whole numbers)
for example
```java
int myNum = 5;
```
`float` stores floating point numbers with decimals.
```java
example-  float myFloatNum = 5.99f;
```
`char` stores single character value.
```java
example- char myLetter = 'D';
```
`boolean` stores values with two states: true or false.
```java
example- boolean myBool = true;
```

* declaring(creating) variables
`syntax` 
```java
type variableName = value;
```
Where type is one of javas type(int or string) and variableName is the name and the value is assigned value.
`example- Create a variable called name of type String and assign it the value "John":`
```java
String name = "John";
System.out.println(name);
```
`example-  Create a variable called myNum of type int and assign it the value 15:`
```java
int myNum;
myNum = 15;
System.out.println(myNum);
```
#### We can also assign a new value to an existing variable
```java
int myNum = 15;
myNum = 20;  // myNum is now 20
System.out.println(myNum);
```

#### final variable
`It is used to not change value of variable`
```java
example : final int myNum = 15;
myNum = 20;  
// will generate an error: cannot assign a value to a final variable
```
`We can also declare a  final type variable without assigning the value, and assign the value late`
```java
final myNum;
myNum = 10;
//Now myNum value is 10. But we cannot assign a new value to an existing data in final type variable.
```

### Java theory questions:

### Garbage collection
It automatically reclaims memory by identifying and removing unreachable objects, managed by the Java Virtual Machine (JVM).

### Abstract classes 
A class which is declared with the abstract keyword is known as an abstract class in Java.
It can have abstract and non-abstract methods (method with the body).	
It doesn't support multiple inheritance.
It can have final, non-final, static and non-static variables. And class memeber like private or porteted.
It can extend another java class and implement multiple java interfaces.
For example, sending SMS where you type the text and send the message. You don't know the internal processing about the message delivery.

### Interface
It can have only abstract methods. Since Java 8, it can have default and static methods also.
It can support multiple Inherritance.
It has only static and final variables.
```java
public interface Drawable{
void draw();
}
```

### Concurrent Hashmap 
It is designed to be used in multithreaded environments where multiple threads may need to access.


### Heap vs Stack memory
It is created when the JVM starts up and used by the application as long as the application runs. 
It stores objects and JRE classes. And smaller in size.


The stack memory is a physical space (in RAM) allocated to each thread at run time. 
It is created when a thread creates.
It stores the variables, references to objects, and partial results. Memory allocated to stack lives until the function returns. 
If there is no space for creating the new objects, it throws the java.lang.StackOverFlowError. 
The scope of the elements is limited to their threads. The JVM creates a separate stack for each thread.


### Multithreading in Java

Multithreading in Java is a process of executing multiple threads simultaneously.
It doesn't block the user because threads are independent and you can perform multiple operations at the same time.
You can perform many operations together, so it saves time.
Threads are independent, so it doesn't affect other threads if an exception occurs in a single thread.


### Syncronization in Java

It is the capability to control the access of multiple threads to any shared resource.
Java Synchronization is better option where we want to allow only one thread to access the shared resource.


