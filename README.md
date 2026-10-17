Student Profile & Course Information System

A simple Python-based application designed to display student profile information and enrolled course details in a structured format using string manipulation and output formatting.

This project was developed as part of the Independent Practical Work for the Introduction to Programming Course (IF-KK1003) at Universitas Teknologi Bandung.

Program Description

This program implements foundational Python programming concepts, such as variable declaration, data type modeling (string and integer), and text formatting using formatted string literals (f-strings).

Computational Logic & Concepts

Variable Declaration & Data Types
Utilizes the str data type for textual information (such as student name, ID, and course name) and the int data type for numerical values (such as age, course credits, semester term, and entry year).

String Formatting (f-strings)
Employs f-strings to inject variable values directly into output strings in a dynamic and clean manner, eliminating the need for manual string concatenation (+).

String Manipulation Operator (*)
Leverages the string multiplication operator (e.g., "=" * 45) to automatically generate consistent line dividers.

Program Source Code

# Student Profile Data
studentName     = "Riani Destianti"
studentId       = "26552011036"
studyProgram    = "Informatics Engineering"
universityName  = "Universitas Teknologi Bandung"
entryYear       = 2026
age             = 18

# Course Information Data
courseCode      = "IF-KK1003"
courseName      = "Introduction to Programming"
courseCredit    = 3
semesterTerm    = 1
classSchedule   = "Saturday, 20:25 WIB"

# Output Formatting
print("=" * 45)
print("            STUDENT PROFILE")
print("=" * 45)
print(f"Name           : {studentName}")
print(f"Student ID     : {studentId}")
print(f"Age            : {age} years old")
print(f"Study Program  : {studyProgram}")
print(f"University     : {universityName}")
print(f"Entry Year     : {entryYear}")
print("-" * 45)
print("           COURSE INFORMATION")
print("-" * 45)
print(f"Course Code    : {courseCode}")
print(f"Course Name    : {courseName}")
print(f"Credits (SKS)  : {courseCredit}")
print(f"Semester       : {semesterTerm}")
print(f"Schedule       : {classSchedule}")
print("=" * 45)


Sample Output

=============================================
            STUDENT PROFILE
=============================================
Name           : Riani Destianti
Student ID     : 26552011036
Age            : 18 years old
Study Program  : Informatics Engineering
University     : Universitas Teknologi Bandung
Entry Year     : 2026
---------------------------------------------
           COURSE INFORMATION
---------------------------------------------
Course Code    : IF-KK1003
Course Name    : Introduction to Programming
Credits (SKS)  : 3
Semester       : 1
Schedule       : Saturday, 20:25 WIB
=============================================


How to Run

Clone this repository or copy the script.

Execute the script via command line:

python main.py


Alternatively, open and execute the file in Google Colab or Jupyter Notebook.

Created by Riani Destianti — Informatics Engineering, Universitas Teknologi Bandung
