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
    `greeting = "Hello, {}!".format(name)`
    ```
- **F-Strings (Python 3.6+):**  
    Embed expressions directly in string literals.
    
```python
    `greeting = f"Hello, {name}!"
```