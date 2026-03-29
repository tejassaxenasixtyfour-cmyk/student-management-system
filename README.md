Student Management System is a computer based software to handle student records through a computer's terminal. It mainly allows the computer to perform CRUD operations.  
1. Creating new student data.
2. Fetching student data.
3. Updating student details.
4. Deleting student data.  
 
Because it is built with Python + Python’s libraries built-in tools, it doesn't require any complex software, It simply executes on the computer’s terminal. making it a lightweight and sharable software that can run on everyone’s computer.

This project is built in two parts. which means the landing page and the logic-business layers are kept separate.The main.py is the landing page, it’s job is to display a numbered menu and each number corresponds to a task that can be performed. While the student_manager.py is the logic layer, It has the logic to perform the selected task. This separation makes it easier to scale the program in the future. 

The data.csv file is responsible for storage of the data. This weather data will not be lost when the program terminates, this file will be stored in the computer’s ROM. After the program is terminated and restarted again, the file will pick off where it was last left off. This makes the software a reliable and organized way to manage a student records.

