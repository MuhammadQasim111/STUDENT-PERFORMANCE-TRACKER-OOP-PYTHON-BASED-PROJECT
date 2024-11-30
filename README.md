# Student Performance Tracker

This project is a Python-based **Student Performance Tracker**. It allows teachers to input student names and their scores in three subjects: Math, Science, and English. The tracker calculates individual student averages, determines if they are passing or need improvement, and computes the class average.

---

## Features
- **Add Students**: Add up to three students with their scores.
- **Check Performance**:
  - Calculates each student's average score.
  - Checks if the student is passing (all scores ≥ 40).
- **Class Statistics**:
  - Displays the performance of all students.
  - Calculates and displays the class average.
- **Input Validation**: Ensures scores are between 0 and 100.

---

## Classes and Methods

### `Student`
- **Attributes**:
  - `name`: The student's name.
  - `scores`: A list of integers representing their scores.
- **Methods**:
  - `calculate_average()`: Calculates the student's average score.
  - `is_passing(passing_score=40)`: Checks if all scores are above or equal to the passing threshold.

### `PerformanceTracker`
- **Attributes**:
  - `students`: A dictionary storing student names as keys and `Student` objects as values.
- **Methods**:
  - `add_student(name, scores)`: Adds or updates a student's scores.
  - `calculate_class_average()`: Calculates the class average score.
  - `display_student_performance()`: Displays each student's name, average score, and pass/fail status.

---

## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/MuhammadQasim111/PYTHON-.git
