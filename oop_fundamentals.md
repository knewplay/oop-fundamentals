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

![Class and objects](./figures/robot-class-objects.jpg)
*A class called Robot, and two object instances of this class.*

### Classes and Objects

#### Example: Designing a Robot Class

### Attributes and Methods

#### Example: Robot Attributes and Behaviors

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

Use a robot example where a Robot object contains multiple Sensor objects and interacts with a Controller object. Explain how these relationships work in a real-world scenario, making the concepts clear and relatable.

## The Four Pillars of OOP: A PIE

### Abstraction

#### Example: Simplifying Complex Robot Systems

### Polymorphism

#### Example: Interchanging Robot Components

### Inheritance

#### Example: Specialized Robot Types

### Encapsulation

#### Example: Protecting Robot Data
