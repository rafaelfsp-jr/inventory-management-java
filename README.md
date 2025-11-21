# 📦 Inventory Management System
[![Project Status](https://img.shields.io/badge/Status-In%20Development-yellow)]()

A basic console-based Inventory Management System built with Java using Object-Oriented Programming (OOP) principles.
The mainly focus is simulate the basic invetory operations.

## ✨ Functionalities

* 🆕**Product creation:** Creates a new product with name, price and barcode.
* ✏️**Addition and updates invetory:** Allows adding a new quantity or update an existing product, using the name or the barcode.
* 🔎**Listing:** Displays all products currently in stock.
* 📋**Interative menu:** Console interface (CLI) for user interaction.

## 🏗️ Project Structure

The project is divided into three main classes following the Separation of Concerns (SoC) principle.

* **`Inventory.java`**: Represents the **Product/Item entity** in the stock.
* **`StockManager.java`**: Responsible for **Business Logic**, managing the collection of `Inventory` objects.
* **`MainApp.java`**: Contains the `main` method.

## 🛠️ Used technologies

* **Java 21**
* **IDE:** VS Code

## ⚙️ How to run the project

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/rafaelfsp-jr/inventory-management-java
    ```
2.  **Compile:** Compile o projeto usando o seu IDE ou terminal:
    ```bash
    javac Inventory.java StockManager.java MainApp.java
    ```
3.  **Execute:**
    ```bash
    java MainApp
    ```
