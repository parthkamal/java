1. abstract methods with parameters - 

```java
abstract class Parent { 
    abstract void say(String name, int age); 
}

public class Example extends Parent { 
    @Override 
    void say(String name, int age) {
        System.out.println("Name: " + name + ", Age: " + age);
    }

    public static void main(String[] args) {
        Example example = new Example();
        example.say("John", 25); 
    }
}

```
