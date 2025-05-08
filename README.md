# 🎨 Java Paint App

A Java Swing-based paint application that allows users to draw freely on a canvas, change brush colors using RGB selection, and manage user login/signup with MySQL integration.

---

## ✨ Features

- ✅ User Login & Signup (MySQL backend)
- ✅ Singleton pattern for database connection
- ✅ Freehand drawing on canvas
- ✅ RGB color selection using `JColorChooser`
- ✅ Clear canvas functionality
- ✅ Organized code with OOP principles

---

---

## ⚙️ Setup Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/java-paint-app.git
cd java-paint-app
CREATE DATABASE paint_app;
USE paint_app;

```bash
CREATE TABLE user (
  id INT AUTO_INCREMENT PRIMARY KEY,
  username VARCHAR(255) NOT NULL UNIQUE,
  password VARCHAR(255) NOT NULL
);
