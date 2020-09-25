---
layout: default
title: OOP
nav_order: 2
---
# OOP
[Object-Oriented programming (C#)](https://docs.microsoft.com/en-us/dotnet/csharp/programming-guide/concepts/object-oriented-programming)
* **Abstraction** means hiding the unnecessary details from type consumers. (Access modifiers)
* **Encapsulation** means that a group of related properties, methods, and other members are treated as a single unit or object.
* [**Inheritance**](https://docs.microsoft.com/en-us/dotnet/csharp/programming-guide/classes-and-structs/inheritance) describes the ability to create new classes based on an existing class.
* [**Polymorphism**](https://docs.microsoft.com/en-us/dotnet/csharp/programming-guide/classes-and-structs/polymorphism) means that you can have multiple classes that can be used interchangeably, even though each class implements the same properties or methods in different ways.
  - Static (Compile time) polymorphism
    - Method overloading
    - Operator overloading
  - Dynamic (Runtime) Polymorphism
    - Virtual method/Method Override  

## [Access modifiers and access levels](https://docs.microsoft.com/en-us/dotnet/csharp/programming-guide/concepts/object-oriented-programming#access-modifiers-and-access-levels)

| C# Modifier        | Definition                                                                                                         |
| :----------------- | :----------------------------------------------------------------------------------------------------------------- |
| public             | The type or member can be accessed by any other code in the same assembly or another assembly that references it.  |
| private            | The type or member can only be accessed by code in the same class.                                                 |
| protected          | The type or member can only be accessed by code in the same class or in a derived class.                           |
| internal           | The type or member can be accessed by any code in the same assembly, but not from another assembly.                |
| protected internal | The type or member can be accessed by any code in the same assembly, or by any derived class in another assembly.  |
| private protected  | The type or member can be accessed by code in the same class or in a derived class within the base class assembly. |

## [Classes and objects](https://docs.microsoft.com/en-us/dotnet/csharp/programming-guide/concepts/object-oriented-programming)
The terms class and object describe the type of objects, and the instances of classes, respectively. So, the act of creating an object is called instantiation. Using the blueprint analogy, a class is a blueprint, and an object is a building made from that blueprint.

* Early Binding 
* Late binding
  