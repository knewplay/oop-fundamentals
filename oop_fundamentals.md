---
title: "OOP Fundamentals"
date: "2024-05-22"
author: "Andrei Guevorkian"
illustrator: "Dengyijia Liu"
---

In this article, you'll be introduced to Object-Oriented Programming (OOP), a method of programming that focuses on building organized and easily scalable software. OOP is a relatively advanced topic, and it's natural if its purpose and benefits aren't immediately clear. OOP is particularly useful in larger programs that need to scale easily, as it helps with the structure and organization of the code. This guide will cover the fundamentals of OOP, providing you with the knowledge and tools to understand and work with VEX V5 code.

## Table of Contents

[Introduction to Object-Oriented Programming](#introduction-to-object-oriented-programming)

- [What is OOP?](#what-is-oop)
- [Brief History and Evolution of OOP](#brief-history-and-evolution-of-oop)

[Building Blocks of OOP](#building-blocks-of-oop)

- [Classes and Objects](#classes-and-objects)
- [Attributes and Methods](#attributes-and-methods)
- [Objects and Their Relationships in Real-World Applications](#objects-and-their-relationships-in-real-world-applications)

[The Four Pillars of OOP: A PIE](#the-four-pillars-of-oop-a-pie)

- [Abstraction](#abstraction)
- [Encapsulation](#encapsulation)
- [Inheritance](#inheritance)
- [Polymorphism](#polymorphism)

## Introduction to Object-Oriented Programming

### What is OOP?

Object-Oriented Programming (OOP) represents a significant shift in how we think about and write code. Instead of focusing solely on functions and logic, OOP emphasizes the importance of data structures that model real-world entities and their interactions. This approach can make your programs more intuitive, scalable, and easier to maintain.

![Real-world modelling](./figures/world-modelling.jpg)
*OOP models real-world entities and interactions between them.*

Imagine you're designing a fleet of robots for a competition. Instead of writing separate pieces of code for each robot's functionality, OOP lets you create a blueprint for a robot. This blueprint describes what a robot is like (its properties) and what it can do (its actions). You can then create as many robots as you need from this blueprint, each with its own unique features but all sharing the same core design.

![Blueprint and designs](./figures/robot-blueprint.jpg)
*A blueprint on the left with three robots modeled from it on the right.*

Having created different robots, we can now write code to specify their interactions with one another and other entities. This helps us manage complex systems in an organized fashion and represent them programmatically.

### Brief History and Evolution of OOP

Programming became essential as computers were developed to perform calculations and automate tasks. Initially, programming was procedural, involving writing commands that the computer processed in sequential order. Early languages like Fortran and COBOL (1950s-1960s) focused on solving mathematical problems and handling business-related tasks such as payroll processing and inventory management. The C language (1970s) advanced procedural programming for operating systems and complex applications.

The concept of Object-Oriented Programming (OOP) emerged in the 1960s with Simula, introducing the idea of simulating real-world entities and processes. This marked a shift from procedural programming by allowing more natural and flexible modeling of complex systems.

In the 1980s, C++ built upon C by adding OOP features, addressing the need for better code management as software systems grew. OOP promotes code reusability, modularity, and easier maintenance through objects and classes (which we will cover in the next section).

The 1990s saw the rise of Java and Python. Java's ability to run on any computer system and Python's simplicity and readability brought OOP to a wider audience, making both languages popular for their versatility and built-in tools.

Today, OOP is fundamental in computer science education and a standard practice in software development, helping developers manage complexity, improve code reusability, and create scalable solutions.

## Building Blocks of OOP

### Classes and Objects

In Object-Oriented Programming (OOP), classes and objects are fundamental concepts. A class is a blueprint for creating objects, defining their structure and behavior. An object is an instance of a class, representing a concrete entity based on the class blueprint.

#### Example: Designing a Robot class

Imagine designing a class called Robot. This class serves as a template for creating various robots. Each robot created from this class would share the same foundational structure but can represent individual robots.

#### Example: Designing a school management system

Consider a school management system with separate classes for `Student` and `Teacher`.

- `Student` class:

  - Each student is created from the Student class.
  - These students can then be part of the school system.

- `Teacher` Class:

  - Each teacher is created from the Teacher class.
  - These teachers can then be part of the school system.

By defining these classes, you can create student and teacher objects. This allows the school management system to manage students and teachers efficiently, leveraging the power of OOP to organize and structure the entities within the system.

### Attributes and Methods

In OOP, the key components of a class are its attributes and methods. Attributes describe the characteristics of an object (properties), while methods define what the object can do (actions). Explain what is an attribute, and what is a method. Readers already know what is a function, so use that to explain methods as well.

#### Example: Robot attributes and behaviors

Imagine designing a class called `Robot`. This class defines what a robot is like (its properties) and what it can do (its actions). For example, a robot might have a name, type, and color, and it can perform actions like moving, picking up objects, and turning.

For the Robot class, properties might include the robot's name, type, and color. Actions could include moving, picking up objects, and turning.

![Robot objects and their attributes](./figures/robot-class-objects.jpg)
*A class called Robot, and two object instances of this class with their unique attributes.*

#### Example: Person, Student, and Teacher attributes and behaviors

Consider a school management system with separate classes for `Student` and `Teacher`.

- `Student` class:

  - Each student has a name, age, and school ID.
  - Students can perform actions like enrolling in courses and taking exams.

- `Teacher` Class:

  - Each teacher has a name, subject, and employee ID.
  - Teachers can perform actions like teaching classes and grading exams.

By defining these classes, you can create student and teacher objects, each with its own properties and actions. This allows the school management system to manage students and teachers efficiently, leveraging the power of OOP to organize and structure the data and actions associated with each entity.

### Objects and Their Relationships in Real-World Applications

Purpose of the section: Explain how OOP concepts are used in everyday applications, such as smartphone apps, video games, and web applications.

- Illustrate how robotic systems use objects to manage different components, such as sensors, motors, and controllers.
- Describe a simple example, like a banking system where customers and accounts are objects with attributes and methods.
- Discuss how a game might use objects to represent players, enemies, and items, each with their own properties and behaviors.

Types of Object Relationships:

Association: Define and explain how one object can be associated with another, such as a robot and its controller.
Aggregation: Discuss how an object can be a collection of other objects, like a robot composed of multiple sensors and motors.
Composition: Describe a stronger form of aggregation where the lifecycle of the contained objects depends on the lifecycle of the container object.
Example:

Use a robot example where a `Robot` object contains multiple `Sensor` objects and interacts with a `Controller` object. Explain how these relationships work in a real-world scenario, making the concepts clear and relatable.

## The Four Pillars of OOP: A PIE

### Abstraction

#### Example: Simplifying Complex Robot Systems

### Polymorphism

![Animals speaking](./figures/polymorphism-speak.jpg)
*Different animals (dog, cat, cow) inherit from `Animal` class and each implement their own `speak()` method.*

#### Example: Interchanging Robot Components

### Inheritance

#### Example: Specialized Robot Types

### Encapsulation

#### Example: Protecting Robot Data
