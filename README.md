# 📁 Employee Management System (First Semester Project)

A simple command-line-based **Employee Management System** written in C, designed as part of a first-semester Computer Engineering course. The project allows basic CRUD operations on employee records and interacts with a CSV file for data persistence.

---

## 📌 Features

* ✅ Create a new CSV file for employee records
* 📖 Read and display all records
* 📝 Append new employee records
* ➕ Add new employee details
* ✏️ Edit existing employee records by ID
* ❌ Delete specific employee entries
* 🔍 Query and display information of an employee by ID

---

## 🛠️ Technologies Used

* **Language**: C
* **File Format**: CSV (Comma-Separated Values)
* **Compiler**: GCC / Code::Blocks

---

## 📂 File Structure

```
📁 EmployeeManagementSystem/
├── employees.csv      # Data file for employee records
├── main.c             # Source code
└── README.md          # Project documentation
```

---

## 🧠 Functional Overview

* **Data Model**: `Employee` struct with fields like ID, Name, Contact, Address, Post, Email, Salary.
* **Storage**: Uses a fixed-size array to hold up to 100 employees.
* **Persistence**: File operations are done using standard C I/O to read/write CSV files.

---

## 🚀 Getting Started

### 1. Compilation

Use any C compiler to compile:

```bash
gcc main.c -o employee_management
```

### 2. Run the Program

```bash
./employee_management
```

### 3. Menu Options

```
1. Create a new File
2. Read a file
3. Append the file
4. Add an employee
5. Edit specific records given employee ID
6. Delete a certain record of an employee
7. Generate a query for an employee
8. Exit
```

---

## 📋 Sample Entry Format (CSV)

```
EmpID,Name,Contact No.,Address,Post,Email,Salary
101,JohnDoe,9800000000,NewYork,Manager,john@example.com,65000.00
```

---

## 🎯 Educational Objectives

* Practice with C structures and file handling
* Understand how to design and manipulate custom data models
* Develop structured menu-driven command-line applications

---

## 🧑‍💻 Contributors

* Siddharth *(Computer Engineering, First Semester)*

---

## 📎 License

This project is open-source and can be reused for educational purposes.

---

## 🙌 Acknowledgements

Thanks to faculty and peers for continuous guidance and support during the development of this project.

---
