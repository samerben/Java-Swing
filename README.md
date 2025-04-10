# 💄 Cosmetic Product Management – Java Swing

A desktop application for managing cosmetic products, built using Java Swing and MySQL.  
This project offers admin login, product and category management, client handling, and order tracking.

## 🖥 About the Project
This application was developed to simulate a complete desktop system for a cosmetic shop.  
It includes UI forms built in Java Swing and connects to a MySQL database for data storage and retrieval.

## 🛠 Tech Stack
- Java (Swing GUI)
- MySQL
- JDBC

## 📦 Features
- 🔐 Admin login interface
- 🧴 Add/Edit/Delete cosmetic products
- 🗂️ Category management
- 🛒 View and manage customer orders
- 👤 Client & employee database integration
- Live product listing and basic filtering

## 🧩 Main Java Classes

| Class Name         | Description                                 |
|--------------------|---------------------------------------------|
| `Accueil.java`     | Main dashboard UI                           |
| `Categorie.java`   | Category management                         |
| `Client.java`      | Client data interface                       |
| `Employe.java`     | Employee management                         |
| `ListeCommande.java`| View orders placed by clients              |
| `Login_Admin.java` | Login form for admin authentication         |
| `Produit.java`     | Product management (CRUD)                   |
| `MysqlConnection.java` | Manages database connection              |


## 🖼 Screenshots
_Add screenshots of the login screen, dashboard, and product list UI here for better showcase._

## ▶️ Running the App

1. Make sure MySQL server is running.
2. Import the provided SQL script into your MySQL server (if available).
3. Update your `MysqlConnection.java` with your own DB credentials.
4. Compile & Run the app using your IDE (Eclipse, IntelliJ, NetBeans...).

```java
// Sample DB Config
String url = "jdbc:mysql://localhost:3306/cosmetic_db";
String user = "root";
String password = "";
