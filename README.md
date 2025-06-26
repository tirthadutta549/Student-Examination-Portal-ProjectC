# 📚 Student Examination Library Management System (C Language)

## 📌 Overview

This project implements a **Library Management System** in C, tailored for student examination or learning purposes. It allows for basic operations such as adding books and borrowers, borrowing and returning books, and printing the current state of the library.

The system uses structured programming and employs custom `struct` types to model Books, Borrowers, and the Library.

---

## 🧱 Data Structures

### Book
Represents a single book in the library.
```c
struct Book {
    int id;
    char title[50];
    char author[50];
    int is_available;  // 1 if available, 0 otherwise
};
