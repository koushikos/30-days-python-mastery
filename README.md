# 🚀 30 Days Python Mastery - Complete Learning Roadmap

> A Comprehensive 30-Day Program to Take You from Python Beginner to Strong Intermediate/Advanced Level

![Python](https://img.shields.io/badge/Python-30--Day%20Mastery-blue?style=for-the-badge&logo=python)
![Beginner to Advanced](https://img.shields.io/badge-Level-Beginner%20to%20Advanced-green?style=for-the-badge&logo=rocket)
![Hands-On Projects](https://img.shields.io/badge-Projects-5--Major%20Projects-red?style=for-the-badge&logo=code)
 
---  

## 📋 Table of Contents

1. [Introduction & How to Use This Program](#introduction--how-to-use-this-program)
2. [Prerequisites & Setup](#prerequisites--setup)
3. [Week-by-Week Overview](#week-by-week-overview)
4. [Daily Curriculum (Day 1-30)](#daily-curriculum-day-1-30)
   - [Week 1: Python Fundamentals](#week-1-python-fundamentals-days-1-7)
   - [Week 2: Data Structures & Control Flow](#week-2-data-structures--control-flow-days-8-14)
   - [Week 3: Functions & Advanced Concepts](#week-3-functions--advanced-concepts-days-15-21)
   - [Week 4: OOP, File Handling & Real-World Apps](#week-4-oop-file-handling--real-world-apps-days-22-30)
5. [Weekly Mini-Projects](#weekly-mini-projects)
6. [Final Capstone Project](#final-capstone-project)
7. [Interview Questions & Answers](#interview-questions--answers)
8. [Common Mistakes to Avoid](#common-mistakes-to-avoid)
9. [Python Best Practices](#python-best-practices)
10. [GitHub Project Ideas](#github-project-ideas)
11. [Practice Datasets & Examples](#practice-datasets--examples)
12. [Resources & Next Steps](#resources--next-steps)

---

## 🌟 Introduction & How to Use This Program

### What You'll Achieve

By completing this 30-day Python mastery program, you will:

- ✅ Master Python fundamentals and syntax
- ✅ Understand all major data structures (lists, tuples, sets, dictionaries)
- ✅ Write efficient, clean, and Pythonic code
- ✅ Implement object-oriented programming concepts
- ✅ Handle files, errors, and external APIs
- ✅ Build real-world projects from scratch
- ✅ Be prepared for Python interviews and certifications
- ✅ Have a strong foundation for web development, data science, or automation

### How to Use This Roadmap

Each day follows this consistent structure:

```
Day X: [Topic Name]

📚 Topics to Learn:
- [Concept 1]
- [Concept 2]

💡 Concept Explanations:
[Detailed explanations with examples]

🔧 Syntax Examples:
```python
# Code examples here
```

💻 Practice Exercises:
[Exercises to practice the concepts]

🎯 Small Task/Challenge:
[A mini-project or challenge for the day]

🎯 Expected Outcome:
[What you should be able to do after completing]
```

### Learning Tips

1. **Code Every Day**: Consistency is key - code at least 1-2 hours daily
2. **Hands-On First**: Always practice code before reading deeper theory
3. **Take Notes**: Document your findings in a coding journal
4. **Build Projects**: Apply concepts by building small projects
5. **Teach Others**: Explain concepts to reinforce your understanding
6. **Don't Skip**: Even if a topic seems easy, complete all exercises
7. **Review & Revise**: At the end of each week, review what you've learned

---

## 💻 Prerequisites & Setup

### Hardware Requirements

| Item | Minimum | Recommended |
|------|---------|-------------|
| Computer | 4GB RAM, 10GB storage | 8GB+ RAM, SSD |
| Internet | Basic connection | Stable broadband |
| Time Commitment | 1-2 hours/day | 2-4 hours/day |

### Software Requirements

- **Operating System**: Windows, macOS, or Linux
- **Python Version**: Python 3.8+ (Download from python.org)
- **Code Editor**: VS Code (recommended) or PyCharm
- **Terminal**: Command Prompt (Windows) / Terminal (Mac/Linux)

### Installation Steps

```
bash
# 1. Download Python from https://www.python.org/downloads/
# 2. Verify installation
python --version  # Should show Python 3.x.x

# 3. Verify pip (package manager)
pip --version

# 4. Install a code editor
# Download VS Code: https://code.visualstudio.com/

# 5. Create a project folder
mkdir python-mastery
cd python-mastery
```

### Virtual Environment Setup (Day 20)

```
bash
# Create a virtual environment
python -m venv myenv

# Activate on Windows
myenv\Scripts\activate

# Activate on Mac/Linux
source myenv/bin/activate

# Install packages
pip install requests numpy pandas

# Deactivate when done
deactivate
```

---

## 📅 Week-by-Week Overview

| Week | Theme | Key Topics | Mini-Project |
|------|-------|------------|--------------|
| Week 1 | Python Fundamentals | Variables, Data Types, Operators, Strings | Calculator |
| Week 2 | Data Structures & Control Flow | Lists, Tuples, Sets, Dictionaries, If/Else, Loops | Todo List App |
| Week 3 | Functions & Advanced Concepts | Functions, List Comprehensions, Lambdas, Error Handling, Modules | Weather App |
| Week 4 | OOP, File Handling & Real-World Apps | Classes, Inheritance, File I/O, APIs, Testing | Portfolio Website |

---

# 📖 Daily Curriculum (Day 1-30)

---

# PHASE 1: PYTHON FUNDAMENTALS (Days 1-7)

---

## Day 1: Introduction to Python & Setting Up Environment

### Topics to Learn

- What is Python and why learn it
- Python vs other programming languages
- Installing Python and setting up IDE
- Writing your first Python program
- Understanding Python syntax and indentation

### Concept Explanations

**What is Python?**

Python is a high-level, interpreted programming language known for its simplicity and readability. It was created by Guido van Rossum and first released in 1991.

**Why Learn Python?**

1. **Versatile**: Used in web development, data science, AI, automation, and more
2. **Easy to Learn**: Simple syntax similar to English
3. **High Demand**: One of the most sought-after programming skills
4. **Large Community**: Extensive libraries and resources
5. **Career Opportunities**: High-paying jobs in multiple domains

**Python Characteristics:**

```
python
# Python is interpreted - runs line by line
# Python is dynamically typed - no need to declare variable types
# Python is object-oriented - everything is an object
# Python has extensive libraries - pip install what you need
```

### Syntax Examples

```
python
# Hello World Program
print("Hello, World!")

# Variables and Data Types
name = "John"           # String
age = 25                # Integer
height = 5.9            # Float
is_student = True       # Boolean

# Multiple assignments
x, y, z = 1, 2, 3

# Type checking
print(type(name))      # <class 'str'>
print(type(age))        # <class 'int'>
print(type(height))     # <class 'float'>
print(type(is_student)) # <class 'bool'>

# Type conversion
age_as_string = str(age)
num = int("42")
decimal = float("3.14")
```

### Practice Exercises

1. ✅ Write a program that prints your name, age, and favorite color
2. ✅ Create variables for a book (title, author, year, price) and print them
3. ✅ Convert temperature from Celsius to Fahrenheit
4. ✅ Calculate the area of a rectangle (length × width)
5. ✅ Swap two variables without using a temporary variable

### Small Task/Challenge

Create a personal introduction program that asks for user input and displays a formatted introduction:

```
python
# Expected Output:
# Enter your name: Alice
# Enter your age: 25
# Enter your city: New York
# Hello! My name is Alice. I am 25 years old and I live in New York.
```

### Expected Outcome

- Understand what Python is and its applications
- Have Python installed and running on your machine
- Write simple Python programs with variables
- Understand basic data types (strings, integers, floats, booleans)

---

## Day 2: Variables, Data Types & Basic Operators

### Topics to Learn

- Variable naming conventions
- Primitive data types in depth
- Arithmetic operators
- Assignment operators
- Comments in Python

### Concept Explanations

**Variable Naming Rules:**

```
python
# ✅ Valid variable names
name = "John"
age2 = 30
is_valid = True
total_price = 99.99
_name = "private"  # Convention for private variables

# ❌ Invalid variable names
# 2name = "John"   # Cannot start with number
# my-name = "John" # Cannot use hyphens
# my name = "John" # Cannot use spaces
# class = "Math"    # Cannot use reserved keywords
```

**Data Types in Python:**

```
python
# Integer - Whole numbers
count = 100
negative = -50
large_num = 1_000_000  # Underscores for readability

# Float - Decimal numbers
price = 19.99
scientific = 3.14e-10  # Scientific notation

# String - Text
greeting = "Hello"
message = 'World'
multiline = """This is a
multi-line string"""

# Boolean - True/False
is_active = True
has_permission = False

# None - Represents absence of value
result = None
```

**Arithmetic Operators:**

```
python
a, b = 10, 3

print(a + b)   # Addition: 13
print(a - b)   # Subtraction: 7
print(a * b)   # Multiplication: 30
print(a / b)   # Division: 3.333...
print(a // b)  # Floor Division: 3
print(a % b)   # Modulus: 1
print(a ** b)  # Exponent: 1000
```

**Assignment Operators:**

```
python
x = 10
x += 5        # x = x + 5 → x = 15
x -= 3        # x = x - 3 → x = 12
x *= 2        # x = x * 2 → x = 24
x /= 4        # x = x / 4 → x = 6.0
x //= 2       # x = x // 2 → x = 3.0
x %= 2        # x = x % 2 → x = 1.0
```

### Practice Exercises

1. ✅ Create a program to calculate the area of a circle (πr²)
2. ✅ Calculate compound interest: A = P(1 + r/n)^(nt)
3. ✅ Convert miles to kilometers (1 mile = 1.60934 km)
4. ✅ Calculate the perimeter and area of a rectangle
5. ✅ Create a program that calculates BMI (weight/height²)

### Small Task/Challenge

Build a simple calculator that performs basic arithmetic operations:

```
python
# Enter first number: 10
# Enter operator (+, -, *, /): *
# Enter second number: 5
# Result: 10 * 5 = 50
```

### Expected Outcome

- Master variable creation and naming conventions
- Understand all primitive data types
- Use arithmetic and assignment operators confidently
- Write clean code with appropriate comments

---

## Day 3: Strings - Deep Dive

### Topics to Learn

- String creation and indexing
- String slicing
- String methods
- String formatting
- f-strings

### Concept Explanations

**String Indexing & Slicing:**

```
python
text = "Python Programming"

# Indexing (starts from 0)
print(text[0])      # P
print(text[7])      # P
print(text[-1])     # g (last character)
print(text[-2])     # n (second to last)

# Slicing [start:end:step]
print(text[0:6])    # Python (characters 0-5)
print(text[7:])     # Programming (from index 7 to end)
print(text[:6])      # Python (start to index 5)
print(text[::2])     # Pto rgamn (every other character)
print(text[::-1])    # gnimmargorP nohtyP (reversed)
```

**String Methods:**

```
python
text = "  Hello, Python World!  "

# Case conversion
print(text.upper())           #   HELLO, PYTHON WORLD!
print(text.lower())           #   hello, python world!
print(text.title())           #   Hello, Python World!
print(text.capitalize())      #   hello, python world!

# Search and replace
print(text.find("Python"))    # 9 (index where found)
print(text.count("o"))        # 3
print(text.replace("Python", "Programming"))  # "  Hello, Programming World!  "

# Whitespace handling
print(text.strip())           # "Hello, Python World!"
print(text.lstrip())          # "Hello, Python World!  "
print(text.rstrip())          # "  Hello, Python World!"

# Split and join
words = "apple,banana,cherry"
print(words.split(","))       # ['apple', 'banana', 'cherry']
parts = ["Hello", "World"]
print(" ".join(parts))       # "Hello World"

# Check methods
print("Hello".isalpha())     # True (all letters)
print("Hello123".isalnum())  # True (letters and numbers)
print("123".isdigit())       # True (all digits)
print("hello".islower())     # True
print("HELLO".isupper())    # True
```

**String Formatting:**

```
python
# f-strings (Python 3.6+) - RECOMMENDED
name = "Alice"
age = 25
print(f"My name is {name} and I am {age} years old")

# Format with expressions
price = 19.99
print(f"Price: ${price:.2f}")  # Price: $19.99
print(f"Age in 10 years: {age + 10}")  # 35

# .format() method
template = "Hello, {0}! You have {1} messages."
print(template.format("Alice", 3))

# Old-style % formatting
print("Hello, %s!" % "World")
```

### Practice Exercises

1. ✅ Reverse a given string
2. ✅ Count vowels in a string
3. ✅ Check if a string is a palindrome
4. ✅ Convert snake_case to camelCase
5. ✅ Extract the domain from an email address

### Small Task/Challenge

Create a word counter that counts words, characters, and vowels in a sentence:

```
python
# Enter a sentence: Python is amazing
# Word count: 3
# Character count: 17
# Vowel count: 5 (o,i,a,i)
```

### Expected Outcome

- Master string indexing and slicing
- Use all common string methods fluently
- Format strings using f-strings
- Manipulate strings for common use cases

---

## Day 4: Boolean, Comparison & Logical Operators

### Topics to Learn

- Boolean data type
- Comparison operators
- Logical operators
- Truthy and Falsy values
- Operator precedence

### Concept Explanations

**Comparison Operators:**

```
python
a, b = 10, 20

# Equality
print(a == b)   # False
print(a == 10)  # True

# Not equal
print(a != b)   # True
print(a != 10)  # False

# Greater than / Less than
print(a > b)    # False
print(a < b)    # True
print(a >= 10)  # True
print(b <= 20)  # True
```

**Logical Operators:**

```
python
x, y = 5, 10

# and - True if both are true
print(x > 0 and y > 0)   # True
print(x > 10 and y > 0)  # False

# or - True if at least one is true
print(x > 0 or y > 0)    # True
print(x > 10 or y > 0)   # True
print(x > 10 or y > 20)  # False

# not - Inverts the boolean
print(not True)   # False
print(not False) # True
print(not (x > 0))  # False
```

**Truthy and Falsy Values:**

```
python
# Falsy values (evaluate to False)
bool(False)      # False
bool(None)       # False
bool(0)          # False
bool("")         # False (empty string)
bool([])         # False (empty list)
bool({})         # False (empty dict)
bool(())         # False (empty tuple)

# Truthy values (evaluate to True)
bool(True)       # True
bool(1)          # True
bool("Hello")    # True
bool([1, 2, 3])  # True
bool({"key": "value"})  # True

# Practical example
name = input("Enter name: ") or "Guest"
print(f"Hello, {name}")
```

**Operator Precedence:**

```
python
# Highest to lowest:
# 1. Parentheses: ()
# 2. Exponentiation: **
# 3. Unary: +x, -x, not x
# 4. Multiplication/Division: *, /, //, %
# 5. Addition/Subtraction: +, -
# 6. Comparisons: ==, !=, <, >, <=, >=
# 7. Boolean NOT: not
# 8. Boolean AND: and
# 9. Boolean OR: or

# Example
result = 2 + 3 * 4  # 14 (not 20)
result = (2 + 3) * 4  # 20
```

### Practice Exercises

1. ✅ Write a program to check if a number is positive, negative, or zero
2. ✅ Check if a year is a leap year
3. ✅ Validate a password (at least 8 chars, has uppercase, lowercase, and number)
4. ✅ Check if three sides form a valid triangle
5. ✅ Determine the largest of three numbers

### Small Task/Challenge

Create a login system that validates username and password:

```
python
# Valid credentials: admin / password123
# Enter username: admin
# Enter password: password123
# Login successful!
# OR
# Login failed! Invalid credentials.
```

### Expected Outcome

- Use comparison and logical operators effectively
- Understand truthy/falsy values
- Write clean conditional expressions
- Apply operator precedence correctly

---

## Day 5: Conditional Statements (If-Elif-Else)

### Topics to Learn

- if statement
- elif statement
- else clause
- Nested conditionals
- Ternary operator

### Concept Explanations

**Basic If Statement:**

```
python
age = 18

if age >= 18:
    print("You are an adult")

# With else
if age >= 18:
    print("Adult")
else:
    print("Minor")

# With elif
score = 85

if score >= 90:
    grade = "A"
elif score >= 80:
    grade = "B"
elif score >= 70:
    grade = "C"
elif score >= 60:
    grade = "D"
else:
    grade = "F"

print(f"Your grade is: {grade}")  # B
```

**Nested Conditionals:**

```
python
age = 25
has_license = True

if age >= 18:
    if has_license:
        print("You can drive!")
    else:
        print("You need to get a license first")
else:
    print("You must be 18 or older to drive")

# Cleaner version with and
if age >= 18 and has_license:
    print("You can drive!")
elif age < 18:
    print("You must be 18 or older")
else:
    print("You need a license")
```

**Ternary Operator (Conditional Expression):**

```
python
# Shortened if-else in one line
age = 20
status = "Adult" if age >= 18 else "Minor"
print(status)  # Adult

# Can also be used in expressions
x = 10
print("Even" if x % 2 == 0 else "Odd")  # Even
```

### Practice Exercises

1. ✅ Write a program to find the largest of three numbers
2. ✅ Create a grade calculator with A, B, C, D, F grades
3. ✅ Check if a number is divisible by 3, 5, or both
4. ✅ Implement a simple calculator with if-elif-else
5. ✅ Create a traffic light simulation (Red/Yellow/Green)

### Small Task/Challenge

Build a BMI calculator with health categorization:

```
python
# Enter weight (kg): 70
# Enter height (m): 1.75
# Your BMI is: 22.86
# Category: Normal weight

# BMI Categories:
# Underweight: < 18.5
# Normal: 18.5 - 24.9
# Overweight: 25 - 29.9
# Obese: >= 30
```

### Expected Outcome

- Write clear conditional statements
- Handle multiple conditions with elif
- Use nested conditionals appropriately
- Apply ternary operator for simple conditions

---

## Day 6: Lists - Introduction & Basic Operations

### Topics to Learn

- List creation
- Indexing and slicing lists
- List methods
- Modifying lists
- List comprehension basics

### Concept Explanations

**Creating Lists:**

```
python
# Empty list
empty = []
empty = list()

# With initial values
fruits = ["apple", "banana", "cherry"]
numbers = [1, 2, 3, 4, 5]
mixed = [1, "hello", 3.14, True]

# Using list() constructor
chars = list("hello")  # ['h', 'e', 'l', 'l', 'o']

# Range-based list
numbers = list(range(1, 11))  # [1, 2, 3, 4, 5, 6, 7, 8, 9, 10]
```

**Accessing List Elements:**

```
python
fruits = ["apple", "banana", "cherry", "date", "elderberry"]

# Positive indexing
print(fruits[0])   # apple
print(fruits[2])   # cherry

# Negative indexing
print(fruits[-1])  # elderberry
print(fruits[-2]) # date

# Slicing
print(fruits[1:4])    # ['banana', 'cherry', 'date']
print(fruits[:3])     # ['apple', 'banana', 'cherry']
print(fruits[2:])     # ['cherry', 'date', 'elderberry']
print(fruits[::2])    # ['apple', 'cherry', 'elderberry']
print(fruits[::-1])   # reversed
```

**List Methods:**

```
python
numbers = [1, 2, 3]

# Adding elements
numbers.append(4)      # [1, 2, 3, 4] - add to end
numbers.insert(0, 0)   # [0, 1, 2, 3, 4] - at specific index
numbers.extend([5, 6]) # [0, 1, 2, 3, 4, 5, 6] - add multiple

# Removing elements
numbers.pop()          # Removes last element, returns it
numbers.pop(0)         # Removes at index
numbers.remove(3)      # Removes first occurrence of value
numbers.clear()        # Removes all elements

# Finding elements
fruits = ["apple", "banana", "cherry"]
print(fruits.index("banana"))  # 1
print(fruits.count("apple"))   # 1

# Sorting
numbers = [3, 1, 4, 1, 5]
numbers.sort()        # Sorts in place
print(sorted(numbers))  # Returns new sorted list
numbers.reverse()     # Reverses in place
```

### Practice Exercises

1. ✅ Create a list of your 5 favorite movies
2. ✅ Add a new movie to the list
3. ✅ Remove the third movie from the list
4. ✅ Sort the list alphabetically
5. ✅ Find the index of a specific movie

### Small Task/Challenge

Build a simple to-do list manager:

```
python
# Options: 1. Add task 2. Remove task 3. View tasks 4. Exit
# Enter choice: 1
# Enter task: Learn Python
# Task added!

# Enter choice: 3
# Your tasks:
# 1. Learn Python

# Enter choice: 2
# Enter task number to remove: 1
# Task removed!
```

### Expected Outcome

- Create and manipulate lists
- Access elements using indexing and slicing
- Use all common list methods
- Understand list mutability

---

## Day 7: Week 1 Review & Mini-Project

### Weekly Milestones

✅ **Week 1 Completed:**

- [ ] Understanding of Python basics and setup
- [ ] Variables, data types, and operators
- [ ] String manipulation
- [ ] Conditional statements
- [ ] List basics

### Practical Exercise

**Comprehensive Review Exercise:**

1. Create a program that calculates the total cost of items in a shopping cart
2. Apply discounts based on total amount
3. Display itemized receipt

### Commands/Concepts Review

```
python
# Variables and types
name = "John"
age = 25

# Strings
text = "Hello World"
text.upper()
text[0:5]

# Conditionals
if age >= 18:
    print("Adult")

# Lists
fruits = ["apple", "banana"]
fruits.append("cherry")
```

### Expected Outcome

- Confirmed understanding of Week 1 topics
- Ready to proceed to Week 2
- Complete first mini-project

---

# PHASE 2: DATA STRUCTURES & CONTROL FLOW (Days 8-14)

---

## Day 8: Tuples & Sets

### Topics to Learn

- Tuple creation and indexing
- Tuple methods
- Set creation and operations
- When to use tuples vs lists vs sets

### Concept Explanations

**Tuples:**

```
python
# Creating tuples
empty_tuple = ()
single_tuple = (1,)  # Comma needed for single element
coordinates = (10, 20, 30)
mixed = (1, "hello", 3.14, True)

# Tuple unpacking
x, y, z = coordinates
print(x, y, z)  # 10 20 30

# Multiple assignment (automatic tuple)
a, b = 1, 2  # a=1, b=2

# Tuple methods
point = (1, 2, 3, 2, 1)
print(point.count(2))  # 2
print(point.index(3))  # 2

# Tuple indexing
print(coordinates[0])  # 10
print(coordinates[-1])   # 30
```

**Sets:**

```
python
# Creating sets
empty_set = set()
fruits = {"apple", "banana", "cherry"}

# Set operations
fruits.add("date")           # Add element
fruits.remove("banana")      # Remove (raises error if not found)
fruits.discard("banana")     # Remove (doesn't raise error)
fruits.pop()                 # Remove random element
fruits.clear()               # Remove all

# Set operations
set1 = {1, 2, 3, 4}
set2 = {3, 4, 5, 6}

print(set1.union(set2))           # {1, 2, 3, 4, 5, 6}
print(set1.intersection(set2))    # {3, 4}
print(set1.difference(set2))      # {1, 2}
print(set1.symmetric_difference(set2))  # {1, 2, 5, 6}

# Check membership
print(1 in set1)  # True

# Remove duplicates from list
numbers = [1, 2, 2, 3, 3, 3]
unique = list(set(numbers))  # [1, 2, 3]
```

### Practice Exercises

1. ✅ Create a tuple with your name, age, and city
2. ✅ Unpack a coordinate tuple into x, y, z variables
3. ✅ Create a set of fruits and add/remove items
4. ✅ Find common elements between two sets
5. ✅ Remove duplicates from a list using sets

### Small Task/Challenge

Create a program that manages a student attendance system:

```
python
# Monday: Alice, Bob, Charlie
# Tuesday: Bob, Charlie, David
# Wednesday: Alice, David, Eve

# Find:
# Students present all three days
# Students present on any day
# Students present on only one day
```

### Expected Outcome

- Understand when to use tuples vs lists vs sets
- Perform set operations (union, intersection, difference)
- Apply tuples for fixed data collections

---

## Day 9: Dictionaries

### Topics to Learn

- Dictionary creation
- Accessing and modifying values
- Dictionary methods
- Iterating over dictionaries
- Nested dictionaries

### Concept Explanations

**Creating Dictionaries:**

```
python
# Empty dictionary
empty = {}
empty = dict()

# With key-value pairs
person = {
    "name": "John",
    "age": 30,
    "city": "New York"
}

# Using dict() constructor
person = dict(name="John", age=30, city="New York")

# Accessing values
print(person["name"])      # John
print(person.get("age"))   # 30
print(person.get("country", "USA"))  # USA (default if not found)

# Adding/modifying
person["email"] = "john@email.com"  # Add new
person["age"] = 31                    # Modify existing
```

**Dictionary Methods:**

```
python
student = {"name": "Alice", "age": 20, "grade": "A"}

# Get all keys, values, items
print(student.keys())    # dict_keys(['name', 'age', 'grade'])
print(student.values())  # dict_values(['Alice', 20, 'A'])
print(student.items())   # dict_items([('name', 'Alice'), ...])

# Update dictionary
student.update({"age": 21, "major": "Computer Science"})
print(student)  # {'name': 'Alice', 'age': 21, 'grade': 'A', 'major': 'CS'}

# Remove items
removed = student.pop("grade")  # Returns removed value
print(removed)  # A

# Other methods
print(len(student))  # 3
student.clear()     # Remove all items
```

**Iterating Over Dictionaries:**

```
python
person = {"name": "John", "age": 30, "city": "NYC"}

# Iterate over keys
for key in person:
    print(key)

# Iterate over values
for value in person.values():
    print(value)

# Iterate over key-value pairs
for key, value in person.items():
    print(f"{key}: {value}")

# Dictionary comprehension
squares = {x: x**2 for x in range(1, 6)}
# {1: 1, 2: 4, 3: 9, 4: 16, 5: 25}
```

### Practice Exercises

1. ✅ Create a dictionary of 5 countries and their capitals
2. ✅ Add a new country-capital pair
3. ✅ Update a capital city
4. ✅ Print all countries with their capitals
5. ✅ Find the most common letter in a string using a dictionary

### Small Task/Challenge

Build a word frequency counter:

```
python
# Enter text: Python is amazing and Python is powerful
# Word frequencies:
# python: 2
# is: 2
# amazing: 1
# and: 1
# powerful: 1
```

### Expected Outcome

- Create and manipulate dictionaries
- Use all dictionary methods
- Iterate over dictionaries efficiently
- Build dictionary-based solutions

---

## Day 10: For Loops & While Loops

### Topics to Learn

- For loop syntax
- Range function
- While loop syntax
- Loop control (break, continue, pass)
- Nested loops

### Concept Explanations

**For Loops:**

```
python
# Basic for loop
fruits = ["apple", "banana", "cherry"]
for fruit in fruits:
    print(fruit)

# Using range()
for i in range(5):
    print(i)  # 0, 1, 2, 3, 4

for i in range(1, 6):
    print(i)  # 1, 2, 3, 4, 5

for i in range(0, 10, 2):
    print(i)  # 0, 2, 4, 6, 8

# Loop through string
for char in "Python":
    print(char)

# Loop through dictionary
for key, value in {"a": 1, "b": 2}.items():
    print(f"{key}: {value}")
```

**While Loops:**

```
python
# Basic while loop
count = 0
while count < 5:
    print(count)
    count += 1

# While with break
while True:
    user_input = input("Enter 'quit' to exit: ")
    if user_input == "quit":
        break
    print(f"You entered: {user_input}")

# While with continue
i = 0
while i < 10:
    i += 1
    if i % 2 == 0:
        continue  # Skip even numbers
    print(i)  # 1, 3, 5, 7, 9
```

**Loop Control Statements:**

```
python
# break - Exit loop completely
for i in range(10):
    if i == 5:
        break
    print(i)  # 0, 1, 2, 3, 4

# continue - Skip current iteration
for i in range(5):
    if i == 2:
        continue
    print(i)  # 0, 1, 3, 4

# pass - Do nothing (placeholder)
for i in range(5):
    if i == 2:
        pass  # TODO: Add code later
    print(i)
```

**Nested Loops:**

```
python
# Multiplication table
for i in range(1, 4):
    for j in range(1, 4):
        print(f"{i} x {j} = {i*j}", end="\t")
    print()  # New line after each row
```

### Practice Exercises

1. ✅ Print all even numbers from 1 to 20
2. ✅ Calculate the factorial of a number
3. ✅ Find the sum of digits in a number
4. ✅ Print a pyramid pattern
5. ✅ Find the first 10 Fibonacci numbers

### Small Task/Challenge

Create a number guessing game:

```
python
# Random number: 7
# Guess a number (1-100): 50
# Too high! Try again.
# Guess a number: 25
# Too low! Try again.
# Guess a number: 7
# Correct! You guessed it in 3 attempts.
```

### Expected Outcome

- Write for loops with range()
- Use while loops effectively
- Apply break, continue, and pass
- Handle nested loop scenarios

---

## Day 11: List Comprehensions

### Topics to Learn

- Basic list comprehension
- Conditionals in list comprehension
- Nested list comprehension
- Dictionary comprehension
- Generator expressions

### Concept Explanations

**Basic List Comprehension:**

```
python
# Traditional way
squares = []
for i in range(1, 6):
    squares.append(i**2)

# List comprehension way
squares = [i**2 for i in range(1, 6)]
# [1, 4, 9, 16, 25]

# With strings
words = ["hello", "world"]
uppercase = [word.upper() for word in words]
# ["HELLO", "WORLD"]
```

**With Conditionals:**

```
python
# Filter even numbers
numbers = [1, 2, 3, 4, 5, 6, 7, 8, 9, 10]
evens = [x for x in numbers if x % 2 == 0]
# [2, 4, 6, 8, 10]

# With if-else (ternary)
numbers = [1, 2, 3, 4, 5]
labels = ["even" if x % 2 == 0 else "odd" for x in numbers]
# ['odd', 'even', 'odd', 'even', 'odd']

# Nested conditionals
result = [x for x in range(100) if x % 2 == 0 if x % 5 == 0]
# [0, 10, 20, 30, 40, 50, 60, 70, 80, 90]
```

**Dictionary Comprehension:**

```python
# Create dictionary from two lists
keys = ["a", "b", "c"]
values = [1, 2, 3]
d = {k: v for k, v in zip(keys, values)}
# {'a': 1, 'b': 2, 'c': 3}

# Square dictionary
squares = {x: x**2 for x in range(1, 6)}
# {1: 1, 2: 4, 3: 9, 4: 16, 5: 25}

# Filter dictionary
d = {"a": 1, "b": 2, "c": 3, "d": 4}
filtered = {k: v for k, v in d.items() if v > 2}
# {'c': 3, 'd': 4}
```

**Set Comprehension:**

```
python
# Similar to list but with braces
text = "hello world"
unique_chars = {char for char in text}
# {'h', 'e', 'l', 'o', ' ', 'w', 'r', 'd'}

# With condition
numbers = [1, 2, 2, 3, 3, 3, 4]
unique_evens = {x for x in numbers if x % 2 == 0}
# {2, 4}
```

### Practice Exercises

1. ✅ Create a list of squares of numbers 1-10
2. ✅ Filter words starting with 'a' from a list
3. ✅ Create a dictionary mapping numbers to their cubes
4. ✅ Extract uppercase letters from a string
5. ✅ Flatten a nested list using list comprehension

### Small Task/Challenge

Build a data transformation program:

```
python
# Input: [1, 2, 3, 4, 5]
# Output:
# Original: [1, 2, 3, 4, 5]
# Squares: [1, 4, 9, 16, 25]
# Evens: [2, 4]
# Dictionary: {1: 1, 2: 4, 3: 9, 4: 16, 5: 25}
```

### Expected Outcome

- Write concise list comprehensions
- Apply conditionals within comprehensions
- Create dictionary and set comprehensions
- Write more Pythonic code

---

## Day 12: Functions - Part 1

### Topics to Learn

- Function definition and calling
- Parameters and arguments
- Return statements
- Default parameters
- *args and **kwargs

### Concept Explanations

**Basic Functions:**

```
python
# Function definition
def greet():
    print("Hello, World!")

# Call function
greet()  # Hello, World!

# Function with parameters
def greet_person(name):
    print(f"Hello, {name}!")

greet_person("Alice")  # Hello, Alice!

# Function with return value
def add(a, b):
    return a + b

result = add(3, 5)
print(result)  # 8
```

**Parameters:**

```
python
# Default parameters
def greet(name="Guest"):
    print(f"Hello, {name}!")

greet()           # Hello, Guest!
greet("Alice")    # Hello, Alice!

# Multiple parameters
def introduce(name, age, city="Unknown"):
    print(f"I'm {name}, {age} years old, from {city}")

introduce("John", 30)
introduce("Alice", 25, "NYC")

# Keyword arguments
introduce(age=25, name="Bob", city="LA")
```

***args and **kwargs:**

```
python
# *args - variable number of positional arguments
def sum_all(*args):
    total = 0
    for num in args:
        total += num
    return total

print(sum_all(1, 2, 3))      # 6
print(sum_all(1, 2, 3, 4, 5))  # 15

# **kwargs - variable number of keyword arguments
def print_info(**kwargs):
    for key, value in kwargs.items():
        print(f"{key}: {value}")

print_info(name="John", age=30, city="NYC")
# name: John
# age: 30
# city: NYC

# Combined
def func(*args, **kwargs):
    print(f"Args: {args}")
    print(f"Kwargs: {kwargs}")

func(1, 2, 3, name="Alice", age=25)
# Args: (1, 2, 3)
# Kwargs: {'name': 'Alice', 'age': 25}
```

### Practice Exercises

1. ✅ Write a function to check if a number is prime
2. ✅ Create a function to calculate the factorial
3. ✅ Write a function that accepts *args and returns the maximum
4. ✅ Create a function with default parameters for person info
5. ✅ Write a function that accepts **kwargs and prints all values

### Small Task/Challenge

Build a calculator with functions:

```
python
# add(2, 3) -> 5
# subtract(10, 4) -> 6
# multiply(3, 5) -> 15
# divide(10, 2) -> 5
# calculator("add", 2, 3) -> 5
# calculator("multiply", 4, 5) -> 20
```

### Expected Outcome

- Define and call functions properly
- Use parameters, arguments, and return values
- Handle default parameters
- Work with *args and **kwargs

---

## Day 13: Functions - Part 2

### Topics to Learn

- Lambda functions
- Scope (local, global, nonlocal)
- Nested functions
- Decorators basics

### Concept Explanations

**Lambda Functions:**

```
python
# Basic lambda
square = lambda x: x ** 2
print(square(5))  # 25

# Lambda with multiple arguments
add = lambda a, b: a + b
print(add(3, 5))  # 8

# Common use cases
numbers = [1, 2, 3, 4, 5]

# With sorted()
pairs = [(1, "one"), (3, "three"), (2, "two")]
sorted_pairs = sorted(pairs, key=lambda x: x[0])
# [(1, 'one'), (2, 'two'), (3, 'three')]

# With map()
squared = list(map(lambda x: x**2, numbers))
# [1, 4, 9, 16, 25]

# With filter()
evens = list(filter(lambda x: x % 2 == 0, numbers))
# [2, 4]

# With reduce()
from functools import reduce
product = reduce(lambda x, y: x * y, numbers)
# 120
```

**Scope:**

```
python
# Global variable
global_var = "I'm global"

def test_scope():
    # Local variable
    local_var = "I'm local"
    print(global_var)  # Can access global
    print(local_var)  # Can access local

# print(local_var)  # ERROR - can't access outside

# Modifying global variable
counter = 0

def increment():
    global counter  # Declare global
    counter += 1

# nonlocal (for nested functions)
def outer():
    count = 0
    
    def inner():
        nonlocal count
        count += 1
        print(count)
    
    inner()

outer()  # 1
```

**Nested Functions:**

```
python
def outer_function():
    message = "Hello"
    
    def inner_function():
        print(message)  # Can access outer variable
    
    inner_function()

outer_function()  # Hello
```

### Practice Exercises

1. ✅ Write a lambda to check if a string starts with 'a'
2. ✅ Use lambda with sorted() to sort by last character
3. ✅ Create a function that returns a lambda
4. ✅ Use map() and lambda to convert strings to uppercase
5. ✅ Use filter() to get words longer than 5 characters

### Small Task/Challenge

Build a filter-map-reduce system:

```
python
# numbers = [1, 2, 3, 4, 5, 6, 7, 8, 9, 10]

# Filter: Only even numbers
# Map: Square them
# Reduce: Sum them
# Result: 220 (4+16+36+64+100)
```

### Expected Outcome

- Write concise lambda functions
- Understand variable scope
- Use nonlocal and global appropriately
- Apply lambda with built-in functions

---

## Day 14: Week 2 Review & Mini-Project

### Weekly Milestones

✅ **Week 2 Completed:**

- [ ] Tuples and sets
- [ ] Dictionaries
- [ ] For and while loops
- [ ] List comprehensions
- [ ] Functions and lambdas

### Mini-Project: Todo List Application

Build a complete todo list application:

```
python
# Features:
# 1. Add task
# 2. Remove task
# 3. Mark task as complete
# 4. View all tasks
# 5. View pending tasks
# 6. View completed tasks

# Expected output:
# 1. Add Task
# 2. Remove Task
# 3. Mark Complete
# 4. View All
# 5. Exit
# Enter choice: 1
# Enter task: Learn Python
# Task added!
```

### Commands/Concepts Review

```
python
# Tuples
coord = (1, 2, 3)
x, y, z = coord

# Sets
unique = set([1, 2, 2, 3])

# Dictionaries
d = {"key": "value"}

# Loops
for i in range(10):
    if i % 2 == 0:
        continue

# List comprehension
squares = [x**2 for x in range(10)]

# Functions
def func(*args, **kwargs):
    pass
```

### Expected Outcome

- Confirmed understanding of Week 2 topics
- Complete todo list mini-project
- Ready to proceed to Week 3

---

# PHASE 3: FUNCTIONS & ADVANCED CONCEPTS (Days 15-21)

---

## Day 15: Error Handling (Try-Except)

### Topics to Learn

- Understanding exceptions
- Try-except blocks
- Multiple except blocks
- Finally clause
- Raising exceptions

### Concept Explanations

**Basic Try-Except:**

```
python
# Basic syntax
try:
    result = 10 / 0
except ZeroDivisionError:
    print("Cannot divide by zero!")

# Catching specific exceptions
try:
    num = int(input("Enter a number: "))
    result = 10 / num
except ValueError:
    print("That's not a valid number!")
except ZeroDivisionError:
    print("Cannot divide by zero!")
```

**Else and Finally:**

```
python
try:
    file = open("example.txt", "r")
    content = file.read()
except FileNotFoundError:
    print("File not found!")
else:
    print("File read successfully!")
    file.close()
finally:
    print("This always runs!")

# Finally for cleanup
try:
    result = 10 / 2
except Exception as e:
    print(f"Error: {e}")
finally:
    print("Cleanup complete")
```

**Raising Exceptions:**

```
python
def divide(a, b):
    if b == 0:
        raise ValueError("Divisor cannot be zero")
    return a / b

try:
    result = divide(10, 0)
except ValueError as e:
    print(e)  # Divisor cannot be zero

# Custom exceptions
class CustomError(Exception):
    pass

raise CustomError("This is a custom error")
```

### Practice Exercises

1. ✅ Handle division by zero error
2. ✅ Handle invalid input (non-numeric)
3. ✅ Handle file not found error
4. ✅ Create a custom exception for invalid age
5. ✅ Handle multiple exceptions in one try block

### Small Task/Challenge

Build a robust calculator with error handling:

```
python
# Enter first number: 10
# Enter operator: /
# Enter second number: 0
# Error: Cannot divide by zero!

# Enter first number: abc
# Error: Please enter valid numbers
```

### Expected Outcome

- Handle exceptions gracefully
- Use try-except-else-finally
- Raise custom exceptions
- Write robust error-handling code

---

## Day 16: File Handling

### Topics to Learn

- Opening and closing files
- Reading files
- Writing files
- Context managers (with statement)
- Working with CSV and JSON

### Concept Explanations

**Reading Files:**

```
python
# Basic reading
file = open("example.txt", "r")
content = file.read()
print(content)
file.close()

# Read lines
file = open("example.txt", "r")
lines = file.readlines()
for line in lines:
    print(line.strip())
file.close()

# Read line by line
file = open("example.txt", "r")
for line in file:
    print(line.strip())
file.close()

# Using with statement (recommended)
with open("example.txt", "r") as file:
    content = file.read()
# File automatically closed
```

**Writing Files:**

```
python
# Write (overwrites)
with open("example.txt", "w") as file:
    file.write("Hello, World!\n")
    file.write("Second line")

# Append
with open("example.txt", "a") as file:
    file.write("\nAppended line")

# Write multiple lines
lines = ["Line 1\n", "Line 2\n", "Line 3\n"]
with open("example.txt", "w") as file:
    file.writelines(lines)
```

**Working with CSV:**

```
python
import csv

# Writing CSV
with open("data.csv", "w", newline="") as file:
    writer = csv.writer(file)
    writer.writerow(["Name", "Age", "City"])
    writer.writerow(["Alice", 25, "NYC"])
    writer.writerow(["Bob", 30, "LA"])

# Reading CSV
with open("data.csv", "r") as file:
    reader = csv.reader(file)
    for row in reader:
        print(row)
```

**Working with JSON:**

```
python
import json

# Writing JSON
data = {
    "name": "John",
    "age": 30,
    "city": "NYC"
}

with open("data.json", "w") as file:
    json.dump(data, file, indent=4)

# Reading JSON
with open("data.json", "r") as file:
    data = json.load(file)
    print(data["name"])  # John
```

### Practice Exercises

1. ✅ Read a file and count the number of lines
2. ✅ Write a list of numbers to a file
3. ✅ Read a CSV file and calculate averages
4. ✅ Create a JSON file with nested data
5. ✅ Append to an existing file

### Small Task/Challenge

Build a note-taking app:

```
python
# Options: 1. Write note 2. Read notes 3. Delete note 4. Exit
# Enter choice: 1
# Enter note: Today I learned Python
# Note saved!

# Enter choice: 2
# Notes:
# 1. Today I learned Python
```

### Expected Outcome

- Read and write files efficiently
- Use context managers
- Handle CSV and JSON files
- Build file-based applications

---

## Day 17: Modules & Packages

### Topics to Learn

- Importing modules
- Creating your own modules
- Package structure
- Standard library overview
- pip and package management

### Concept Explanations

**Importing Modules:**

```
python
# Import entire module
import math
print(math.sqrt(16))  # 4.0
print(math.pi)        # 3.14159...

# Import specific items
from math import sqrt, pi
print(sqrt(16))  # 4.0

# Import with alias
import numpy as np
import pandas as pd

# Import all (not recommended)
from math import *
```

**Standard Library Modules:**

```
python
import datetime
print(datetime.datetime.now())

import random
print(random.randint(1, 10))
print(random.choice(["a", "b", "c"]))

import os
print(os.getcwd())
print(os.listdir("."))

import sys
print(sys.version)
print(sys.argv)

import json
import csv
import re
```

**Creating Your Own Module:**

```
python
# mymodule.py
def greet(name):
    return f"Hello, {name}!"

def add(a, b):
    return a + b

# main.py
import mymodule
print(mymodule.greet("Alice"))  # Hello, Alice!
print(mymodule.add(3, 5))        # 8
```

**Creating Packages:**

```
my_package/
    __init__.py
    module1.py
    module2.py
    subpackage/
        __init__.py
        module3.py
```

### Practice Exercises

1. ✅ Import and use the math module
2. ✅ Create a custom module with multiple functions
3. ✅ Use the random module to generate a random password
4. ✅ Import os and list files in a directory
5. ✅ Use datetime to calculate days between dates

### Small Task/Challenge

Create a utility module:

```
python
# Create a utilities.py module with:
# - calculate_area(radius)
# - celsius_to_fahrenheit(c)
# - is_palindrome(text)
# - word_count(text)

# Import and use in main.py
```

### Expected Outcome

- Import and use modules
- Create custom modules and packages
- Navigate the Python standard library
- Understand package management

---

## Day 18: Object-Oriented Programming - Classes

### Topics to Learn

- Classes and objects
- __init__ method
- Instance variables
- Methods
- Self parameter

### Concept Explanations

**Creating Classes:**

```
python
class Dog:
    # Class attribute (shared by all instances)
    species = "Canis familiaris"
    
    # Constructor
    def __init__(self, name, age):
        # Instance attributes
        self.name = name
        self.age = age
    
    # Instance method
    def bark(self):
        return f"{self.name} says Woof!"
    
    # Another method
    def get_info(self):
        return f"{self.name} is {self.age} years old"

# Creating objects
dog1 = Dog("Buddy", 3)
dog2 = Dog("Max", 5)

print(dog1.name)        # Buddy
print(dog1.bark())      # Buddy says Woof!
print(Dog.species)      # Canis familiaris
```

**More Class Examples:**

```
python
class Car:
    def __init__(self, make, model, year):
        self.make = make
        self.model = model
        self.year = year
        self.odometer = 0
    
    def drive(self, miles):
        self.odometer += miles
        return f"Drove {miles} miles"
    
    def get_odometer(self):
        return f"Current mileage: {self.odometer}"
    
    def __str__(self):
        return f"{self.year} {self.make} {self.model}"

my_car = Car("Toyota", "Camry", 2022)
print(my_car)           # 2022 Toyota Camry
print(my_car.drive(100))  # Driven 100 miles
```

### Practice Exercises

1. ✅ Create a Student class with name, grade, and subjects
2. ✅ Add methods to calculate average grade
3. ✅ Create a BankAccount class with deposit and withdraw
4. ✅ Add a __str__ method to the BankAccount class
5. ✅ Create a Book class with title, author, and pages

### Small Task/Challenge

Build a Rectangle class:

```
python
class Rectangle:
    def __init__(self, width, height):
        # Initialize attributes
    
    def area(self):
        # Return area
    
    def perimeter(self):
        # Return perimeter
    
    def __str__(self):
        # Return string representation

# Test
r = Rectangle(5, 3)
print(r)           # Rectangle: 5 x 3
print(r.area())    # 15
print(r.perimeter())  # 16
```

### Expected Outcome

- Create classes and objects
- Understand __init__ and self
- Define instance methods
- Use __str__ for string representation

---

## Day 19: OOP - Inheritance & Polymorphism

### Topics to Learn

- Inheritance
- super() function
- Method overriding
- Multiple inheritance
- Polymorphism

### Concept Explanations

**Inheritance:**

```
python
# Parent class
class Animal:
    def __init__(self, name):
        self.name = name
    
    def speak(self):
        return "Some sound"
    
    def __str__(self):
        return f"{self.__class__.__name__}: {self.name}"

# Child class
class Dog(Animal):
    def speak(self):
        return "Woof!"

class Cat(Animal):
    def speak(self):
        return "Meow!"

# Using inheritance
dog = Dog("Buddy")
print(dog)           # Dog: Buddy
print(dog.speak())   # Woof!
```

**super() Function:**

```
python
class Person:
    def __init__(self, name, email):
        self.name = name
        self.email = email

class Student(Person):
    def __init__(self, name, email, student_id):
        super().__init__(name, email)  # Call parent constructor
        self.student_id = student_id

student = Student("Alice", "alice@email.com", "S123")
print(student.name)        # Alice
print(student.email)       # alice@email.com
print(student.student_id)  # S123
```

**Multiple Inheritance:**

```
python
class Flyable:
    def fly(self):
        return "Flying!"

class Swimmable:
    def swim(self):
        return "Swimming!"

class Duck(Flyable, Swimmable):
    def quack(self):
        return "Quack!"

duck = Duck()
print(duck.fly())    # Flying!
print(duck.swim())   # Swimming!
print(duck.quack())  # Quack!
```

**Polymorphism:**

```
python
class Shape:
    def area(self):
        pass

class Rectangle(Shape):
    def __init__(self, width, height):
        self.width = width
        self.height = height
    
    def area(self):
        return self.width * self.height

class Circle(Shape):
    def __init__(self, radius):
        self.radius = radius
    
    def area(self):
        return 3.14 * self.radius ** 2

shapes = [Rectangle(5, 3), Circle(2)]
for shape in shapes:
    print(f"Area: {shape.area()}")
```

### Practice Exercises

1. ✅ Create a Vehicle class and Car/Bike subclasses
2. ✅ Add a method to parent and override in child
3. ✅ Create Employee and Manager classes
4. ✅ Implement multiple inheritance with Person
5. ✅ Use polymorphism with different shape classes

### Small Task/Challenge

Build an inheritance hierarchy:

```
python
# Person (parent)
# - Student (child)
# - Teacher (child)

# Student: name, id, grades, add_grade()
# Teacher: name, id, subjects, add_subject()

# Both should inherit from Person
```

### Expected Outcome

- Implement inheritance
- Use super() effectively
- Override methods
- Apply polymorphism

---

## Day 20: Virtual Environments & pip

### Topics to Learn

- What are virtual environments
- Creating and activating venv
- Installing packages with pip
- requirements.txt
- Common packages overview

### Concept Explanations

**Virtual Environments:**

```
bash
# Create virtual environment
python -m venv myenv

# Activate on Windows
myenv\Scripts\activate

# Activate on Mac/Linux
source myenv/bin/activate

# Install packages
pip install requests
pip install numpy pandas

# Check installed packages
pip list

# Deactivate
deactivate
```

**requirements.txt:**

```
bash
# Generate requirements.txt
pip freeze > requirements.txt

# Install from requirements.txt
pip install -r requirements.txt
```

**Common Packages:**

```
bash
# Web requests
pip install requests

# Data analysis
pip install numpy pandas

# Web development
pip install flask django

# Testing
pip install pytest

# Automation
pip install selenium beautifulsoup4
```

### Practice Exercises

1. ✅ Create a virtual environment
2. ✅ Install requests and use it
3. ✅ Create requirements.txt
4. ✅ Use pip to uninstall a package
5. ✅ Check available packages

### Small Task/Challenge

Set up a project environment:

```
bash
# 1. Create project folder
# 2. Create virtual environment
# 3. Install: requests, flask, pytest
# 4. Create requirements.txt
# 5. Write a simple Flask app
```

### Expected Outcome

- Create and manage virtual environments
- Install and use packages
- Create and use requirements.txt
- Understand dependency management

---

## Day 21: Week 3 Review & Mini-Project

### Weekly Milestones

✅ **Week 3 Completed:**

- [ ] Error handling
- [ ] File handling
- [ ] Modules and packages
- [ ] OOP basics
- [ ] Inheritance
- [ ] Virtual environments

### Mini-Project: Weather App

Build a weather information app:

```
python
# Features:
# 1. Get current weather by city
# 2. Get 5-day forecast
# 3. Save favorite cities
# 4. Display weather data

# Use requests to fetch data from OpenWeatherMap API
# (Use free API key or mock data)
```

### Commands/Concepts Review

```
python
# Error handling
try:
    pass
except Exception as e:
    pass

# File handling
with open("file.txt", "r") as f:
    pass

# OOP
class Parent:
    pass

class Child(Parent):
    pass
```

### Expected Outcome

- Confirmed understanding of Week 3 topics
- Complete weather mini-project
- Ready to proceed to Week 4

---

# PHASE 4: OOP, FILE HANDLING & REAL-WORLD APPS (Days 22-30)

---

## Day 22: Advanced OOP - Class Methods & Static Methods

### Topics to Learn

- Class methods
- Static methods
- Property decorators
- Dunder methods
- Class vs instance attributes

### Concept Explanations

**Class Methods and Static Methods:**

```
python
class MyClass:
    class_variable = 0
    
    def __init__(self, value):
        self.instance_variable = value
    
    # Instance method
    def instance_method(self):
        return f"Instance: {self.instance_variable}"
    
    # Class method - operates on class, not instance
    @classmethod
    def class_method(cls):
        cls.class_variable += 1
        return f"Class variable: {cls.class_variable}"
    
    # Static method - doesn't need class/instance
    @staticmethod
    def static_method(x, y):
        return x + y

# Using class methods
print(MyClass.class_method())  # Class variable: 1

# Using static methods
print(MyClass.static_method(3, 5))  # 8
```

**Property Decorators:**

```python
class Temperature:
    def __init__(self, celsius):
        self.celsius = celsius
    
    @property
    def fahrenheit(self):
        return (self.celsius * 9/5) + 32
    
    @property
    def kelvin(self):
        return self.celsius + 273.15
    
    @fahrenheit.setter
    def fahrenheit(self, value):
        self.celsius = (value - 32) * 5/9

temp = Temperature(25)
print(temp.fahrenheit)  # 77.0
temp.fahrenheit = 100
print(temp.celsius)     # 37.78
```

**Dunder Methods:**

```
python
class Book:
    def __init__(self, title, pages):
        self.title = title
        self.pages = pages
    
    def __str__(self):
        return f"{self.title} ({self.pages} pages)"
    
    def __repr__(self):
        return f"Book('{self.title}', {self.pages})"
    
    def __len__(self):
        return self.pages
    
    def __add__(self, other):
        return self.pages + other.pages
    
    def __eq__(self, other):
        return self.pages == other.pages

book = Book("Python", 300)
print(book)          # Python (300 pages)
print(len(book))     # 300
```

### Practice Exercises

1. ✅ Create a class with @classmethod to track instances
2. ✅ Use @property for computed attributes
3. ✅ Implement __str__ and __repr__
4. ✅ Create a custom list class with __add__
5. ✅ Use static method for utility calculations

### Small Task/Challenge

Build a smart calculator class:

```
python
class Calculator:
    @staticmethod
    def add(*args):
        return sum(args)
    
    @classmethod
    def history(cls):
        # Track calculations
    
    @property
    def last_result(self):
        # Return last result
```

### Expected Outcome

- Use @classmethod and @staticmethod
- Apply @property decorators
- Implement dunder methods
- Understand class vs instance attributes

---

## Day 23: Decorators

### Topics to Learn

- What are decorators
- Creating decorators
- Decorators with arguments
- Built-in decorators (@property, @classmethod, @staticmethod)
- Practical decorator examples

### Concept Explanations

**Basic Decorators:**

```
python
# Decorator function
def my_decorator(func):
    def wrapper():
        print("Before function")
        func()
        print("After function")
    return wrapper

@my_decorator
def say_hello():
    print("Hello!")

say_hello()
# Before function
# Hello!
# After function
```

**Decorators with Arguments:**

```
python
def repeat(times):
    def decorator(func):
        def wrapper(*args, **kwargs):
            for _ in range(times):
                result = func(*args, **kwargs)
            return result
        return wrapper
    return decorator

@repeat(times=3)
def greet(name):
    print(f"Hello, {name}!")

greet("Alice")
# Hello, Alice!
# Hello, Alice!
# Hello, Alice!
```

**Built-in Decorators:**

```
python
class Example:
    @property
    def value(self):
        return self._value
    
    @classmethod
    def class_method(cls):
        pass
    
    @staticmethod
    def static_method():
        pass
```

**Practical Example - Timing Decorator:**

```
python
import time

def timer(func):
    def wrapper(*args, **kwargs):
        start = time.time()
        result = func(*args, **kwargs)
        end = time.time()
        print(f"{func.__name__} took {end - start:.2f} seconds")
        return result
    return wrapper

@timer
def slow_function():
    time.sleep(1)
    print("Done!")

slow_function()  # Done! slow_function took 1.00 seconds
```

### Practice Exercises

1. ✅ Create a decorator that logs function calls
2. ✅ Create a decorator that validates input
3. ✅ Create a decorator that retries on failure
4. ✅ Stack multiple decorators
5. ✅ Create a decorator with arguments

### Small Task/Challenge

Build authentication decorator:

```
python
def requires_auth(func):
    # Check if user is authenticated
    # Return function or error
    pass

@requires_auth
def delete_account():
    # Delete account logic
    pass
```

### Expected Outcome

- Create custom decorators
- Use decorators with arguments
- Apply built-in decorators
- Build practical decorator solutions

---

## Day 24: Generators & Iterators

### Topics to Learn

- Iterators
- Generators
- yield keyword
- Generator expressions
- itertools module

### Concept Explanations

**Iterators:**

```
python
# Custom iterator
class Counter:
    def __init__(self, limit):
        self.limit = limit
        self.current = 0
    
    def __iter__(self):
        return self
    
    def __next__(self):
        if self.current < self.limit:
            self.current += 1
            return self.current
        raise StopIteration

for num in Counter(5):
    print(num)  # 1, 2, 3, 4, 5
```

**Generators:**

```
python
# Generator function
def count_up_to(n):
    current = 1
    while current <= n:
        yield current
        current += 1

gen = count_up_to(5)
print(next(gen))  # 1
print(next(gen))  # 2
print(list(gen))  # [3, 4, 5]

# Using in loops
for num in count_up_to(5):
    print(num)  # 1, 2, 3, 4, 5
```

**Generator Expressions:**

```
python
# Like list comprehension but lazy
gen = (x**2 for x in range(10))
print(next(gen))  # 0
print(next(gen))  # 1

# Use with sum, max, min
total = sum(x**2 for x in range(1, 101))
print(total)  # 338350
```

**Fibonacci with Generator:**

```
python
def fibonacci(n):
    a, b = 0, 1
    for _ in range(n):
        yield a
        a, b = b, a + b

for num in fibonacci(10):
    print(num)  # 0, 1, 1, 2, 3, 5, 8, 13, 21, 34
```

### Practice Exercises

1. ✅ Create a generator for even numbers
2. ✅ Create a generator that yields prime numbers
3. ✅ Use generator expression for sum
4. ✅ Create custom iterator class
5. ✅ Implement infinite generator

### Small Task/Challenge

Build a password generator:

```
python
def generate_passwords(length, count):
    # Yield 'count' number of random passwords
    pass

for pwd in generate_passwords(8, 5):
    print(pwd)
```

### Expected Outcome

- Create generators with yield
- Use generator expressions
- Build custom iterators
- Understand lazy evaluation

---

## Day 25: Regular Expressions (Regex)

### Topics to Learn

- Regex basics
- Pattern matching
- Character classes
- Quantifiers
- Groups and alternation

### Concept Explanations

**Basic Patterns:**

```
python
import re

# Search for pattern
text = "My email is john@example.com"
pattern = r"\w+@\w+\.\w+"
match = re.search(pattern, text)
print(match.group())  # john@example.com

# Find all matches
text = "Call 555-1234 or 555-5678"
numbers = re.findall(r"\d{3}-\d{4}", text)
print(numbers)  # ['555-1234', '555-5678']
```

**Character Classes:**

```
python
# \d - Digit [0-9]
# \D - Non-digit
# \w - Word char [a-zA-Z0-9_]
# \W - Non-word char
# \s - Whitespace
# \S - Non-whitespace
# . - Any character except newline
# [abc] - Any of a, b, or c
# [^abc] - Not a, b, or c
# [a-z] - Range

print(re.findall(r"\d", "abc123"))  # ['1', '2', '3']
print(re.findall(r"\w+", "Hello World"))  # ['Hello', 'World']
```

**Quantifiers:**

```
python
# * - 0 or more
# + - 1 or more
# ? - 0 or 1
# {n} - exactly n
# {n,} - n or more
# {n,m} - between n and m

print(re.findall(r"\d+", "123 abc 456"))  # ['123', '456']
print(re.findall(r"\d{3}", "12345"))  # ['123', '45']
print(re.findall(r"colou?r", "color colour"))  # ['color', 'colour']
```

**Groups:**

```
python
# Groups with ()
text = "John Doe, 30 years old"
pattern = r"(\w+) (\w+), (\d+)"
match = re.search(pattern, text)
print(match.group(1))  # John
print(match.group(2))  # Doe
print(match.group(3))  # 30
print(match.groups())   # ('John', 'Doe', '30')

# Named groups
pattern = r"(?P<name>\w+) (?P<surname>\w+)"
match = re.search(pattern, "John Doe")
print(match.group("name"))  # John
```

### Practice Exercises

1. ✅ Validate email address format
2. ✅ Extract all phone numbers from text
3. ✅ Find all words starting with 'a'
4. ✅ Replace all numbers with 'X'
5. ✅ Validate password (8+ chars, has digit, has uppercase)

### Small Task/Challenge

Build a text parser:

```
python
# Extract:
# - All emails
# - All URLs
# - All phone numbers
# - All dates (MM/DD/YYYY format)

text = "Contact me at john@email.com or visit https://example.com. Call 555-123-4567 on 12/25/2024."
```

### Expected Outcome

- Write regex patterns
- Use character classes and quantifiers
- Create groups and named groups
- Apply regex for text parsing

---

## Day 26: Working with APIs

### Topics to Learn

- What is an API
- REST API concepts
- Making HTTP requests
- Handling JSON responses
- Error handling with APIs

### Concept Explanations

**HTTP Requests:**

```
python
import requests

# GET request
response = requests.get("https://api.github.com")
print(response.status_code)  # 200
print(response.json())       # Response data

# GET with parameters
params = {"page": 1, "per_page": 10}
response = requests.get("https://api.github.com/users", params=params)

# POST request
data = {"title": "foo", "body": "bar", "userId": 1}
response = requests.post("https://jsonplaceholder.typicode.com/posts", json=data)

# Headers
headers = {"Authorization": "Bearer token"}
response = requests.get("https://api.example.com", headers=headers)
```

**Working with JSON:**

```
python
import requests

response = requests.get("https://jsonplaceholder.typicode.com/users/1")
data = response.json()

# Access nested data
print(data["name"])              # Leanne Graham
print(data["address"]["city"])   # Gwenborough

# Parse JSON from string
json_string = '{"name": "John", "age": 30}'
data = json.loads(json_string)
```

**Error Handling:**

```
python
import requests

try:
    response = requests.get("https://api.example.com", timeout=5)
    response.raise_for_status()  # Raises exception for 4xx/5xx
    data = response.json()
except requests.exceptions.Timeout:
    print("Request timed out")
except requests.exceptions.ConnectionError:
    print("Connection error")
except requests.exceptions.HTTPError as e:
    print(f"HTTP error: {e}")
else:
    print("Success:", data)
```

### Practice Exercises

1. ✅ Fetch data from a public API (JSONPlaceholder)
2. ✅ Make a POST request to create data
3. ✅ Handle API errors gracefully
4. ✅ Parse nested JSON response
5. ✅ Use query parameters

### Small Task/Challenge

Build a simple API client:

```
python
# Fetch weather data from OpenWeatherMap
# Display: temperature, humidity, description
# Handle errors gracefully
# Use environment variables for API key
```

### Expected Outcome

- Make HTTP requests
- Parse JSON responses
- Handle API errors
- Build API clients

---

## Day 27: Multithreading Basics

### Topics to Learn

- What is multithreading
- Threading module
- Creating threads
- Thread synchronization
- When to use threading

### Concept Explanations

**Creating Threads:**

```
python
import threading
import time

def task(name, duration):
    print(f"{name} started")
    time.sleep(duration)
    print(f"{name} finished")

# Create threads
t1 = threading.Thread(target=task, args=("Task 1", 2))
t2 = threading.Thread(target=task, args=("Task 2", 1))

# Start threads
t1.start()
t2.start()

# Wait for completion
t1.join()
t2.join()

print("All tasks complete!")
```

**Thread Pool:**

```
python
from concurrent.futures import ThreadPoolExecutor

def task(n):
    return n * n

with ThreadPoolExecutor(max_workers=5) as executor:
    results = executor.map(task, [1, 2, 3, 4, 5])
    print(list(results))  # [1, 4, 9, 16, 25]
```

**Thread Synchronization:**

```
python
import threading

counter = 0
lock = threading.Lock()

def increment():
    global counter
    with lock:
        for _ in range(100000):
            counter += 1

threads = [threading.Thread(target=increment) for _ in range(5)]
for t in threads:
    t.start()
for t in threads:
    t.join()

print(counter)  # 500000
```

### Practice Exercises

1. ✅ Create multiple threads to download files
2. ✅ Use thread pool for parallel processing
3. ✅ Implement thread-safe counter
4. ✅ Use queue for thread communication
5. ✅ Compare execution time with/without threads

### Small Task/Challenge

Build a parallel file downloader:

```
python
# Download multiple files simultaneously
# Show progress for each file
# Handle completion
```

### Expected Outcome

- Create and manage threads
- Use thread pools
- Implement thread synchronization
- Understand threading limitations

---

## Day 28: Async Basics (asyncio)

### Topics to Learn

- Async programming concepts
- async/await syntax
- asyncio module
- Coroutines
- Tasks and futures

### Concept Explanations

**Basic Async:**

```
python
import asyncio

async def say_hello():
    print("Hello")
    await asyncio.sleep(1)
    print("World")

async def main():
    await say_hello()

asyncio.run(main())
```

**Multiple Coroutines:**

```
python
import asyncio

async def task(name, delay):
    print(f"{name} started")
    await asyncio.sleep(delay)
    print(f"{name} finished")

async def main():
    # Run concurrently
    await asyncio.gather(
        task("Task 1", 2),
        task("Task 2", 1),
        task("Task 3", 3)
    )

asyncio.run(main())
# All tasks run simultaneously!
```

**Async with Requests:**

```
python
import asyncio
import aiohttp

async def fetch_url(session, url):
    async with session.get(url) as response:
        return await response.text()

async def main():
    urls = ["https://example.com", "https://example.org"]
    async with aiohttp.ClientSession() as session:
        results = await asyncio.gather(*[fetch_url(session, url) for url in urls])
        print(len(results))

asyncio.run(main())
```

### Practice Exercises

1. ✅ Create async function with sleep
2. ✅ Run multiple coroutines concurrently
3. ✅ Use asyncio.gather
4. ✅ Handle async errors
5. ✅ Compare with threading

### Small Task/Challenge

Build async API fetcher:

```
python
# Fetch multiple API endpoints concurrently
# Calculate total time
# Handle errors gracefully
```

### Expected Outcome

- Write async/await code
- Run coroutines concurrently
- Use asyncio.gather
- Understand async vs sync

---

## Day 29: Testing Basics

### Topics to Learn

- Why testing matters
- Types of testing
- pytest framework
- Writing test cases
- Assertions

### Concept Explanations

**Basic Testing with pytest:**

```
python
# test_example.py
import pytest

def add(a, b):
    return a + b

def test_add():
    assert add(2, 3) == 5
    assert add(-1, 1) == 0
    assert add(0, 0) == 0

def test_add_strings():
    assert add("Hello ", "World") == "Hello World"
```

**Assertions:**

```
python
# Common assertions
assert x == y
assert x != y
assert x is None
assert x is not None
assert x in list
assert x not in list
assert isinstance(x, int)
assert raises(Exception, function)
```

**Fixtures:**

```
python
import pytest

@pytest.fixture
def sample_data():
    return {"name": "John", "age": 30}

def test_with_fixture(sample_data):
    assert sample_data["name"] == "John"
```

**Testing Classes:**

```
python
class TestMathOperations:
    def test_add(self):
        assert 2 + 3 == 5
    
    def test_multiply(self):
        assert 2 * 3 == 6
    
    def test_divide(self):
        assert 6 / 2 == 3
```

### Practice Exercises

1. ✅ Write tests for a calculator
2. ✅ Use pytest fixtures
3. ✅ Test exception handling
4. ✅ Test a class with multiple methods
5. ✅ Use parametrize for multiple test cases

### Small Task/Challenge

Test a data processing module:

```
python
# test_data.py
# Test functions that:
# - Calculate average
# - Filter data
# - Transform data
# - Handle errors
```

### Expected Outcome

- Write basic test cases
- Use pytest framework
- Apply fixtures
- Understand testing best practices

---

## Day 30: Final Capstone Project & Review

### Weekly Milestones

✅ **Week 4 Completed:**

- [ ] Advanced OOP
- [ ] Decorators
- [ ] Generators
- [ ] Regex
- [ ] APIs
- [ ] Multithreading
- [ ] Async
- [ ] Testing

### Final Capstone Project

Build a complete CLI application: **Personal Finance Tracker**

```
python
"""
Features:
1. Add transaction (income/expense)
2. View transaction history
3. View summary (total income, expenses, balance)
4. Filter by category
5. Export to CSV
6. Data persistence (JSON)
7. Input validation
8. Error handling

Structure:
- Transaction class
- FinanceManager class
- CLI interface
- File handling
- Input validation
- Testing
"""
```

### Project Structure

```
finance_tracker/
├── main.py           # Entry point
├── models/
│   └── transaction.py
├── managers/
│   └── finance_manager.py
├── utils/
│   ├── validators.py
│   └── file_handler.py
├── tests/
│   └── test_finance.py
├── data/
│   └── transactions.json
└── requirements.txt
```

### Expected Outcome

- Build complete application
- Apply all learned concepts
- Write tests
- Follow best practices

---

# 🎯 Weekly Mini-Projects

## Week 1 Mini-Project: Calculator

Build a simple calculator with basic operations:
- Addition, subtraction, multiplication, division
- User-friendly CLI interface
- Error handling for invalid inputs

## Week 2 Mini-Project: Todo List App

Create a todo list application:
- Add, remove, mark complete
- Store tasks in a list
- Display formatted list
- Simple text-based menu

## Week 3 Mini-Project: Weather App

Build a weather information app:
- Fetch weather data (use API or mock)
- Display current conditions
- Support multiple cities
- Save favorites

## Week 4 Mini-Project: Portfolio Website (Optional)

Create a personal portfolio:
- Basic Flask web app
- Multiple pages
- Contact form
- Responsive design

---

# 🏆 Final Capstone Project

## Personal Finance Tracker

Build a complete CLI application for tracking personal finances.

### Features

1. **Transaction Management**
   - Add income/expense
   - Categorize transactions
   - Add descriptions
   - Date tracking

2. **View & Filter**
   - View all transactions
   - Filter by type (income/expense)
   - Filter by category
   - Filter by date range

3. **Summary Reports**
   - Total income
   - Total expenses
   - Current balance
   - Category breakdown

4. **Data Persistence**
   - Save to JSON file
   - Load on startup
   - Auto-save changes

5. **Additional Features**
   - Export to CSV
   - Input validation
   - Error handling
   - Help system

### Sample Output

```
===== Personal Finance Tracker =====
1. Add Income
2. Add Expense
3. View All Transactions
4. View Summary
5. Filter by Category
6. Export to CSV
7. Exit

Enter choice: 1
Enter description: Salary
Enter amount: 5000
Enter category: Income
Transaction added!

Enter choice: 4
===== Summary =====
Total Income: $5000
Total Expenses: $0
Balance: $5000
```

---

# 📝 Interview Questions & Answers

## Python Basics

**Q: What is Python?**
A: Python is a high-level, interpreted programming language known for its simplicity, readability, and versatility. It supports multiple programming paradigms including procedural, object-oriented, and functional programming.

**Q: What is the difference between lists and tuples?**
A: Lists are mutable (can be modified) while tuples are immutable (cannot be modified). Lists use more memory and are slower, tuples are faster and use less memory.

**Q: What is PEP 8?**
A: PEP 8 is Python's style guide that provides conventions for writing Python code, including naming conventions, code layout, and best practices.

**Q: What is the difference between `==` and `is`?**
A: `==` checks for value equality while `is` checks for identity (whether they are the same object in memory).

**Q: What are Python decorators?**
A: Decorators are functions that modify the behavior of other functions. They are used to add functionality without modifying the original function.

## Data Structures

**Q: What is a dictionary in Python?**
A: A dictionary is an unordered collection of key-value pairs. Keys must be unique and immutable (strings, numbers, tuples), while values can be any type.

**Q: How do you remove duplicates from a list?**
A: Use `list(set(original_list))` or use a dict comprehension to preserve order.

**Q: What is list comprehension?**
A: List comprehension is a concise way to create lists using a single line of code with optional conditions.

## Functions

**Q: What is the difference between arguments and parameters?**
A: Parameters are variables in the function definition, arguments are the actual values passed when calling the function.

**Q: What are *args and **kwargs?**
A: `*args` allows passing a variable number of positional arguments, `**kwargs` allows passing variable number of keyword arguments.

**Q: What is a lambda function?**
A: A lambda function is an anonymous function defined with the `lambda` keyword, typically used for short, simple operations.

## OOP

**Q: What is inheritance?**
A: Inheritance allows a class (child class) to inherit attributes and methods from another class (parent class), promoting code reuse.

**Q: What is polymorphism?**
A: Polymorphism allows objects of different classes to be treated as objects of a common superclass, typically through method overriding.

**Q: What is the difference between public, private, and protected?**
A: In Python, there's no strict access control. By convention, `_variable` is protected, `__variable` is name-mangled (private), and public variables have no prefix.

## Advanced Topics

**Q: What is a generator?**
A: A generator is a function that yields values one at a time using the `yield` keyword, creating an iterator that can be iterated over lazily.

**Q: What is the difference between threading and asyncio?**
A: Threading uses OS threads and is suitable for I/O-bound tasks with GIL release. asyncio uses coroutines and is event-driven, better for high-concurrency I/O operations.

**Q: What is GIL (Global Interpreter Lock)?**
A: GIL is a mutex that protects access to Python objects, preventing multiple threads from executing Python bytecode simultaneously, making CPU-bound threads less effective.

---

# ⚠️ Common Mistakes to Avoid

## 1. Using `=` Instead of `==`

```
python
# ❌ Wrong
if x = 5:  # SyntaxError

# ✅ Correct
if x == 5:
    print("x is 5")
```

## 2. Not Handling Mutable Default Arguments

```
python
# ❌ Wrong
def add_item(item, list=[]):
    list.append(item)
    return list

# ✅ Correct
def add_item(item, list=None):
    if list is None:
        list = []
    list.append(item)
    return list
```

## 3. Modifying List While Iterating

```
python
# ❌ Wrong
for item in my_list:
    if item < 0:
        my_list.remove(item)

# ✅ Correct
my_list = [item for item in my_list if item >= 0]
```

## 4. Using Wrong Indentation

```
python
# ❌ Wrong
def func():
print("Hello")

# ✅ Correct
def func():
    print("Hello")
```

## 5. Not Closing Files

```
python
# ❌ Wrong
f = open("file.txt", "r")
content = f.read()
# Forgot to close

# ✅ Correct
with open("file.txt", "r") as f:
    content = f.read()
```

## 6. Mixing Tabs and Spaces

```
python
# Always use spaces (4 recommended)
# Configure your editor to use spaces
```

## 7. Not Using Virtual Environments

```
python
# ❌ Wrong - installing packages globally
pip install requests

# ✅ Correct - using virtual environment
python -m venv myenv
source myenv/bin/activate
pip install requests
```

## 8. Ignoring Exception Types

```
python
# ❌ Wrong
try:
    x = int(input())
except:  # Bare except catches everything
    print("Error")

# ✅ Correct
try:
    x = int(input())
except ValueError:
    print("Please enter a valid number")
```

---

# ✅ Python Best Practices

## Code Style

1. **Follow PEP 8** - Use 4 spaces for indentation
2. **Use meaningful names** - `user_name` not `n`
3. **Keep lines under 79 characters**
4. **Use blank lines sparingly** - Maximum 2 consecutive
5. **Comment meaningfully** - Explain "why", not "what"

## Functions

1. **Small, focused functions** - One task per function
2. **Use default arguments** - For optional parameters
3. **Document functions** - Use docstrings
4. **Return early** - Avoid deep nesting

## Classes

1. **Use PascalCase** - `MyClass`
2. **Use snake_case for methods** - `my_method()`
3. **One class per file** - Unless closely related
4. **Use `__init__`** - Initialize all attributes

## Error Handling

1. **Be specific** - Catch specific exceptions
2. **Don't ignore errors** - At least log them
3. **Clean up resources** - Use finally or context managers
4. **User-friendly messages** - Show helpful errors

## Performance

1. **Use list comprehensions** - Over loops when possible
2. **Use generators** - For large datasets
3. **Avoid global variables** - Pass data explicitly
4. **Profile before optimizing** - Use cProfile

## Testing

1. **Write tests early** - Test-driven development
2. **Test edge cases** - Empty, None, large inputs
3. **Name tests clearly** - `test_function_name`
4. **Keep tests independent** - No shared state

## Version Control

1. **Use .gitignore** - Ignore venv, __pycache__, .pyc
2. **Commit often** - Small, logical commits
3. **Write good commit messages** - Describe changes
4. **Use branches** - For features and fixes

---

# 💡 GitHub Project Ideas

## Beginner Projects

1. **Calculator** - Simple CLI calculator
2. **Guess the Number** - Random number guessing game
3. **To-Do List** - Task management app
4. **Currency Converter** - Exchange rate converter
5. **Password Generator** - Random password creator

## Intermediate Projects

6. **Weather App** - API-based weather information
7. **File Organizer** - Sort files by extension
8. **Web Scraper** - Extract data from websites
9. **Quiz App** - Interactive quiz system
10. **Budget Tracker** - Personal finance management

## Advanced Projects

11. **REST API** - Flask/Django REST API
12. **Chat Bot** - AI-powered chatbot
13. **Data Analyzer** - Pandas data analysis
14. **Portfolio Website** - Flask/Django web app
15. **Automation Scripts** - Task automation tools

---

# 📊 Practice Datasets & Examples

## Sample CSV Data

```
csv
name,age,city, salary
Alice,30,NYC,75000
Bob,25,LA,55000
Charlie,35,NYC,90000
Diana,28,Chicago,65000
Eve,32,NYC,80000
```

## Sample JSON Data

```
json
{
  "users": [
    {"id": 1, "name": "Alice", "email": "alice@email.com"},
    {"id": 2, "name": "Bob", "email": "bob@email.com"}
  ],
  "products": [
    {"id": 1, "name": "Laptop", "price": 999},
    {"id": 2, "name": "Phone", "price": 699}
  ]
}
```

## Practice Exercises

1. **CSV Analysis** - Calculate average salary by city
2. **JSON Parsing** - Extract and format user data
3. **Data Validation** - Check for missing/invalid values
4. **Data Transformation** - Convert between formats
5. **Statistical Analysis** - Mean, median, mode

---

# 📚 Resources & Next Steps

## Official Documentation

- [Python.org](https://www.python.org) - Official Python website
- [Python Docs](https://docs.python.org/3/) - Official documentation
- [PEP 8](https://www.python.org/dev/peps/pep-0008/) - Style guide

## Learning Platforms

- [Real Python](https://realpython.com) - In-depth tutorials
- [Python.org Tutorial](https://docs.python.org/3/tutorial/) - Official tutorial
- [W3Schools Python](https://www.w3schools.com/python/) - Beginner-friendly

## Practice Platforms

- [LeetCode](https://leetcode.com) - Algorithm practice
- [HackerRank](https://www.hackerrank.com) - Python practice
- [Project Euler](https://projecteuler.net) - Math problems
- [Codewars](https://www.codewars.com) - Coding challenges

## Frameworks to Learn Next

- **Web Development**: Django, Flask, FastAPI
- **Data Science**: Pandas, NumPy, Matplotlib
- **Machine Learning**: TensorFlow, PyTorch, Scikit-learn
- **Automation**: Selenium, BeautifulSoup, Scrapy

## Certifications

- [PCEP](https://pythoninstitute.org/pcep) - Entry-level
- [PCAP](https://pythoninstitute.org/pcap) - Associate
- [PCPP](https://pythoninstitute.org/pcpp) - Professional

---

# 🎉 Congratulations!

You've completed the **30 Days Python Mastery** program! 

By now, you should have:

- ✅ Solid understanding of Python fundamentals
- ✅ Knowledge of all major data structures
- ✅ Ability to write functions and classes
- ✅ Skills in file handling and error management
- ✅ Understanding of APIs and async programming
- ✅ Testing fundamentals

**What's Next?**

1. Build more projects
2. Contribute to open source
3. Learn a framework (Django, Flask, Pandas)
4. Practice data structures and algorithms
5. Prepare for interviews

**Keep Coding!** 🚀

---

*Last Updated: 2024*
*Created as part of 30 Days Python Mastery Program*
