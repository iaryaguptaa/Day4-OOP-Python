# Day 4: Object-Oriented Programming (OOP)

This repository contains my Jupyter Notebook submission for the **Day 4** self-learning assignment of the Data Science Internship. The module focuses on designing modular, scalable, and reusable Python applications using Object-Oriented Programming principles.

## Core OOP Concepts Covered
* **Classes and Objects:** Blueprints and their physical instances.
* **Constructors (`__init__`):** Object initialization.
* **Encapsulation:** Data hiding using private variables (e.g., `__balance`).
* **Inheritance:** Parent-Child class relationships and code reusability using `super()`.
* **Polymorphism & Method Overriding:** Same method names exhibiting different behaviors.
* **Abstraction:** Hiding complex implementations using Abstract Base Classes (`ABC`).

## Practice Projects Included
The enclosed Jupyter Notebook (`Day4_OOP.ipynb`) contains the following implementations:
1. **Student Management System:** Demonstrates basic class creation, attributes, and instance methods for calculating grades.
2. **Bank Account System:** Implements **Encapsulation** by restricting direct access to the account balance using private variables.
3. **Employee Management:** Demonstrates **Inheritance** where a `Manager` child class inherits and extends the functionality of an `Employee` parent class.
4. **Vehicle System:** Showcases **Polymorphism** and **Method Overriding** where `Car` and `Bike` classes override a generic `start()` method.
5. **Shape Area Calculator:** Applies **Abstraction** using Python's `abc` module to enforce the implementation of an `area()` method in child classes.
6. **Library Management System (Mini-Project):** A comprehensive system combining multiple classes (`Book`, `Member`, `Library`) that interact with each other to issue, return, and track available books.

## Tech Stack
* **Language:** Python 3
* **Environment:** Jupyter Notebook (VS Code)

## 🚀 How to View
Since the code is written in a Jupyter Notebook (`.ipynb`), you can view the code, theory notes, and executed outputs directly on GitHub by simply clicking on the file.
