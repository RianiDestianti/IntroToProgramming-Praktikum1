# Student Profile and Course Information Program

A Python application designed to process and display structured student profile data along with course details using basic programming and computational logic concepts.

---

## Program Features

- **Structured Variable Declaration:** Uses appropriate data types (`str` and `int`) to represent student and academic information.
- **Formatted Output:** Utilizes Python `f-strings` for clean and readable text alignment.
- **Dynamic Separator Lines:** Uses string multiplication to generate clean horizontal border lines.

---

## Computational Logic Reflection

1. **Variable Declaration**  
   The program stores information using appropriate data types, such as strings (`str`) for names, ID numbers, and study programs, and integers (`int`) for entry year, age, and course credits. This ensures that academic records are structured and managed efficiently.

2. **String Formatting (f-strings)**  
   The program uses `f"..."` expressions within `print()` functions to dynamically inject variable values into formatted text lines. This approach keeps the code concise, readable, and more efficient than traditional string concatenation.

3. **String Repetition Operator (`*`)**  
   By using `"=" * 45` and `"-" * 45`, the program generates border lines programmatically. This demonstrates computational efficiency by eliminating manual character repetition.

---

## Python Source Code

```python
studentName     = "Riani Destianti"
studentId       = "26552011036"
studyProgram    = "Informatics Engineering"
universityName  = "Universitas Teknologi Bandung"
entryYear       = 2026
age             = 18

courseCode      = "IF-KK1003"
courseName      = "Introduction to Programming"
courseCredit    = 3
semesterTerm    = 1
classSchedule   = "Saturday, 20:25 WIB"

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
