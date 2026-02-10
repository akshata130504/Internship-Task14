# Internship-Task14

# 📦 Java Developer Internship – Task 14  
## Mini Project: Console-Based Inventory Management System

## 📌 Project Objective
The objective of this mini project is to build a **console-based Inventory Management System** using **Core Java concepts** such as OOP, Collections, File Handling, and Exception Handling.  
The system allows users to manage products efficiently and persist inventory data.

## 🛠 Tools Used
- **Language:** Java  
- **IDE:** IntelliJ IDEA / Eclipse  
- **Collections:** HashMap  
- **File Handling:** Serialization (ObjectInputStream / ObjectOutputStream)  
- **JDK Version:** Java 17 / Java 21  

## 📂 Project Structure
Java-Internship-Task-14
│
├── src
│ ├── Product.java
│ └── InventoryApp.java
│
├── inventory.txt
└── README.md

## 🧩 Features Implemented

- Designed a **Product class** with id, name, quantity, and price

- Stored products using **HashMap** for fast lookup
  
- Implemented CRUD operations:
  
  - Add product
    
  - Update product
    
  - Delete product
    
  - View inventory
    
- Ensured **unique product IDs**
  
- Displayed inventory summary in formatted output
  
- Persisted inventory data using **file handling**
  
- Loaded saved inventory data on application restart\
  
- Handled invalid user inputs gracefully
  
- Refactored logic into reusable methods

## ▶️ How to Run the Application

Compile and run the program from the `src` directory:

     ```bash
     javac Product.java InventoryApp.java
     java InventoryApp
     
## 💻 Sample Console Output

=== Inventory Management ===

1. Add Product
  
2. Update Product
   
3. Delete Product
   
4. View Inventory
   
5. Exit

Enter Product ID: 101

Product added successfully.

--- Inventory Summary ---

ID: 101 | Name: Laptop | Qty: 5 | Price: 45000.00

## 📄 Inventory Data File

File created: inventory.txt

Stores serialized inventory data

Ensures data persistence across program executions

## 🧠 Key Design Decisions

🔹 Why HashMap for Inventory?

HashMap provides fast access using unique product IDs as keys.

🔹 Handling Duplicate Product IDs

The application validates product IDs and prevents duplicates.

🔹 Data Persistence

Inventory data is stored using serialization, allowing recovery after restart.

🔹 Data Consistency

Controlled CRUD operations and validations ensure consistent data.

🔹 Scalability Consideration

File-based storage works for small systems; databases are preferred for large-scale applications.

## 🎯 Learning Outcomes

Applied OOP principles in a real-world scenario

Used Java Collections effectively

Implemented data persistence using file handling

Built a menu-driven console application

Improved problem-solving and code organization skills
