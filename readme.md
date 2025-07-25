📘 Day 1 – Python Basics
✅ Topics Covered:
What is Python?

Introduction to Python and its uses in data science, web development, automation, etc.

First Python Program

Wrote and executed: print("Hello, World!")

Python Character Set

Alphabets, digits, special symbols, whitespace characters used in Python

Variables & Memory

How variables are declared and how Python handles memory allocation

Rules for Identifiers

Valid naming conventions for variables and functions

Data Types

int, float, str, bool, complex, etc.

Keywords

Reserved words like if, else, while, def, True, False, etc.

Operators

Arithmetic (+, -, *, /, %, **, //)

Assignment (=, +=, -=, etc.)

Comparison, Logical, Bitwise, Identity, Membership

Type Conversion & Type Casting

int(), float(), str() for converting types

Taking User Input

Using input() and casting to appropriate types

Basic Practice Problems

Sum of two numbers

Area of a circle

Voting eligibility check

Type checker using type() function

🧠 Practice Focus:
Understanding how Python handles variables and memory

Writing simple logic using if-else

Using input() and print() effectively

Learning to debug syntax issues and indentation




📅 Day 2: Python Practice – Strings & Conditional Statements
✅ Topics Covered:
Python Strings

Indexing and Slicing

String Built-in Functions (len(), .lower(), .upper(), .find(), etc.)

Conditional Statements (if, else, elif)

📘 Concepts Learned:
Accessing characters using positive & negative indexing

Extracting substrings using slicing with different steps (string[start:end:step])

Using string functions for formatting and analysis

Writing conditional logic based on input/conditions

💻 Practice Problems:
Reverse a string using slicing

Count vowels in a string

Check if a string is a palindrome

Password validator (length, special char, upper/lower)

Anagram checker

Remove duplicates from a string

Custom string slicer with index validation

📎 Resources Used:
Practice notebook: Day2/practice_problems.ipynb

IDE: VS Code + Python 3.x

Reference: W3Schools – Python Strings
## 📅 Day 3 - Python Practice Log

### ✅ Topics Covered:
- Lists
  - Creation, Indexing, Slicing
  - Common methods: `append()`, `insert()`, `remove()`, `pop()`, etc.
- Tuples
  - Conversion between tuple and list
  - Accessing and updating values via conversion

### 🧠 Practice Questions Solved:
1. Add an element at the 2nd position in a list.
2. Check if an item exists in a list and print confirmation.
3. Convert a tuple to list → append new element → convert back to tuple.
4. Merge two lists and sort them.
5. Remove duplicates from a list without using `set()`.
6. Find the largest and smallest numbers in a list without `max()` or `min()`.

### 💡 Key Learnings:
- Difference between mutable (list) and immutable (tuple) types.
- How to manipulate tuple content via list conversion.
- Handling list operations and implementing logic without built-in functions.

### 🔁 Commands/Examples Used:
```python
# Add element at index 1
my_list.insert(1, "new_value")

# Convert tuple to list, modify, and back
my_tuple = (10, 20)
temp_list = list(my_tuple)
temp_list.append(30)
my_tuple = tuple(temp_list)

