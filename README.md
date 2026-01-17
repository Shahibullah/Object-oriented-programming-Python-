Object-oriented programming (OOP) is a computer programming model that organizes software design around data, or objects, rather than functions and logic.

1. Encapsulation

Bundling data (variables) and methods (functions) that operate on that data into a single unit called a class.

Restricts direct access to some components to protect data.

Achieved using access modifiers (private, protected, public).

Example:
A BankAccount class hides the balance and allows access only through deposit() and withdraw() methods.

2. Abstraction

Hiding complex implementation details and showing only essential features.

Focuses on what an object does, not how it does it.

Implemented using abstract classes or interfaces.

Example:
A Car interface exposes start() and stop() methods without revealing engine internals.

3. Inheritance

One class (child/subclass) can inherit properties and methods from another (parent/superclass).

Promotes code reuse and hierarchical relationships.

Example:
Dog inherits from Animal, gaining its behaviors while adding its own.

4. Polymorphism

Ability of different objects to respond to the same method call in different ways.

Achieved through method overriding and method overloading.

Example:
Animal.sound() produces different sounds for Dog, Cat, etc.
