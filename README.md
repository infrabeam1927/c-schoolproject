# 📘 Student Report Card Management System

A console-based C++ application for managing student academic records, including marks, grades, and reports, using file handling with binary files.

---

## 📌 Features

- Add new student records
- Display all student records
- Search for a student by roll number
- Modify an existing student record
- Delete a student record
- Generate class-wise grade report
- Generate individual student report card
- Simple menu-driven user interface

---

## 🛠️ Technologies Used

- **Language:** C++
- **File Handling:** Binary file operations (`fstream`)
- **Console I/O:** `cin`, `cout`, `clrscr`, `getch`
- **Legacy Headers:** `<iostream.h>`, `<fstream.h>`, `<conio.h>` *(Use a compatible compiler like Turbo C++ or adapt for modern compilers)*

---

## 🚀 Getting Started

### Requirements

- Turbo C++ or DOSBox (for legacy header compatibility)
- Or, for modern systems:
  - Replace old headers with `#include <iostream>`, `#include <fstream>`, etc.
  - Remove `clrscr()` and `getch()` or replace with standard equivalents

### Compilation

For Turbo C++:
```bash
Open Turbo C++ > Open Project > Compile (Alt + F9) > Run (Ctrl + F9)
```
For modern compilers (like g++), you may need to modify the code:
'''bash
g++ -o student_report student.cpp
./student_report
'''
### Contribution
Let me know if you’d like a version tailored for **modern C++ (like `g++`)** or you plan to run this project on **Windows/macOS/Linux** without Turbo C++.

