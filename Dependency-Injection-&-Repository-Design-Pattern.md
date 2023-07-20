 # Dependency Injection & Repository Design Pattern 
 ## Why This topic Matters ?
 + Dependency Injection (DI) and the Repository design pattern are important concepts in software development that help make code more modular, testable and maintainable. DI allows developers to remove hard-coded dependencies in a class by injecting them through constructor, property or method parameters 

 ## Dependency injection :
 + It is a technique for achieving Inversion of Control (IoC) between classes and their dependencies, In Dependency Injection, the concept of "dependency" refers to any external service or object that a class relies on to perform its functionality. It's an object that another object depends on . The main goal of Dependency Injection is to decouple components by removing the responsibility of creating and managing dependencies from the class itself.

 ## The Repository pattern:
 + The Repository pattern is a Domain-Driven Design pattern intended to keep persistence concerns outside of the system's domain model. One or more persistence abstractions - interfaces - are defined in the domain model, and these abstractions have implementations in the form of persistence-specific adapters defined elsewhere in the application, It's classes that encapsulate the logic required to access data sources.

 ## The repository Design Pattern:
 + The repository pattern is one of the more popular patterns at the moment. I for one like it, it follows the solid principles and done right it is clean and easy to use, The main goal of the Repository Design Pattern is to centralize data access logic and encapsulate the interactions with the underlying data storage, promoting separation of concerns and improving maintainability and testability of the application.

 ## SOLID principle:
 + The SOLID principles are a set of five design principles that aim to guide software developers in creating well-structured, maintainable, and scalable object-oriented software 
    1. **Single-Responsibility Principle:**
    + A class should have one and only one reason to change, meaning that a class should have only one job.
    2. **Open-Closed Principle:**
    + Objects or entities should be open for extension but closed for modification.
    3. **Liskov Substitution Principle:**
    + Let q(x) be a property provable about objects of x of type T. Then q(y) should be provable for objects y of type S where S is a subtype of T.
    4. **Interface Segregation Principle:**
    + A client should never be forced to implement an interface that it doesn’t use, or clients shouldn’t be forced to depend on methods they do not use.
    5. **Dependency Inversion Principle:**
    + Entities must depend on abstractions, not on concretions. It states that the high-level module must not depend on the low-level module, but they should depend on abstractions.
