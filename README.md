# Python-DataTypes
A Simple Code for understanding the different data types in Python.
# Python Data Types

This Python script demonstrates the use of various data types in Python and how to check their types using the `type()` function.

## Requirements

- Python (version 3.x or higher) installed on your machine.

## Data Types Covered

1. **Integer (int)**: Represents whole numbers (positive, negative, or zero).
2. **Floating Point (float)**: Represents decimal numbers.
3. **String (str)**: Represents sequences of characters.
4. **List (list)**: Represents an ordered collection of items.
5. **Tuple (tuple)**: Represents an immutable ordered collection of items.
6. **Dictionary (dict)**: Represents key-value pairs.
7. **Set (set)**: Represents an unordered collection of unique items.

## How to Run

1. Download or clone this repository.
2. Open a terminal or command prompt.
3. Navigate to the directory where the script is located.
4. Run the Python script using the following command:

    ```bash
    python data_types.py
    ```

   If you're using Python 3, the command might be:

    ```bash
    python3 data_types.py
    ```

## Code Explanation

```python
# Integer
a = 10
print(type(a))  # <class 'int'>

# Floating point
b = 3.14
print(type(b))  # <class 'float'>

# String
c = "Hello"
print(type(c))  # <class 'str'>

# List
d = [1, 2, 3]
print(type(d))  # <class 'list'>

# Tuple
e = (4, 5, 6)
print(type(e))  # <class 'tuple'>

# Dictionary
f = {"name": "Ajay", "age": 25}
print(type(f))  # <class 'dict'>

# Set
g = {"apple", "orange", "banana"}
print(type(g))  # <class 'set'>
