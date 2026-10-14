🔢 Number Statistics Using Python

📌 Project Overview

Number Statistics is a beginner-friendly Python project developed as part of the AI & ML Internship at Veda Technology.

The main purpose of this project is to analyze a list of numbers and perform basic numerical operations. The program identifies even and odd numbers, separates them into individual lists, and finds the largest and smallest numbers in the given list.

This project helps develop a strong foundation in Python programming and basic data processing.

🎯 Objectives

The objectives of this project are:

- To identify even numbers and odd numbers from a given list.
- To separate even and odd numbers into different lists.
- To find the largest number in the list.
- To find the smallest number in the list.
- To practice Python loops and conditional statements.
- To understand the modulo operator and built-in functions.

🛠️ Technologies Used

- Programming Language: Python
- Development Environment: Jupyter Notebook
- Version Control: Git
- Code Hosting: GitHub

📋 Project Requirements

The program should:

1. Accept or define a list of numerical values.
2. Process each number using a loop.
3. Identify even numbers using the modulo operator ("%").
4. Identify odd numbers.
5. Store even and odd numbers in separate lists.
6. Find the maximum and minimum values.
7. Display the results clearly.

⚙️ How the Program Works

1. Creating a List

A Python list stores multiple numbers in a single variable.

numbers = [12, 7, 24, 9, 3, 18, 5, 30]

2. Creating Empty Lists

Two empty lists are created to store even and odd numbers separately.

even_numbers = []
odd_numbers = []

3. Identifying Even and Odd Numbers

A "for" loop processes every number in the original list.

The modulo operator ("%") calculates the remainder after division.

- If "number % 2 == 0", the number is even.
- Otherwise, the number is odd.

for number in numbers:
    if number % 2 == 0:
        even_numbers.append(number)
    else:
        odd_numbers.append(number)

4. Finding the Largest and Smallest Numbers

Python provides two built-in functions:

- "max(numbers)" returns the largest number.
- "min(numbers)" returns the smallest number.

largest = max(numbers)
smallest = min(numbers)

5. Displaying the Results

The "print()" function displays the lists and statistical results.

💻 Complete Python Code

numbers = [12, 7, 24, 9, 3, 18, 5, 30]

even_numbers = []
odd_numbers = []

for number in numbers:
    if number % 2 == 0:
        even_numbers.append(number)
    else:
        odd_numbers.append(number)

largest = max(numbers)
smallest = min(numbers)

print("Numbers:", numbers)
print("Even numbers:", even_numbers)
print("Odd numbers:", odd_numbers)
print("Largest number:", largest)
print("Smallest number:", smallest)

📤 Sample Output

Numbers: [12, 7, 24, 9, 3, 18, 5, 30]
Even numbers: [12, 24, 18, 30]
Odd numbers: [7, 9, 3, 5]
Largest number: 30
Smallest number: 3

🧠 Python Concepts Learned

Concept| Description
Lists| Store multiple numbers in one variable
"for" loop| Process each number in the list
"if-else"| Apply conditions to classify numbers
Modulo ("%")| Check the remainder after division
"append()"| Add an item to a list
"max()"| Find the largest value
"min()"| Find the smallest value
"print()"| Display the results

🧪 Test Cases

Input| Expected Result
"[2, 5, 8, 9]"| Even: "[2, 8]", Odd: "[5, 9]"
"[10, 20, 30]"| Even: "[10, 20, 30]", Odd: "[]"
"[1, 3, 5]"| Even: "[]", Odd: "[1, 3, 5]"
"[-4, -3, 0, 7]"| Even: "[-4, 0]", Odd: "[-3, 7]"

Note: The input list must contain at least one number when using "max()" and "min()".

📈 Applications

This project demonstrates basic techniques that are useful in:

- Numerical data processing
- Basic statistical analysis
- Data cleaning and classification
- Learning the fundamentals of data science
- Preparing for more advanced Python and machine learning projects

🚀 How to Run the Project

1. Install Python or open Jupyter Notebook.
2. Create a new Python notebook or file.
3. Copy the program into a code cell or Python file.
4. Run the program.
5. Observe the even numbers, odd numbers, largest number, and smallest number.

📂 Project Structure

Number-Statistics/
│
├── Number_Statistics.ipynb
└── README.md

"Number_Statistics.ipynb" contains the Python program, and "README.md" explains the project.

🎓 Internship Information

- Organization: Veda Technology
- Track: AI & ML
- Level: 1
- Task: Day 5 – Number Statistics

🏁 Conclusion

The Number Statistics project successfully demonstrates how Python can be used to process a list of numbers. It provides practical experience with loops, conditional statements, lists, the modulo operator, and built-in functions.

These concepts form a foundation for further learning in Python, data science, and machine learning.

---

Project: Number Statistics
Language: Python
