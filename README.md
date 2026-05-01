# Python

Explortion is innovation

The 10 modules at a glance:

1. Hello Python — variables, print, f-strings
2. Operators & input — math, logic, user input
3. Conditionals — if/elif/else, ternary
4. Loops — for, while, range, enumerate
5. Data Structures — lists, dicts, sets, comprehensions
6. Functions — def, return, *args, lambda
7. String Methods — the data cleaning toolkit
8. File Handling & Exceptions — try/except, with open()
9. OOP — classes, objects, inheritance
10. Full Program — everything combined into one real project


# 1

3 min

Absolute beginner

1. Hello, Python
   
Variables, print, comments, data types

print()

Outputs text to screen. Your first tool.

Variables
Labels that store values. No declaration needed.

Data types
int, float, str, bool — Python figures it out.

Comments
# This line is ignored by Python.

# Your first Python program print("Hello, World!") # Variables — no 'var' or 'let' needed name = "Vishvi" age = 21 is_student = True gpa = 9.1 print(f"Name: {name}, Age: {age}") # f-string = modern way print(type(name)) # <class 'str'>


# 2

3 min

Beginner

2. Operators & input()
Math, comparison, logical operators + user input

Arithmetic
+ - * / // % ** — // is floor div, ** is power.
    
Comparison

== != > < >= <= — returns True/False.

Logical

and, or, not — combine conditions.

input()

Reads user input. Always returns a string.

# Arithmetic print(10 // 3) # 3 (floor division) print(10 % 3) # 1 (remainder) print(2 ** 8) # 256 (power) # User input name = input("Enter your name: ") age = int(input("Enter age: ")) # Convert str → int # Logical print(age > 18 and name != "") # True/False


# 3

3 min

Beginner

3. Conditionals

if / elif / else — decision making
if / elif / else

Python uses indentation (4 spaces) — no curly braces.

Nested if

if inside if — use sparingly.

Ternary

value_if_true if condition else value_if_false

match (3.10+)

Like switch-case. Modern Python.

score = 78 if score >= 90: print("Grade: A") elif score >= 70: print("Grade: B") # This runs else: print("Grade: C or below") # Ternary — one-liner conditional result = "Pass" if score >= 50 else "Fail" print(result) # Pass
