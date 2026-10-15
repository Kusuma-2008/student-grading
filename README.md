Student Grading System
Description
A Python program that reads student marks from a CSV file and assigns grades.

Grading Rules
- 80–100: A
- 60–less than 80: B
- 40–less than 60: C
- 0–less than 40: F
- Marks outside 0–100 are rejected.

Files
- "grading.py": Calculates grades and reads student records.
- "students.csv": Contains sample student data.
- "test-grading.py": Contains unit tests.

Run the Program
python grading.py

Run Tests
python -m unittest test-grading.py