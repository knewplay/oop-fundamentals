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

Programming in general became necessary once computers were developed to perform calculations and automate tasks. In the early days of computing, programming was primarily procedural, meaning that programs were written as sequences of instructions that operated on data. Procedural programming is in fact all we did in the Programming Essentials book: writing commands that the computer processes in sequential order.

Early programming languages like Fortran and COBOL, developed in the 1950s and 1960s, focused on solving mathematical problems and handling business-related tasks such as payroll processing and inventory management by manipulating variables and executing commands step-by-step. The C programming language, developed in the early 1970s, further advanced procedural programming by providing powerful features for creating operating systems and complex software applications.

The concept of Object-Oriented Programming (OOP) first emerged in the 1960s with the creation of Simula, a programming language developed in Norway. Simula introduced the idea of simulating real-world entities and processes, marking a significant departure from the purely procedural approach. This new method allowed programmers to model complex systems more naturally and intuitively, paving the way for more advanced and flexible software designs.

In the 1980s, OOP gained more traction with the development of C++, which built upon the C programming language by adding features that supported OOP. There was a necessity for this evolution because as software systems grew in size and complexity, the procedural approach became increasingly difficult to manage. OOP addressed these challenges by promoting code reusability, modularity, and easier maintenance through the use of objects and classes (which we will get to in the next section).

The 1990s saw the rise of Java and Python. Java's ability to run on any computer system and Python's simplicity and readability brought OOP to a broader audience. Both languages became popular for their versatility and wide range of built-in tools, influencing software development practices across various domains.

Today, OOP is a fundamental concept in computer science education and a standard practice in software development across various domains. Its principles help developers manage complexity, improve code reusability, and create scalable software solutions, making it an essential skill for modern programmers.

## Building Blocks of OOP

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
