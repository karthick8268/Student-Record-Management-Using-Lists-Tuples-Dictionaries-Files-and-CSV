🎓 Student Record Management System Using Python

📌 Project Overview

The Student Record Management System is a Python-based application that demonstrates how to organize, store, and retrieve student information using fundamental Python data structures and file handling techniques.

This project uses Lists, Tuples, Dictionaries, Text Files, and CSV Files to manage student records.

It provides practical experience in handling structured data and performing file operations using Python.

🚀 Features

✅ Student Record Storage – Stores student details using lists and dictionaries.

✅ Tuple Implementation – Demonstrates immutable data storage using course information.

✅ Text File Generation – Automatically creates a text file containing student records.

✅ CSV File Generation – Exports student information into a structured CSV file.

✅ CSV File Reading – Retrieves and displays student records from the generated CSV file.

✅ Automated File Handling – Uses Python file handling operations to create, write, and read files.

🛠️ Technologies Used

- Programming Language: Python 3
- Development Environment: VS Code / Any Python IDE
- Python Module: csv (Built-in)
- Data Structures: List, Tuple, Dictionary
- File Formats: TXT and CSV

📂 Project Structure

Student-Record-Management/
│
├── main.py
├── students.txt
├── students.csv
└── README.md

Note: The "students.txt" and "students.csv" files are automatically generated when the Python program is executed.

⚙️ How to Run

Step 1: Install Python 3.

Step 2: Download or clone the GitHub repository.

Step 3: Open the project folder in VS Code or a terminal.

Step 4: Execute the Python program.

python main.py

Step 5: The program automatically generates the student record files and displays the CSV data.

📊 Student Information

The application initially contains three student records.

Roll No| Name| Department| Mark
101| Anitha| CSE| 86
102| Bala| CSE| 91
103| Chitra| ECE| 78

💻 Sample Output

Course Tuple: ('Python', 4)

--- Records from CSV ---

101 Anitha CSE 86
102 Bala CSE 91
103 Chitra ECE 78

📄 Generated Files

1. students.txt

Stores student records in a human-readable text format.

Example:

{'RollNo': '101', 'Name': 'Anitha', 'Department': 'CSE', 'Mark': 86}
{'RollNo': '102', 'Name': 'Bala', 'Department': 'CSE', 'Mark': 91}
{'RollNo': '103', 'Name': 'Chitra', 'Department': 'ECE', 'Mark': 78}

2. students.csv

Stores student information in a structured, comma-separated format.

RollNo,Name,Department,Mark
101,Anitha,CSE,86
102,Bala,CSE,91
103,Chitra,ECE,78

The CSV file can be opened using spreadsheet applications such as Microsoft Excel.

🧠 Python Concepts Implemented

1. Lists

Used to maintain a collection of student records.

2. Dictionaries

Used to store individual student details as key-value pairs.

3. Tuples

Used to represent fixed course information.

course = ("Python", 4)

4. File Handling

Demonstrates reading and writing files using Python's "open()" function and "with" statement.

5. CSV Module

Uses Python's built-in "csv" module for structured data storage and retrieval.

6. Loops

Uses "for" loops to process multiple student records efficiently.

🎯 Learning Outcomes

Through this project, I gained practical experience in:

- Understanding Python data structures.
- Organizing student information using dictionaries.
- Working with lists and tuples.
- Implementing text file operations.
- Exporting structured data into CSV files.
- Reading and processing CSV records.
- Developing basic data management applications.

🔮 Future Enhancements

- Add new student records dynamically.
- Implement student search functionality.
- Add options to update and delete records.
- Calculate student grades based on marks.
- Integrate SQLite database storage.
- Develop a menu-driven user interface.
- Create a web-based student management application.

📌 Important Note

This project uses predefined student records to demonstrate Python data structures and file handling.

The generated files are overwritten whenever the program runs.

The current version does not support interactive addition, modification, or deletion of student records.

👨‍💻 Developed By

Karthick B

Computer Science and Engineering Student

Chennai Institute of Technology

GitHub: "karthick8268" (https://github.com/karthick8268)

---

⭐ If you find this project useful, consider giving the repository a star!