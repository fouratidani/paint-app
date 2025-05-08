# 🎨 Java Paint App

A Java Swing-based paint application that allows users to draw freely on a canvas, change brush colors using RGB selection, and manage user login/signup with MySQL integration.

---

## ✨ Features

- ✅ User Login & Signup (MySQL backend)
- ✅ Singleton pattern for database connection
- ✅ Freehand drawing on canvas
- ✅ RGB color selection using `JColorChooser`
- ✅ Clear canvas functionality
- ✅ Optional undo/redo support
- ✅ Organized code with OOP principles

---

## 🧩 Project Structure

.
├── DrawArea.java # Drawing canvas component
├── LoginGUI.java # Login interface
├── SignupGUI.java # Signup interface
├── LoginDAO.java # Handles login database logic
├── SignupDAO.java # Handles signup database logic
├── Singleton.java # Singleton DB connection class
├── PaintGUI.java # Paint interface after login
└── README.md # Project documentation
