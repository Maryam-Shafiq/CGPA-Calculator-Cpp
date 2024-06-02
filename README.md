# GPA and CGPA Calculator

This C++ program calculates the GPA (Grade Point Average) and CGPA (Cumulative Grade Point Average) for a student over three semesters. The program assumes that each course carries 3 credit hours.

## Features

- **Grade Calculation**: Converts numerical marks to letter grades based on a predefined scale.
- **GPA Calculation**: Computes the GPA for each course using the letter grade.
- **CGPA Calculation**: Aggregates the GPA of all semesters to calculate the overall CGPA.

## How It Works

1. **Input**: The user inputs marks for 5 courses in each of the three semesters.
2. **Processing**:
    - Marks are converted to grades.
    - GPA for each course is calculated.
    - GPA for each semester is computed.
    - CGPA is determined by averaging the GPAs of all semesters.
3. **Output**: Displays the marks, grades, and GPA for each course and semester, along with the overall CGPA.

## Usage

1. **Clone the Repository**:
    ```bash
    git clone https://github.com/Maryam-Shafiq/CGPA-Calculator-Cpp.git
    cd gpa-cgpa-calculator
    ```

2. **Compile the Program**:
    ```bash
    g++ -o gpa_calculator gpa_calculator.cpp
    ```

3. **Run the Program**:
    ```bash
    ./gpa_calculator
    ```

4. **Enter Marks**: Input the marks for each course in each semester when prompted.

## Example

Enter marks for semester 1 for all 5 courses:
Course 1: 85
Course 2: 90
Course 3: 78
Course 4: 88
Course 5: 92

Enter marks for semester 2 for all 5 courses:
Course 1: 76
Course 2: 83
Course 3: 89
Course 4: 94
Course 5: 87

Enter marks for semester 3 for all 5 courses:
Course 1: 70
Course 2: 75
Course 3: 80
Course 4: 85
Course 5: 90

****************************************************************
Semester-1    Obt Marks    Grade    Course GPA
Course-1        85           B+      3.3
Course-2        90           A-      3.7
Course-3        78           C+      2.3
Course-4        88           B+      3.3
Course-5        92           A-      3.7
Semester-1 GPA    3.26
****************************************************************
Semester-2    Obt Marks    Grade    Course GPA
Course-1        76          C        2.0
Course-2        83          B        3.0
Course-3        89          B+       3.3
Course-4        94          A        4.0
Course-5        87          B+       3.3
Semester-2 GPA    3.12
****************************************************************
Semester-3    Obt Marks    Grade    Course GPA
Course-1        70          C-        1.7
Course-2        75          C         2.0
Course-3        80          B-        2.7
Course-4        85          B+        3.3
Course-5        90          A-        3.7
Semester-3 GPA    2.68
****************************************************************
CGPA = 3.02



## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.


