### Widening Casting

Widening casting is done automatically when passing a smaller size type to a larger size type.  

**Example**

````java
public class Main {
    int myInt = 9;
    double myDouble = myInt; // Automatic casting into double
    
    System.out.println(myInt);
    System.out.println(myDouble);
}
````

### Narrowing Casting

Narrowing casting must be done manually by placing  the type in parentheses () in front of the value:  

**Example**

````java
public class Main {
    public static void main(String[] args){
        double myDouble = 9.78d;
        int myInt = (int) myDouble; // manual casting double into in;
    }
}
````
