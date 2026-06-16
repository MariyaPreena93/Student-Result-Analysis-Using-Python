# Student Result Analysis Using Python

## Overview

This project analyzes student academic records and generates useful insights such as topper details, average marks, grade assignments, and final result summaries.

It is a beginner-friendly Python project that demonstrates the use of lists, dictionaries, loops, conditional statements, and basic data analysis techniques.

## Features

* Find topper details
* Calculate average marks
* Identify students scoring above average
* Assign grades based on marks
* Generate PASS/FAIL results
* Display a complete student summary

## Sample Dataset

```python
students = [
    {"ID":2401,"name":"Soniya","marks":490},
    {"ID":2402,"name":"Reena","marks":380},
    {"ID":2403,"name":"Meha","marks":420},
    {"ID":2404,"name":"Ram","marks":320},
    {"ID":2405,"name":"Athul","marks":250},
    {"ID":2406,"name":"Rahul","marks":200}
]
```

## Functionality

### 1. Topper Identification

Finds the student with the highest marks and displays:

* Student ID
* Student Name
* Marks

### 2. Average Marks Calculation

Calculates the average marks of all students.

### 3. Above Average Performers

Displays students whose marks are greater than the class average.

### 4. Grade Assignment

Grades are assigned according to the following criteria:

| Marks Range   | Grade   |
| ------------- | ------- |
| 450 and above | Grade A |
| 350 - 449     | Grade B |
| 250 - 349     | Grade C |
| 200 - 249     | Grade D |
| Below 200     | Grade E |

### 5. Result Summary

Generates PASS/FAIL status for each student:

* Grade A → PASS
* Grade B → PASS
* Grade C → PASS
* Grade D → PASS
* Grade E → FAIL

## Technologies Used

* Python 3.x
* Lists
* Dictionaries
* Loops
* Conditional Statements
* Built-in Functions (`max()`, `sum()`)

## Project Structure

```text
Student_Result_Analysis/
│
├── student_result_analysis.py
├── README.md
```

## Sample Output

```text
------Topper Details--------

Student ID : 2401
Student Name: Soniya
Marks: 490

-----Average Marks-----

Average Mark: 343.33

-----Students who scored above average-----

Soniya -- 490
Reena -- 380
Meha -- 420

------Student Grade-----

Soniya -- Grade A
Reena -- Grade B
Meha -- Grade B
Ram -- Grade C
Athul -- Grade C
Rahul -- Grade D

-----Summary-----

{'ID': 2401, 'name': 'Soniya', 'marks': 490, 'grade': 'Grade A', 'result': 'PASS'}
...
```

## Learning Objectives

This project helps practice:

* Data processing using Python
* Working with lists of dictionaries
* Aggregation functions
* Conditional logic
* Data enrichment
* Basic reporting and analysis

## Future Enhancements

* Read student data from a CSV file
* Export results to CSV or Excel
* Calculate class rank
* Find highest and lowest scores
* Generate graphical reports using Matplotlib
* Create a menu-driven application

## Author

Mariya Preena

Python Practice Project – Student Result Analysis
