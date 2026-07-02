# UMaT Management System

## About
This project was created as a case study activity for EL 162 — Python and OOP at the University of Mines and Technology (UMaT), Tarkwa. It demonstrates the concept of inheritance in Python by building a simple system to manage different types of people on campus.

## Task Summary
UMaT wants a simple system to manage different types of people on campus. All people share common information such as name and age, but each role has additional responsibilities:
- A **Student** has a student ID and can enroll in a course
- A **Lecturer** has an employee ID and can teach a course

## What the Code Does
- Creates a parent class `Person` with attributes `name` and `age` and a `display_info()` method
- Creates a child class `Student` that inherits from `Person` and adds `student_id` and `enroll_course()`
- Creates a child class `Lecturer` that inherits from `Person` and adds `employee_id` and `teach_course()`
- Uses `super()` to initialize inherited attributes
- Overrides `display_info()` in the `Student` class to include the student ID

## Concepts Demonstrated
- Inheritance
- `super()` method
- Method overriding
- Parent and child classes

## How to Run
1. Open `umat_management_system.ipynb` in PyCharm or Jupyter Notebook
2. Run each cell from top to bottom using `Shift + Enter`
3. Check the output under each cell

## Author
Opoku-Agyen Paynin Akyaa
EL 162 — Python & OOP
University of Mines and Technology (UMaT), Tarkwa
