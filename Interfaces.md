# Interfaces
## Why this topic matters?
+ By using interfaces, you can, for example, include behavior from multiple sources in a class it provides  a powerful mechanism for encapsulation, abstraction, polymorphism, and code reuse. In addition, you must use an interface if you want to simulate inheritance for structs, because they can't actually inherit from another struct or class.

#
## So what is interface??
+ interface is a reference type that defines a contract for classes to follow you can define an interface in C# like this:

````markdown
interface IEquatable<T>
{
    bool Equals(T obj);
}
````
+ Interfaces can contain instance methods, properties, events, indexers, or any combination of those four member types but it can't contain instance fields, instance constructors, or finalizers.
+ Interfaces can inherit from one or more interfaces. The derived interface inherits the members from its base interfaces and it can't be instantiated directly. Its members are implemented by any class or struct that implements the interface.

#
## What problem does the interface solve?
+ The basic problem an interface is trying to solve is to separate how we use something from how it is implemented.