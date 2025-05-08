# Java Paint App

A Java Swing-based paint application that allows users to draw freely on a canvas, change brush colors using RGB selection, and manage user login/signup with MySQL integration.

---

## Features

- ✅ User Login & Signup (MySQL backend)
- ✅ Singleton pattern for database connection
- ✅ Freehand drawing on canvas
- ✅ RGB color selection using `JColorChooser`
- ✅ Clear canvas functionality
- ✅ Organized code with OOP principles

---

## Technologies
- **Java** — Core programming language
- **Swing (JFC)** — For GUI components
- **JDBC (Java Database Connectivity)** — To interact with MySQL
- **MySQL** — Relational database for user authentication
- **Graphics2D** — For drawing on the canvas
- **Intellij Idea** — Primary IDE for development  
- **Git** — Version control
---
## Setup Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/java-paint-app.git
cd java-paint-app
CREATE DATABASE paint_app;
USE paint_app;
```
### 2. MySQL Setup
```bash
CREATE TABLE user (
  id INT AUTO_INCREMENT PRIMARY KEY,
  username VARCHAR(255) NOT NULL UNIQUE,
  password VARCHAR(255) NOT NULL
);
```
### 3. Update Your Database Credentials
```bash
connection = DriverManager.getConnection(
  "jdbc:mysql://localhost:3306/paint_app", "root", "your_password"
);
```

### 4. Compile and Run
java main


