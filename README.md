📚 Library Book Management System

Course: Data Structures (ENCS205)
Semester: 3rd — B.Tech CSE
Assignment No: 02
Theme: Linear Data Structures – Single Linked List & Stack
Submitted by: Aryan Mishra
Roll No: 2401010304
Session: 2025–26

🧩 Project Overview

This console-based application simulates a Library Book Management System using:

Single Linked List for dynamic book management

Stack for tracking recent transactions (Issue/Return) and supporting Undo functionality

The system enables inserting, deleting, issuing, returning, and undoing transactions of books dynamically — fully satisfying the assignment’s learning outcomes.

⚙️ Key Features

✅ Add (Insert) new books to the library
✅ Delete books using Book ID
✅ Issue or return books
✅ Undo the last transaction (Issue/Return) using a stack
✅ Display all available books
✅ View all recent transactions
✅ Console-based menu-driven interface

🧠 Data Structures Used
Structure	Purpose
Single Linked List	To store and manage all book records dynamically
Stack (Linked Implementation)	To record transactions and enable Undo operation
🧱 Classes Overview
Class	Description
Book	Represents a book record node in the linked list
BookList	Manages book operations (insert, delete, search, display)
Transaction	Represents a transaction node in the stack
TransactionStack	Implements stack operations (push, pop, view)
LibrarySystem	Handles user operations and integrates linked list + stack
LibraryManagement	Main class containing the program’s entry point
💻 How to Run
Step 1: Save the Java file

Save your code as:

LibraryManagement.java

Step 2: Compile the program
javac LibraryManagement.java

Step 3: Run the program
java LibraryManagement

🧪 Sample Input / Output
Input Example
===== Library Book Management System =====
1. Insert Book
2. Delete Book
3. Issue Book
4. Return Book
5. Undo Last Transaction
6. View All Books
7. View Transactions
8. Exit
Enter your choice: 1
Enter Book ID: 101
Enter Title: Data Structures
Enter Author: Narasimha Karumanchi
✅ Book inserted successfully.

Output Example
---------- Library Books ----------
Book ID: 101 | Title: Data Structures | Author: Narasimha Karumanchi | Status: Available
-----------------------------------

Undo Example
Book ID: 101 issued successfully.
↩️ Undo successful for Book ID: 101

📋 Assignment Objectives Covered

✔ Apply single linked list to manage dynamic book records
✔ Implement stack to handle undo operations
✔ Integrate two linear data structures in a practical scenario
✔ Simulate real-world problem solving in library management
✔ Demonstrate algorithmic thinking in operation design

📅 Submission Details

Submission Date: 29th October 2025

Mode: GitHub repository link submission


👨‍💻 Author

Name: Aryan Mishra
Roll No: 2401010304
Course: B.Tech CSE — 3rd Semester
Year: 2025–26
