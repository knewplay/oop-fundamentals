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

Object-Oriented Programming (OOP) represents a significant shift in how we think about and write code. Instead of focusing solely on functions and logic, OOP emphasizes the importance of data structures that model real-world entities and their interactions.

![Real-world modelling](./figures/world-modelling.jpg)
*OOP models real-world entities and interactions between them.*

Previously, we have learned about procedural programming. In procedural programming, the program is organized around functions that process data in a sequence. This means the whole program is focused on how data flows and what operations are performed on it step by step. It’s a function-focused approach.

OOP, however, is a different paradigm. It focuses on structuring the information and modeling either the real world or a world we want to create through software, such as a game world. This shift in focus allows for a more organized and natural way of thinking about and interacting with data.

For instance, let's say we want to write some code to extract and analyze data from a Stack Overflow survey. The survey data includes information on how many users use certain programming languages, how many years they've been programming, and their working preferences (remote, hybrid, or in-person). In a procedural approach, we would write a series of functions to handle each part of the process: one function to scrape the data from the website, another to store this data into a CSV file, and additional functions to analyze the data. We might count the number of times each programming language is mentioned, determine how many people work in different settings, and perform analysis to identify trends, such as which languages are most popular among remote workers. The program runs these functions in sequence: first loading data, then analyzing it, and then performing further analysis.

Now, consider getting hired at a bank to work on their software backend. In this context, we have users who may or may not have bank accounts. Bank accounts have balances, can receive deposits, and have a deposit history. We can withdraw from an account, make deposits, or transfer money from one account to another through transactions. A transaction includes details such as the amount, the 'from' bank account, the 'to' bank account, and the date and time it was completed. This approach helps in modeling the banking system, capturing the relationships and interactions between users, accounts, and transactions in a structured and organized manner.

By focusing on entities and their interactions, OOP allows us to create software that more closely mirrors real-world systems. This approach can make your programs more intuitive, scalable, and easier to maintain.

### Brief History and Evolution of OOP

Programming became essential as computers were developed to perform calculations and automate tasks. Initially, programming was procedural, involving writing commands that the computer processed in sequential order. Early languages like Fortran and COBOL (1950s-1960s) focused on solving mathematical problems and handling business-related tasks such as payroll processing and inventory management. The C language (1970s) advanced procedural programming for operating systems and complex applications.

The concept of Object-Oriented Programming (OOP) emerged in the 1960s with Simula, introducing the idea of simulating real-world entities and processes. This marked a shift from procedural programming by allowing more natural and flexible modeling of complex systems.

In the 1980s, C++ built upon C by adding OOP features, addressing the need for better code management as software systems grew. OOP facilitates code reusability, modularity, and easier maintenance through objects and classes (which we will cover in the next section).

The 1990s saw the rise of Java and Python, both of which are OOP languages. Java's ability to run on any computer system and Python's simplicity and readability brought OOP to a wider audience, making both languages popular for their versatility and built-in tools.

Today, OOP is fundamental in computer science education and a standard practice in software development, helping developers manage complexity, improve code reusability, and create scalable solutions.

## Building Blocks of OOP

### Classes and Objects

In Object-Oriented Programming (OOP), classes and objects are fundamental concepts. A class is a blueprint for creating objects, defining their structure and behavior. An object is created from a class, representing a concrete entity based on the class blueprint.

#### Example: Designing a RoboticArm class

Imagine you're designing a fleet of robots for a competition. Instead of writing separate pieces of code for each robot's functionality, OOP lets you create a blueprint for a robot. This blueprint describes what a robot is like (its properties) and what it can do (its actions). You can then create as many robots as you need from this blueprint, each with its own unique features but all sharing the same core design.

![Blueprint and designs](./figures/robot-blueprint.jpg)
*A blueprint on the left with three robots modeled from it on the right.*

The blueprint you see on the left is the class, and the specific robots you see on the right, based on the blueprint, are known as objects. All classes have names; let's say the name of this class is `RoboticArm`. This class serves as a template for creating various robots. When you create a robot from this class, you are instantiating the class, and each instantiated robot is called an instance of the class. Each robot shares the same foundational structure but can have unique characteristics.

By creating different robots from the `RoboticArm` class, you can manage their interactions and behaviors in an organized way. This approach allows you to efficiently handle complex systems and ensures that all robots adhere to a consistent design and functionality.

#### Example: Designing a school management system

Consider a school management system with separate classes for `Student` and `Teacher`.

- `Student` class:

  - The `Student` class serves as a blueprint for creating student objects.
  - Each student object, also known as an instance of the `Student` class, represents an individual student.
  - These student instances can then be part of the school system.

- `Teacher` Class:

  - The `Teacher` class serves as a blueprint for creating teacher objects.
  - Each teacher object, also known as an instance of the `Teacher` class, represents an individual teacher.
  - These teacher instances can then be part of the school system.

By defining these classes, you can create student and teacher objects, each of which is an instance of their respective class. This allows the school management system to manage students and teachers efficiently, leveraging the power of OOP to organize and structure the entities within the system.

### Attributes and Methods

In OOP, the key components of a class are its attributes and methods. Attributes describe the characteristics of an object (properties), while methods define what the object can do (actions). Attributes are like variables that store data specific to an object. Methods, on the other hand, are functions that belong to a class and define the actions that that object can perform.

#### Example: Robot attributes and behaviors

Imagine designing a class called `Robot`. This class a placeholder for what a robot is like (its attributes) and what it can do (its methods). For example, a robot might have a name, color, and weight, and it can perform actions like introducing itself.

![Robot objects and their attributes](./figures/robot-class-objects.jpg)
*A class called Robot, and two object instances of this class with their unique attributes.*

One robot can be called "Tom", be blue, and weigh 40 lbs, and another robot can be named "Jerry", be red, and weigh 10 lbs. When you create objects, you can give it custom attributes. However, when it comes to methods, these are less customizable, as we can see that both objects have the same method, that is "Introduce". Nonetheless, each attribute and method is linked to a given object. For example, the `Introduce` method done by the first object, and the `Introduce` method done by the second object, are not the same method. They always apply to their respective object.

#### Example: Student and Teacher attributes and behaviors

Consider the school management system from before.

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

Classes can inherent behaviors from eachother, forming hierarchies.

#### Example: Specialized Robot Types

### Encapsulation

#### Example: Protecting Robot Data
