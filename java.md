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


