# Python_primary_built-in-data_structures
Python Built-In Data Structures Tutorial for Absolute Beginners

## Numbers in Python
In Python, numbers are a fundamental data type and can be categorized into several types:

- Integers: These are whole numbers without a fractional component, such as `-2, 0, and 42`. Python supports arbitrarily large integers, limited only by the available memory.

- Floating-Point Numbers: Also known as "floats," these numbers have a decimal point, such as `3.14, 0.001, and -2.5`. They are used to represent real numbers and are stored using double-precision (64-bit) format.

- Complex Numbers: Python also supports complex numbers, which have a real and an imaginary part. They are written in the form `a + bj`, where a is the real part and b is the imaginary part.

Python provides built-in functions for numerical operations and allows for the conversion between different numerical types. Additionally, Python includes libraries like math and decimal for advanced mathematical functions and precise decimal arithmetic, respectively.

## Arithmetic operators in Python
Arithmetic operators in Python are used to perform mathematical operations on numerical values. Here is a brief overview of each operator:

- Addition `(+)`: Adds two numbers.
  Example: `3 + 2` results in 5.
  
- Subtraction `(-)`: Subtracts the second number from the first.
  Example: `5 - 2` results in 3.
  
- Multiplication `(*)`: Multiplies two numbers.
  Example: `4 * 3` results in 12.
  
- Division `(/)`: Divides the first number by the second, resulting in a float.
  Example: `10 / 2` results in 5.0.
  
- Floor Division `(//)`: Divides the first number by the second and rounds down to the nearest integer.
  Example: `7 // 2` results in 3.
  
- Modulus `(%)`: Returns the remainder of the division of the first number by the second.
  Example: `7 % 3` results in 1.
  
- Exponentiation `(**)`: Raises the first number to the power of the second number.
  Example: `2 ** 3` results in 8.
  
These operators are essential for performing basic arithmetic calculations in Python.

## Lists in Python

A list in Python is an ordered, mutable collection of items that can hold a variety of data types, including other lists. Lists are created using square brackets, with elements separated by commas.

### List Methods
- append: Adds an element to the end of the list.

- insert: Inserts an element at a specified position in the list.

- remove: Removes the first occurrence of a specified element from the list.

- pop: Removes and returns the element at a specified position (or the last element if no position is specified).

- index: Returns the index of the first occurrence of a specified element in the list.

- count: Returns the number of times a specified element appears in the list.

- sort: Sorts the elements of the list in ascending (or descending) order.

- reverse: Reverses the order of elements in the list.

- extend: Adds all elements of an iterable (e.g., another list) to the end of the list.

- copy: Returns a shallow copy of the list.

- clear: Removes all elements from the list, resulting in an empty list.

### Other List Operations
- len: Returns the number of elements in the list.

- slicing: Allows accessing a subset of the list using a range of indices, specified in the format [start:stop:step]. This can be used to extract, modify, or replace parts of the list.

These methods and operations provide powerful tools for managing and manipulating lists in Python, making them a versatile data structure.

## Tuples in Python

A tuple in Python is an ordered, immutable collection of items, which can hold a variety of data types. Tuples are created using parentheses, with elements separated by commas. Once created, the elements of a tuple cannot be changed, making tuples useful for storing data that should not be modified.

### Tuple Methods and Operations
- len: Returns the number of elements in the tuple.

- count: Returns the number of times a specified element appears in the tuple.

- index: Returns the index of the first occurrence of a specified element in the tuple.

- concatenation: Combines two or more tuples to create a new tuple.

- repetition: Creates a new tuple by repeating the elements of the original tuple a specified number of times.

- sorted: Returns a new list containing all elements from the tuple, sorted in ascending order.

- max: Returns the largest element in the tuple.

- min: Returns the smallest element in the tuple.

- reversed: Returns an iterator that accesses the tuple elements in reverse order.

- in: Checks if a specified element is present in the tuple, returning True if it is and False otherwise.

- not in: Checks if a specified element is not present in the tuple, returning True if it is not and False otherwise.

These methods and operations allow you to work with tuples effectively, despite their immutability, providing useful ways to access, analyze, and manipulate tuple data in Python.
