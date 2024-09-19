---
title: Node.js Interview Questions
type: docs
prev: /
next: docs/NodejsInterviewQuestion/
---

A simple demo page.

## JavaScript Interview Questions

### 1. How many data types are there in JavaScript?

In JavaScript, there are 7 data types for Primitive types:
- **Primitive types**:
  - `undefined`
  - `null`
  - `boolean`
  - `number`
  - `bigint`
  - `string`
  - `symbol`
- **Non-primitive type**:
  - `object`

### 2. Does JavaScript support inheritance?

Yes, JavaScript supports inheritance. It primarily uses **prototypal inheritance**, which means that objects can inherit properties from other objects. This differs from classical inheritance in languages like Java, but starting from ES6, JavaScript also supports **class-based inheritance** using the `class` syntax, although it still functions with prototypes under the hood.

### 3. What is OOP?

**Object-Oriented Programming (OOP)** is a programming paradigm based on the concept of "objects," which are instances of classes. OOP organizes code into reusable objects, allowing for easier management of large codebases. OOP principles include:
- **Encapsulation**: Bundling data and methods that operate on that data within an object.
- **Abstraction**: Hiding the internal complexity and exposing only what’s necessary.
- **Inheritance**: A mechanism where one class can inherit properties and methods from another.
- **Polymorphism**: The ability to define a function in multiple forms.

### 4. What is SOLID?

**SOLID** is an acronym representing five principles that help developers write clean, maintainable, and scalable code:
- **S**: Single Responsibility Principle (SRP) - A class should have one, and only one, reason to change.
- **O**: Open/Closed Principle (OCP) - Software entities should be open for extension but closed for modification.
- **L**: Liskov Substitution Principle (LSP) - Objects of a superclass should be replaceable with objects of a subclass without altering the correctness of the program.
- **I**: Interface Segregation Principle (ISP) - No client should be forced to depend on interfaces it does not use.
- **D**: Dependency Inversion Principle (DIP) - High-level modules should not depend on low-level modules. Both should depend on abstractions.

### 5. What are the types of design patterns?

Design patterns provide solutions to common design problems in software development. The primary categories of design patterns are:
- **Creational Patterns**: Focus on object creation mechanisms.
  - Examples: Singleton, Factory, Abstract Factory, Builder, Prototype
- **Structural Patterns**: Deal with object composition and relationships.
  - Examples: Adapter, Composite, Proxy, Facade, Flyweight, Decorator
- **Behavioral Patterns**: Concerned with communication between objects.
  - Examples: Observer, Strategy, Command, Chain of Responsibility, State, Template Method

### 6. What is the difference between a class and an abstract class?

- **Class**: A blueprint for creating objects. It can be instantiated, meaning objects can be created from it. A class may contain fields, methods, and constructors.
  
- **Abstract Class**: A class that cannot be instantiated directly. It serves as a base class for other classes and may include abstract methods (methods without implementation) that must be implemented by any subclass. Abstract classes are used to define a common interface or structure for subclasses while forcing those subclasses to provide specific behavior.

### 7. Event loop?
Link: https://200lab.io/blog/event-loop-la-gi/
### 8. Callback hell
