# Warehouse Management System (Java)

Warehouse management system developed in Java, focusing on **object-oriented design**, **data structures**, and **business logic implementation**.  
The application operates via a **command-line interface** and supports product management, order processing, sales tracking, and file-based persistence.

## Features
- Product hierarchy using inheritance and polymorphism
- Support for multiple product categories (Home Devices, Gaming Devices, Image & Sound Devices)
- Order and sales management
- Stock updates and pricing logic
- File-based persistence (read/write from text files)
- Modular and maintainable class design

## Architecture Overview
The system is structured around a core `Product` abstraction, extended by multiple specialized product types.  
Orders and sales are processed through dedicated classes, while file I/O is handled via separate reader and writer components.

An overview of the class design and relationships is illustrated below:

![Class Diagram](assets/warehouse_class_diagram.png)

## Tech Stack
- Java
- Object-Oriented Programming (OOP)
- File I/O
- Data Structures
- Command-Line Interface (CLI)

## How It Works (High-Level)
1. Products, orders, and sales are loaded from files at startup
2. Users interact with the system via a menu-driven CLI
3. Business logic handles stock, pricing, and order status
4. Updated data is persisted back to files upon exit

## What I Learned
- Designing clean object-oriented systems in Java
- Applying inheritance and polymorphism to real-world problems
- Separating business logic from file handling
- Writing maintainable and readable backend-oriented code
