# Design Patterns

Simple repository containing one simple example for all existing patterns in C#.


## Creational

Patterns that flexibly create and instantiate objects for you.

- [Abstract factory](DesignPatterns/Creational/AbstractFactory.cs) groups object factories that have a common theme.
- [Builder](DesignPatterns/Creational/Builder.cs) constructs complex objects by separating construction and representation.
- [Factory method](DesignPatterns/Creational/FactoryMethod.cs) creates objects without specifying the exact class to create.
- [Prototype](DesignPatterns/Creational/Prototype.cs) creates objects by cloning an existing object.
- [Singleton](DesignPatterns/Creational/Singleton.cs) restricts object creation for a class to only one instance.

## Structural

Patterns that define ways to compose objects to obtain new functionality.
 
- [Adapter](DesignPatterns/Structural/Adapter.cs) allows classes with incompatible interfaces to work together.
- [Bridge](DesignPatterns/Structural/Bridge.cs) decouples an abstraction from its implementation so that the two can vary independently.
- [Composite](DesignPatterns/Structural/Composite.cs) composes zero-or-more similar objects so that they can be manipulated as one object.
- [Decorator](DesignPatterns/Structural/Decorator.cs) dynamically adds/overrides behaviour in an existing method of an object.
- [Facade](DesignPatterns/Structural/Facade.cs) provides a simplified interface to a large body of code.
- [Flyweight](DesignPatterns/Structural/Flyweight.cs) reduces the cost of creating and manipulating a large number of similar objects.
- [Private Class Data](DesignPatterns/Structural/PrivateClassData.cs) restricts exposure of accessor/mutator by limiting their visibility.
- [Proxy](DesignPatterns/Structural/Proxy.cs) provides a placeholder for another object to control access, reduce cost, and reduce complexity.

## Behavioral

Patterns that specifically concern the communication between objects.

- [Chain of responsibility](DesignPatterns/Behavioral/ChainOfResponsibility.cs) delegates commands to a chain of processing objects.
- [Command](DesignPatterns/Behavioral/Command.cs) creates objects which encapsulate actions and parameters.
- [Interpreter](DesignPatterns/Behavioral/Interpreter.cs) implements a specialized language.
- [Iterator](DesignPatterns/Behavioral/Iterator.cs) accesses the elements of an object sequentially without exposing its underlying representation.
- [Mediator](DesignPatterns/Behavioral/Mediator.cs) allows loose coupling between classes by being the only class that has detailed knowledge of their methods.
- [Memento](DesignPatterns/Behavioral/Memento.cs) provides the ability to restore an object to its previous state (undo).
- [Observer](DesignPatterns/Behavioral/Observer.cs) is a publish/subscribe pattern which allows a number of observer objects to see an event.
- [State](DesignPatterns/Behavioral/State.cs) allows an object to alter its behavior when its internal state changes.
- [Strategy](DesignPatterns/Behavioral/Strategy.cs) allows one of a family of algorithms to be selected on-the-fly at runtime.
- [Template method](DesignPatterns/Behavioral/TemplateMethod.cs) defines the skeleton of an algorithm as an abstract class, allowing its subclasses to provide concrete behavior.
- [Visitor](DesignPatterns/Behavioral/Visitor.cs) separates an algorithm from an object structure by moving the hierarchy of methods into one object.