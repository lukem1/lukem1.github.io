---
title: 'STUPID or SOLID'
date: 2021-02-18 08:00:00
tags: CSCI462
---

## Reflections on S.O.L.I.D.

The article "From STUPID to SOLID Code" describes what principles to keep in mind to turn STUPID code into SOLID code. These acronyms are defined as follows:

**STUPID**

- **S**ingleton

  - Singleton refers to the singleton pattern, which is a design which restricts classes to a single instance. This gives a program a single global state, which the article argues makes testing extremely difficult.

- **T**ight Coupling

  - Tight coupling occurs when the modules in your software are highly dependent upon one another. A symptom of this is if when making changes to one module you must make changes to another module. This makes modules difficult to reuse and test.

- **U**ntestability

  - Testing should not be difficult. If it is, it is indicative of other issues like tight coupling.

- **P**remature Optimization

  - Optimization is complex, making minor changes won't help much and it will make code unreadable.

- **I**ndescriptive Naming

  - Name things properly, make sure future you and others will be able to understand the names of your variables, classes, etc.

- **D**uplication

  - Don't repeat yourself. Repetitive code indicates refactoring is necessary.

**SOLID**

- **S**ingle Responsibility Principle

  - Every class should have a single responsibility. This design pattern helps produce highly modular and testable code.

- **O**pen/Closed Principle

  - "software entities should be open for extension, but closed for modification". Member variables should be private unless necessary and getters/setters should only be created when needed.

- **L**iskov Substitution Principle

  - Objects should be replaceable with their subtypes.

- **I**nterface Segregation Principle

  - Many specialized interfaces are better than one generalized interface. Reduces clutter and increases cohesion.

- **D**ependency Inversion Principle

  - "Abstractions should not depend on details and details should depend on abstractions."

I agree that the principles provided here act as good indicators for quality in object oriented programming, and I can recall instances where I have violated a couple of these principles, for instance the Liskov Substitution Principle which states that objects should be replaceable with their subtypes, and that when this is not possible in an implementation it should be rewritten not as a subclass, but as an interface.

## References

- [From STUPID to SOLID Code!](https://williamdurand.fr/2013/07/30/from-stupid-to-solid-code/)
- [Liskov Substitution Principle](https://deviq.com/principles/liskov-substitution-principle)
