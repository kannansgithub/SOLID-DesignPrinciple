# SOLID Design Principle

## Why SOLID required?

> If we are not follow SOLID principle we will end up with

- Tight/Strongly Coupling with many other module
- Tightly coupled application created lot of unknown issues when we are fixing the issues/bug
- It will take more time to implement new features
- Code not easy to testable
- Lot of duplicate codes in the application
- Not easy to read/maintain the code

> SOLID principles Help us to

- To reduce the complex of the code
- Increase readability, extensibility and maintenance
- Reduce errors on bug fix
- Improves reuseablity
- Achive better testablity
- Reduce Tight/Strongly Coupling

> Successfull application depends on

- Architecture

        Choosing the correct architecture is the first step for developing the application Ex. MVC, Web API, etc...

- Design Principles

        Application development must needs to follow the design principles to make better softwares.

- Design Patterns

        We need to choose the correct design patterns based on the application requirement.

## What is SOLID?

SOLID principles are the design principles that enable us to manage most of the software design problems. The SOLID Design principles have many subset of principles. This was promoted by **Robert C. Martin**

SOLID is an acronym of the five design principles that will helps to make system to **loosely coupled, understandable** and **maintaineable**

This SOLID acronym was first introduced by **Michael Feathers**

## SOLID acronym

- **S**: Single Responsibility Principle **(SRP)**
- **O**: Open closed Principle **(OCP)**
- **L**: Liskov substitution Principle **(LSP)**
- **I**: Interface Segregation Principle **(ISP)**
- **D**: Dependency Inversion Principle **(DIP)**

### Single Responsibility Principle (SRP)

**Robert C. Martin** express the principles as

> _Every software module should have only one reason to change_

This means that every class/module in our code should have only one responsibility of the software. That responsibility should be entirely encapsulated by the class.

### Open closed Principle (OCP)

Open Closed principle says that

> _"A software module/class is open for extension and closed for modification"_

- Open for extension

  `Our module/class in such a way that the new functionality can be added with minimal code changes of existing class/module`

- Closed for modification

  `Our module/class in such a way that should not allow to alter it existing code/module until we find bugs`

As it says, a class should be open for extensions, we can use inheritance to do this

### Liskov substitution Principle (LSP)

Interoduced by **Barbara LisKow** state that

> _objects in a program should be replaceable with instances of their subtypes without modifying the program_

This means the program module is using Parent class, then the reference to the Parent class can be replaced with Child class without affecting the functionality of the program module.

We can also state that "Drived types must be substitutable for their types"

### Interface Segregation Principle (ISP)

Interface Segregation Principle state that

> many functional specific interfaces are better that one general purpose/big interface

That means we should not be forced the application to implement interfaces that they don't use. Instead of creating one big interface, we can break it small interfaces are preferred.

### Dependency Inversion Principle (DIP)

The Dependency Inversion Principle (DIP) states that

> One should depend upon abstractions not concretions

That mean Abstractions should not depend upon details. Details should depend upon abstractions.

high-level modules/classes should not depend on low-level modules/classes.
