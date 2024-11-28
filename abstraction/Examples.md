1. currently this is an example of 100% abstraction

```java
abstract class Parent{ 
    abstract void say(){}
}


public class Example extends Parent{ 
    @Override void say(){
        System.out.println("method overriden");
    }
}

```
