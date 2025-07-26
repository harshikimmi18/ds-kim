# 💧 Rainwater Harvesting Advisor using ANN

This project uses an **Artificial Neural Network (ANN)** model to predict optimal rainwater harvesting capacity and recommend harvesting methods based on environmental parameters.

---

## 📌 Project Overview

This model serves as an advisor tool to optimize rainwater collection and storage based on:
- Rainfall
- Roof Area
- Water Usage
- Soil Type
- Population Density

The goal is to use machine learning (ANN) to recommend suitable harvesting plans for a region, assisting in sustainable water management.

---

## 🧠 Technologies Used

- Python 🐍
- Google Colab
- NumPy
- Pandas
- Scikit-learn
- Keras (TensorFlow backend)
- Matplotlib (for visualization)

---

## 📂 Dataset

A **synthetic dataset** was created with realistic environmental conditions and expected harvesting outcomes.  
Key features:
- `rainfall_mm`  
- `roof_area_m2`  
- `daily_usage_liters`  
- `soil_type` *(numerically encoded)*  
- `population_density`

Target variable:
- `advised_storage_capacity_liters`

---

## 🏗️ Model Architecture

- **Input Layer**: 5 neurons (one for each input parameter)
- **Hidden Layers**: 2 Dense layers with ReLU activation
- **Output Layer**: 1 neuron (regression output)
- **Loss Function**: Mean Squared Error (MSE)
- **Optimizer**: Adam

---

## ⚙️ How to Run

1. Clone this repository or open in Google Colab
2. Install dependencies (if running locally)
3. Run the notebook: `rainwater_harvesting_ann.ipynb`
4. Train the model on the synthetic dataset
5. Evaluate performance using test data
6. Save or load the model using `.h5` files

---

## 📊 Results

- Achieved low Mean Absolute Error (MAE) on test data.
- Model generalized well on unseen examples.
- Visualizations show close correlation between predicted and actual capacities.

---

## ✅ Future Improvements

- Replace synthetic dataset with real-world rainfall + demographic data
- Convert into a web dashboard using Streamlit
- Include fuzzy logic or reinforcement learning for adaptive suggestions

---

## 🧠 Author

Harshitha  
Data Science Enthusiast | UI Developer  
*Intern at Convey Tech Labs & Internz Learn*

---

## 📄 License

This project is open source and free to use under the MIT License.



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




# 🗓️ Day 4: Sets & Dictionaries in Python

## ✅ Topics Covered:
- Python `set()` operations:
  - Adding and updating elements
  - Set union, intersection, difference
  - Checking subset/superset
- Python `dict()` operations:
  - Creating, updating key-value pairs
  - Looping through keys, values, and items
  - Dictionary methods like `.get()`, `.items()`, `.values()`, `.keys()`
  - Finding max value and key with `max()` and `key=dict.get`

## 🧠 Concepts Practiced:
1. Using `.add()` and `.update()` in sets
2. Subset checking using `issubset()` instead of `in`
3. Looping through a dictionary with `.items()`
4. Checking if a key exists in a dictionary
5. Adding new key-value pairs conditionally
6. Using `max()` to find the highest value in a dictionary
7. Printing key with the highest value using `key=dict.get`

## 📂 Tasks Completed:
- ✅ Solved 10 practice problems on sets and dictionaries
- ✅ Debugged and fixed logical and syntax errors
- ✅ Understood how to extract values and keys in smart ways

