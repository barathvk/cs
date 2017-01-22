# Strings
> A **String** is a sequence of characters. In the Java language, Strings are **Objects**

## Creating a String

The easiest way to create a String is to write:
```java
String x = "Hello World";
```
Here, "Hello World" is a **string literal**. What the compiler does in this case is create a String _object_ with the string literal as its value. This is the equivalent of:
```java
String x = new String("Hello World")
```
This is called **autoboxing** and is a feature of Java that converts primitives to their object equivalents
### Other ways to create a String:
```java
char[] helloArray = { 'h', 'e', 'l', 'l', 'o', ' ', 'w', 'o', 'r', 'l', 'd'}
String x = new String(helloArray)
```
## String methods
As with other _objects_, Strings have **methods** associated with them. Some methods are **static**, meaning they do not need to have instances to be executed. They can be executed directly from the _class_.
### Static Methods
### Instance Methods


### Further Learning

[](https://www.youtube.com/watch?v=k5R3skKKQBg)
