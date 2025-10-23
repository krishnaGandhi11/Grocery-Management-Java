🛒 Grocery Management System (Java)

📖 Overview

This project is a Java-based Grocery Management System built to demonstrate Object-Oriented Programming (OOP) concepts in action — Inheritance, Encapsulation, and Polymorphism.

As a B.Tech CSE student, I wanted to move beyond theory and actually feel how OOPs simplifies complex logic.
The “click” moment came when I implemented the showInventory() method.
Instead of writing multiple if-else checks for Fruits, Vegetables, or Dairy, I looped through a list of grocery items and simply called:

gItem.displayDetails();


Java’s runtime polymorphism handled the rest — automatically calling the correct method for each specific object.
That single line of code made the entire system modular, clean, and scalable.

🧠 Key Concepts Demonstrated

Inheritance: Base class GroceryItem extended by Fruit, Vegetable, and DairyProduct.

Encapsulation: Private fields with public getters and setters.

Polymorphism: Unified method call displayDetails() for multiple product types.

Abstraction: Service classes like InventoryService hide internal logic.

⚙️ Project Structure
GROSSERY/
│
├── models/
│   ├── GroceryItem.class
│   ├── Fruit.class
│   ├── Vegetable.class
│   ├── DairyProduct.class
│
├── services/
│   ├── InventoryService.class
│   ├── InventoryServiceImpl.class
│
├── utils/
│   └── Main.class
│
└── ...

💡 Features

Add, remove, and display grocery items.

Categorized models for fruits, vegetables, and dairy products.

Demonstrates clean architecture using OOP principles.

Perfect for beginners learning Java and object-oriented design.

🚀 How to Run

Clone this repository:

git clone https://github.com/krishgandhi/Grocery-Management-Java.git


Open in VS Code or any Java IDE.

Compile and run:

javac Main.java

java Main

🧩 Tech Stack

Language: Java

Concepts: OOP, Encapsulation, Inheritance, Polymorphism

Tools: VS Code / IntelliJ IDEA

🌟 Reflection

OOPs concepts felt boring in theory — but magical in practice.
Building this project made me realize how Inheritance and Polymorphism aren’t just exam topics — they’re the blueprint for writing scalable and intelligent software.

This hands-on experience genuinely fired me up to dive deeper into backend development and understand how clean architecture powers real-world systems.

🏷️ Tags

#Java #BackendDevelopment #OOPs #Programming #LearningByDoing #StudentProject
