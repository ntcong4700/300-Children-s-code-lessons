# Quickstart with java

In Java, every application begins with a class name, and that class must match the filename.  

```java
public class Main {
    public static void main(String[] args){
        System.out.println("Hello World");
    }
}
```
#### The main Method  
The ***main()*** method is required and you in every Java program :

````java
public static void main(String args)
````

Any code inside the ***main()*** method will be executed. Don't worry about the code before and after it.

#### Print Text

````java
System.out.println("Hello World")
````

***println()*** : print something in console.

#### Java Variables

Variables are containers for storing data values.

In Java, there are different types of variables, for example :  
- String
- int
- float
- char
- boolean

**Varibale declaring**
````java
type variableName = value;
````

**Final varibale**

The ***final*** keyword, which means you cannot change its value, you can only read.

````java
final int myNum = 15;
myNum = 20;
````

⇒ This will creat an error : cannot assign a value to a final variable