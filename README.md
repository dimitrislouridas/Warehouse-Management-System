# 📦 Warehouse Management System (Java)

A warehouse management system developed in **Java**, focusing on **object-oriented design**, **data structures**, and **business logic implementation**.  
The application operates via a **command-line interface (CLI)** and supports product management, order processing, sales tracking, and file-based persistence.

---

## ✨ Features
- Product hierarchy using **inheritance** and **polymorphism**
- Support for multiple product categories:
  - Home Devices
  - Gaming Devices
  - Image & Sound Devices
- Order and sales management
- Stock updates and pricing logic
- File-based persistence (read/write from text files)
- Modular and maintainable class design

---

## 🏗 Architecture Overview
The system is structured around a core **`Product` abstraction**, extended by multiple specialized product types.  
Orders and sales are handled through dedicated domain classes, while **file I/O responsibilities are separated** into reader and writer components.

An overview of the class design and relationships is illustrated below:

![Class Diagram](assets/warehouse_class_diagram.png)

---

## ⚙️ How It Works (High-Level)
1. Products, orders, and sales are loaded from files at startup
2. Users interact with the system via a **menu-driven CLI**
3. Business logic manages stock levels, pricing, and order status
4. Updated data is persisted back to files upon exit

---

## 🛠 Tech Stack
- **Java**
- Object-Oriented Programming (OOP)
- File I/O
- Data Structures
- Command-Line Interface (CLI)

---

## 📚 What I Learned
- Designing clean and extensible **object-oriented systems** in Java
- Applying **inheritance and polymorphism** to real-world business models
- Separating business logic from persistence and I/O layers
- Building maintainable, backend-oriented applications
