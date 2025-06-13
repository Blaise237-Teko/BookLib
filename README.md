# 📚 Book Library Management System

A simple Java Swing-based desktop GUI application to manage your personal book library — store books, track reading status, and visualize statistics using an embedded SQLite database.

---

## 🚀 What the App Does

This Book Library Manager allows users to:

- 📥 **Add New Books** (Title, Author, Genre, Status)
- 📋 **View All Books** in a searchable table
- 🔍 **Search & Filter** by title, author, or genre
- ✅ **Mark Books as Read/Unread**
- 🧮 **View Stats**: Total, Read, Unread
- 📈 **Visualize** data with bar/pie charts using JFreeChart
- 💾 **Save Permanently** using SQLite database

---

## 🧰 Tech Stack & Libraries

| Tool          | Purpose                            |
|---------------|------------------------------------|
| Java (JDK 11+) | Core application logic             |
| **Swing**     | GUI for forms, buttons, tables     |
| **SQLite (JDBC)** | Embedded database for storage  |
| **JFreeChart**| Chart library for data visualization |

---
```
## 📁 BookLibrary/
book-library-externalfiles/
├── lib/                       # External libraries
│   ├── sqlite-jdbc.jar        # JDBC driver for SQLite
│   └── jfreechart.jar         # Library for visual charts
├── src/
│   ├── gui/
│   │   ├── AddBookForm.java
│   │   ├── BookTablePanel.java
│   │   └── DashboardPanel.java
│   ├── dao/
│   │   └── BookDAO.java
│   ├── database/
│   │   └── Database.java
│   ├── model/     # Book.java, DAO classes
│   │   └── Book.java
│   ├── chart/
│   │   └── StatsChart.java
│   └── Main.java      # App entry point
├── db/
│   └── books.db
├── README.md
├── .gitignore
└── BookLibrary.launch   (optional for Eclipse)
```
