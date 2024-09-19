---
title: JS
type: docs
prev: docs/first-page
next: docs/Nodejs/leaf
sidebar:
  open: true
---

### 7. Method Overloading vs Method Overriding

- *Method Overloading*:(Static Polymorphism)

- **Definition**: Occurs when a class has multiple methods with the same name but different parameters (number or type).
- **Timing**: Resolved at **compile-time**.
- **Usage**: It allows different ways to call a method based on different parameter sets.
  
Example:
```java
class Example {
    void display(int a) { /* ... */ }
    void display(int a, int b) { /* ... */ }
}
```
--------------------------------
- *Method Overriding* (Dynamic Polymorphism)

- **Definition**: Occurs when a subclass provides a specific implementation of a method that is already defined in its parent class, using the same method signature (name, parameters, and return type).

- **Timing**: Resolved at runtime.

- **Usage**: It allows a subclass to provide a different behavior for a method inherited from its parent class.

Example: 
```java
class Parent {
    void show() {
        System.out.println("Parent's show()");
    }
}

class Child extends Parent {
    @Override
    void show() {
        System.out.println("Child's show()");
    }
}
```
