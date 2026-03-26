Student Management System
Description
A simple command-line based Student Management System built in Python that
allows users to do CRUD operations on
student records. It uses a CSV file for managing data, making
it lightweight + speed efficient to use.
The application follows a modular design with separate files for the user interface
(CLI menu) and core business logic, ensuring clean code organization and
maintainability.
Requirements
• Python[Latest Version]
Installation
1. Either Download the repository OR download and extract the ZIP file.
2. Find the project directory:
3. cd student-management-system
No additional installation required - The project uses only Python’s
built-in libraries.
How to Run
1. Open a terminal/command prompt \.
2. Execute the main program:
3. python main.py
Follow the on-screen menu to interact with the system:
– Enter the number corresponding to your desired action
– Follow the prompts to input student data
– The program will run endlessly until you specifically quit.
Example Usage
===== Student Management System =====
1. Add Student
2. View Students
3. Search Student
4. Update Student
5. Delete Student
6. Exit
=====================================
Enter your choice (1-6): 1
Enter Student ID: 101
Enter Name: Tejas
Enter Age: 20
Enter Course: CSE
Student added successfully!
Features
• Add Student: Add new student records with ID, Name, Age, and Course
information.
• View Students: Retrieve and print all stored student records.
• Search Student: Find a specific student by their unique ID
• Update Student: Modify existing student information
• Delete Student: Remove student records from the system
• Persistent Storage: Data is saved in the data.csv file.
• CLI Interface: User Friendly command line interface.
• No External Dependencies: Uses only Python’s built-in libraries and has a clean landing
page code and logic code which are kept separate.
• Modular Design: Clean separation between UI and business logic
File Structure
student-management-system/
│ ├── main.py Interface
│ └── Displays CLI menu and handles user input
│ └── Calls functions from student_manager.py based on user
choice
│ └── Runs in a loop until user exits
│ ├── student_manager.py
│ ├── init_file()
if not exists
│ ├── add_student()
│ ├── view_students()
records
│ ├── search_student()
│ ├── update_student()
information
│ └── delete_student()
│ ├── data.csv
│ └── Stores student records in CSV format (ID, Name, Age,
Course)
│ └── Example: 24BCE10826,Tejas Saxena,18,Core-CSE
│ └── README.md
Module Descriptions
File Purpose
main.py student_manager.py data.csv Acts as the controller/UI layer providing the
CLI interface
Handles all data operations (CRUD) and
file I/O
Simple database storing student records
persistently
Note: The data.csv file is already and will be created on first run if it doesn’t
exist. Do not manually modify this file to avoid data corruption.
