---
title: Python Basics & Syntax
tags: [python, basics, syntax, documentation]
---

# Python Basics & Syntax

This document outlines the fundamental elements of Python syntax in a point-by-point format.

---

## 1. Python Environment

- **Interactive Shell (REPL):**
  - Use for quick experiments and testing code snippets.
- **Script Files:**
  - Save code in files with a `.py` extension.
- **Integrated Development Environments (IDEs):**
  - Examples: VSCode, PyCharm, etc.

---

## 2. Basic Syntax

- **Comments:**
  - *Single-line Comments:*  
    Use the hash symbol (`#`) to write comments.
    ```python
    # This is a single-line comment
    ```
  - *Multi-line Comments / Docstrings:*  
    Enclose text within triple quotes (`""" ... """`) for multi-line comments or function documentation.
    ```python
    """
    This is a multi-line comment or docstring.
    It can span multiple lines.
    """
    ```

- **Indentation:**
  - Python uses indentation to define code blocks.
  - Standard indentation is 4 spaces per level.
  - Consistent indentation is critical for proper code execution.
    ```python
    if True:
        print("This block is indented")
    ```

- **Variables and Data Types:**
  - Variables are dynamically typed.
  - Common data types:
    - **Numbers:** `int`, `float`, `complex`
    - **Strings:** `str`
    - **Booleans:** `bool`
    - **Collections:** `list`, `tuple`, `set`, `dict`
    ```python
    x = 10          # int
    pi = 3.14       # float
    name = "Alice"  # string
    is_valid = True # boolean
    ```

---

## 3. String Formatting

- **Concatenation:**  
  Use the `+` operator to join strings.
```python
	greeting = "Hello, " + name
```
- **`str.format()` Method:**  
    Insert variables into strings using placeholders.
```python
    greeting = "Hello, {}!".format(name)`
    ```
- **F-Strings (Python 3.6+):**  
    Embed expressions directly in string literals.
    
```python
    greeting = f"Hello, {name}!"
```

---

## 4. Operators

- **Arithmetic Operators:**
    
    - Addition: `+`
        
    - Subtraction: `-`
        
    - Multiplication: `*`
        
    - Division: `/`
        
    - Floor Division: `//`
        
    - Modulus: `%`
        
    - Exponentiation: `**`
        
```python
    a = 10
	b = 3
	print(a + b)  # Outputs: 13
	print(a / b)  # Outputs: 3.333...
	print(a // b) # Outputs: 3
	print(a % b)  # Outputs: 1
	print(a ** b) # Outputs: 1000

```
- **Comparison Operators:**
    
    - Equal: ` ==`
        
    - Not equal: `!=`
        
    - Less than: `<`
        
    - Greater than: `>`
        
    - Less than or equal: `<=`
        
    - Greater than or equal: `>=`
        
- **Logical Operators:**
    
    - `and`, `or`, `not`
        
- **Assignment Operators:**
    
    - Basic assignment: `a = a`
        
    - Compound assignments: `+=`, `-=`, etc.
        

---

## 5. Control Structures
- **Conditional Statements:**
    
    - Use `if`, `elif`, and `else` to control code flow.
        
```python
	if x > 0:
		print("Positive")
	elif x == 0:
		print("Zero")
	else:
		print("Negative")`
```
    
- **Loops:**
    
    - _For Loops:_  
        Iterate over sequences or ranges.
        
        ```python
	for i in range(5):
		print(i)`
	```
    - _While Loops:_  
        Execute as long as a condition is true.
        
```python
	count = 0
	while count < 5:
		print(count)
		count += 1`
```        

---

## 6. Functions

- **Defining Functions:**
    
    - Use the `def` keyword to create functions.
        
    
```python
	    def greet(person):
			"""Return a greeting message."""
			return f"Hello, {person}!"
		print(greet("Alice"))`
```
- **Docstrings:**
    
    - Use triple quotes to document the function’s purpose, parameters, and return value.
        

---

## 7. Modules and Imports

- **Modules:**
    
    - Organize code into reusable modules.
        
- **Importing:**
    
    - Use `import` to include modules in your script.
        
    

```python
    import math
	print(math.sqrt(16))  # Outputs: 4.0`
```

---

> [!tip] **Practice Tip:**  
> Experiment with these concepts in a Python interpreter or script to build familiarity with the language.