Console-Based Library Management System

Project Overview

This is a Console-Based Library Management System developed using Java.
The system allows users to manage books and members efficiently using
Object-Oriented Programming principles and file-based data persistence.

The application is developed and executed using Spring Tool Suite (STS).

Project Objectives

- Implement OOP concepts (Encapsulation, Abstraction)
- Manage books and members
- Allow borrowing and returning of books
- Store data permanently using text files
- Practice Maven project structure in STS

Technologies Used

- Java (JDK 11 / 17)
- Spring Tool Suite (STS)
- Maven
- File Handling (BufferedReader & BufferedWriter)
- OOP Concepts

 Project Structure

```
week3-library-system
│
├── src/main/java/library
│   ├── Main.java
│   ├── Book.java
│   ├── Member.java
│   ├── Library.java
│   └── FileHandler.java
│
├── data
│   ├── books.txt
│   └── members.txt
│
├── pom.xml
├── .gitignore
└── README.md
```

Setup Instructions (Using STS)

Step 1: Extract the ZIP File

Right click on the zip → Extract All

Step 2: Open STS

Open Spring Tool Suite.

Step 3: Import Project

1. Click **File → Import**
2. Select **Maven → Existing Maven Projects**
3. Click **Next**
4. Browse and select the extracted folder
5. Click **Finish**

Step 4: Update Maven Project

Right click project →  
Maven → Update Project →  
✔ Check "Force Update" → OK

How to Run the Application in STS

1. Expand:
   src/main/java/library

2. Right click:
   Main.java

3. Click:
   Run As → Java Application

---

## 🖥 Sample Console Output

```
=== LIBRARY MANAGEMENT SYSTEM ===
1. Add New Book
2. View All Books
3. Register Member
4. Borrow Book
5. Return Book
6. Exit
Enter choice:
```

---

Features Implemented

✔ Add new book  
✔ View all books  
✔ Register member  
✔ Borrow book  
✔ Return book  
✔ Persistent storage using text files  
✔ Maven project structure  
✔ Console-based menu system  

Technical Details

Book Class
- Stores book details
- Attributes: id, title, author, isBorrowed
- Implements encapsulation using private variables and getters

Member Class
- Stores member details
- Attributes: id, name

Library Class
- Manages all business logic
- Handles add, borrow, return operations

FileHandler Class
- Handles reading and writing to:
  - books.txt
  - members.txt
- Uses:
  - BufferedReader
  - BufferedWriter

Testing Evidence

Tested following cases:

✔ Adding multiple books  
✔ Registering multiple members  
✔ Borrowing available book  
✔ Prevent borrowing already borrowed book  
✔ Returning book  
✔ Data persistence after restart  



Spring Tool Suite (STS)  
Java Maven Project Structure  

---

# ✅ Project Completed Successfully
