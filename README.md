# 🚗 Vehicle Registration System

A Java-based Vehicle Registration System designed to manage vehicle records efficiently using Java Core and Object-Oriented Programming principles.

## 📌 Project Overview

The Vehicle Registration System is a console-based application that allows users to register, manage, and track different types of vehicles.

The project focuses on applying core Java concepts through a practical system, emphasizing clean code, object-oriented design, data validation, and exception handling.

## ✨ Features

- Register different types of vehicles.
- Support Cars, Trucks, and Motorcycles.
- Store and manage vehicle information.
- Search vehicles using plate numbers.
- Update vehicle owner information.
- Remove registered vehicles.
- Display all registered vehicles.
- Prevent duplicate vehicle registration.
- Validate vehicle data.
- Handle errors using custom exceptions.

## 🛠️ Technologies Used

- Java
- Object-Oriented Programming (OOP)
- Collections Framework
- Exception Handling
- Java Core

## 🧱 Project Architecture

The project is organized into multiple packages to separate responsibilities and improve maintainability.

### Entities
Contains the vehicle hierarchy and domain entities.

- `Vehicle` – Abstract base class containing common vehicle attributes.
- `Car` – Represents cars with additional attributes such as number of doors.
- `Truck` – Represents trucks with cargo capacity.
- `Motorcycle` – Represents motorcycles with engine type.

### Registration System
- `RegistrationSystem` – Responsible for managing registered vehicles and performing registration operations.

### Validation & Exceptions
- Validation logic for vehicle data.
- Custom exceptions for invalid operations.
- Duplicate plate number handling.

## 🧠 OOP Concepts Applied

- **Encapsulation:** Protecting vehicle data through private fields and controlled access.
- **Abstraction:** Defining common vehicle behavior through an abstract `Vehicle` class.
- **Inheritance:** Reusing common properties across different vehicle types.
- **Polymorphism:** Managing different vehicle types through the common `Vehicle` reference.
- **Method Overriding:** Customizing behavior in subclasses.

## 📚 Java Core Concepts

This project demonstrates practical applications of:

- Classes and Objects
- Constructors
- Abstract Classes
- Inheritance
- Polymorphism
- Encapsulation
- Collections Framework
- Exception Handling
- Custom Exceptions
- Data Validation
- Object-Oriented Design

## 📂 Project Structure

```text
VehicleRegistrationSystem/
│
├── Entities/
│   ├── Vehicle.java
│   ├── Car.java
│   ├── Truck.java
│   └── Motorcycle.java
│
├── RegistrationSystem/
│   └── RegistrationSystem.java
│
├── ValidatorAndException/
│   ├── Validator.java
│   └── Custom Exceptions
│
└── Main.java
```

## 🎯 Learning Objectives

The main goal of this project is to strengthen Java Core knowledge through practical implementation and to develop a better understanding of object-oriented programming and software design.

## 👨‍💻 Author

**Mohamed Yasser**

- GitHub: [MohammedYa](https://github.com/MohammedYa)

---

⭐ If you find this project useful, feel free to explore the repository and share your feedback.
