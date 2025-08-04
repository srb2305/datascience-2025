
# Python Basics - Class 1 Notes

This document covers the **basics of Python programming** including variables, operators, conditional statements, and loops with examples.

---

## 1. Introduction to Python
- Python is an easy-to-learn, high-level programming language.
- It is widely used in Data Science, AI/ML, Web Development, etc.

---

## 2. Variables in Python
Variables are used to store data.

### Example:
```python
name = "Srb IT Solution"
age = 25
price = 99.99
```

---

## 3. Data Types
| Data Type | Example |
|-----------|--------:|
| Integer   | 10 |
| Float     | 10.5 |
| String    | "Hello" |
| Boolean   | True / False |

---

## 4. Operators in Python
| Operator Type | Example |
|---------------|--------:|
| Arithmetic (+, -, *, /, %) | a + b |
| Assignment (=, +=, -=) | a += 5 |
| Comparison (==, !=, >, <) | a > b |
| Logical (and, or, not) | a > 10 and b < 5 |

### Example:
```python
a = 10
b = 5
print(a + b)  # Output: 15
print(a > b)  # Output: True
```

---

## 5. Conditional Statements (if, elif, else)
### Example:
```python
x = 20

if x > 20:
    print("Greater than 20")
elif x == 20:
    print("Equal to 20")
else:
    print("Less than 20")
```

---

## 6. Loops in Python

### a) For Loop
```python
for i in range(1, 6):
    print(i)
# Output: 1 2 3 4 5
```

### Example 1: Print Even Numbers till 10
```python
for i in range(2, 11, 2):
    print(i)
# Output: 2 4 6 8 10
```

### Example 2: Loop with Steps (Decrement from 10 to 0)
```python
for i in range(10, -1, -1):
    print(i)
# Output: 10 9 8 7 6 5 4 3 2 1 0
```

### Example 3: Iterate through List (Array)
```python
fruits = ["Apple", "Orange", "Banana"]

for fruit in fruits:
    print(fruit)
# Output:
# Apple
# Orange
# Banana
```

### b) While Loop
```python
count = 1
while count <= 5:
    print(count)
    count += 1
```

---

## 7. Example Program
```python
# Program to check even or odd
num = int(input("Enter a number: "))

if num % 2 == 0:
    print("Even Number")
else:
    print("Odd Number")
```
