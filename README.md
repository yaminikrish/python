# 📘 Python Full Concepts - README

This document provides a comprehensive explanation of core Python programming concepts along with **examples** for each. It is designed for beginners and intermediate learners aiming to master Python.

---

## 📌 1. Variables

Variables are containers for storing data values. In Python, you don't need to declare the type of variable. Python automatically infers the type.

**Explanation:**
Variables are symbolic names that refer to data. Python uses dynamic typing, which means the type is inferred at runtime.

**Examples:**

```python
x = 5                # integer
name = "Alice"        # string
price = 12.5         # float
is_valid = True      # boolean
items = [1, 2, 3]    # list
```

---

## 📌 2. Data Types

Python has several built-in data types.

**Explanation:**
Data types determine what kind of value a variable holds. They help Python understand what operations are possible on that value.

**Common types:**

* Numeric: `int`, `float`, `complex`
* Text: `str`
* Boolean: `bool`
* Sequence: `list`, `tuple`, `range`
* Set: `set`, `frozenset`
* Mapping: `dict`
* Binary: `bytes`, `bytearray`, `memoryview`

**Examples:**

```python
x = 10            # int
y = 3.14          # float
z = "Hello"       # str
flag = False      # bool
lst = [1, 2, 3]   # list
tpl = (4, 5)      # tuple
dct = {'a': 1}    # dict
```

---

## 📌 3. Types of Print Statements

**Explanation:**
The `print()` function is used to display output to the screen.

**Examples:**

```python
print("Hello")
print("Name:", name)
print(f"Price is {price}")  # f-string for formatting
print("Hello", end=" ")
print("World")
```

---

## 📌 4. Operators

**Explanation:**
Operators are special symbols used to perform operations on variables and values.

**Types:**

* Arithmetic: `+`, `-`, `*`, `/`, `%`, `**`, `//`
* Comparison: `==`, `!=`, `>`, `<`, `>=`, `<=`
* Logical: `and`, `or`, `not`
* Bitwise: `&`, `|`, `^`, `~`, `<<`, `>>`
* Assignment: `=`, `+=`, `-=`, etc.

**Examples:**

```python
print(5 + 3)        # Arithmetic
print(10 > 5)       # Comparison
print(True and False) # Logical
a = 5
a += 2
print(a)
```

---

## 📌 5. Loops (for and while)

**Explanation:**
Loops are used for iterating over a sequence or executing a block of code repeatedly.

### 🔁 For Loop:

```python
for i in range(5):
    print(i)

for item in ["a", "b"]:
    print(item)
```

### 🔁 While Loop:

```python
i = 0
while i < 5:
    print(i)
    i += 1
```

---

## 📌 6. Control Statements

**Explanation:**
Control statements alter the flow of execution in loops and conditionals.

* `break` – Exit the loop early
* `continue` – Skip current iteration
* `pass` – Do nothing (placeholder)

**Examples:**

```python
for i in range(5):
    if i == 3:
        break
    print(i)

for i in range(5):
    if i == 2:
        continue
    print(i)

def func():
    pass
```

---

## 📌 7. Strings and Built-in Functions

**Explanation:**
Strings are sequences of Unicode characters. They are immutable.

**Functions:** `upper()`, `lower()`, `strip()`, `replace()`, `split()`, `find()`, `len()`

**Examples:**

```python
s = " Hello World "
print(s.upper())          # Convert to uppercase
print(s.strip())          # Remove whitespace
print(s.replace("Hello", "Hi"))
print(s.split())          # Split string into list
print(len(s))             # Get length
```

---

## 📌 8. Lists and Built-in Functions

**Explanation:**
Lists are ordered and mutable collections. You can change, add, and remove elements.

**Functions:** `append()`, `extend()`, `pop()`, `remove()`, `sort()`, `reverse()`, `index()`

**Examples:**

```python
lst = [1, 2, 3]
lst.append(4)       # Add element
lst.pop()           # Remove last
lst.remove(2)       # Remove by value
lst.sort()          # Sort list
print(lst)
```

---

## 📌 9. Tuples and Built-in Functions

**Explanation:**
Tuples are ordered and immutable collections. Used when data should not change.

**Functions:** `count()`, `index()`

**Examples:**

```python
tpl = (1, 2, 2, 3)
print(tpl.count(2))  # Count occurrences
print(tpl.index(3))  # Find index
```

---

## 📌 10. Dictionary and Built-in Functions

**Explanation:**
Dictionaries store key-value pairs. Keys must be unique and immutable.

**Functions:** `get()`, `keys()`, `values()`, `items()`, `update()`

**Examples:**

```python
d = {"a": 1, "b": 2}
print(d.get("a"))
print(d.keys())
print(d.values())
d.update({"c": 3})
print(d.items())
```

---


## ACKNOWLDEMENT

I would like to express my sincere gratitude to Kamal Sir, the Trainer and Managing Director of Vihara Tech, for his exceptional teaching, continuous guidance, and encouragement throughout the learning journey. This compilation of Python concepts would not have been possible without his mentorship.



## Author
K.YAMINI KRISHNA
yamini.kelam1@gmail.com
https://www.linkedin.com/in/yamini-krishna-445412367/


