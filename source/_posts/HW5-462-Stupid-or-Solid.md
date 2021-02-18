---
title: 'This bugs me'
date: 2021-02-18 08:00:00
tags: CSCI462
---

## Reflections on S.O.L.I.D.

The article "From STUPID to SOLID Code" describes what principles to keep in mind to turn STUPID code into SOLID code. These acronyms are defined as follows:

**STUPID**

- **S**ingleton
- **T**ight Coupling
- **U**ntestability
- **P**remature Optimization
- **I**ndescriptive Naming
- **D**uplication

**SOLID**

- **S**ingle Responsibility Principle
- **O**pen/Closed Principle
- **L**iskov Substitution Principle
- **I**nterface Segregation Principle
- **D**ependency Inversion Principle

I agree that the principles provided here act as good indicators for quality in object oriented programming, and I can recall instances where I have violated a couple of these principles, for instance the Liskov Substitution Principle which states that objects should be replaceable with their subtypes, and that when this is not possible in an implementation it should be rewritten not as a subclass, but as an interface. 

## References

- [From STUPID to SOLID Code!](https://williamdurand.fr/2013/07/30/from-stupid-to-solid-code/)
- [Liskov Substitution Principle](https://deviq.com/principles/liskov-substitution-principle)
