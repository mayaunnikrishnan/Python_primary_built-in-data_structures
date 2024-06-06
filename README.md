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

## Set in python

A set in Python is an unordered collection of unique elements. Sets are commonly used to perform mathematical operations like union, intersection, difference, and symmetric difference. Key characteristics of sets include uniqueness of elements and unordered storage.

- Set Creation: 
Sets can be created using curly braces `{}` or the `set()` function. Duplicate elements are automatically removed, and the resulting set contains only unique elements.

- Add: The `add()` method adds a single element to a set. If the element is already present, the set remains unchanged.

- Remove: The `remove()` method removes a specified element from the set. If the element is not found, a KeyError is raised.

- Discard: Similar to `remove()`, but does not raise an error if the element is not present in the set.

- Pop: Removes and returns an arbitrary element from the set. This method is useful when the specific element to remove is not important.

- Clear: Removes all elements from the set, leaving an empty set.

### Set Operations
Sets support various operations to manipulate their contents efficiently:

- Union: Combines elements from two or more sets, ensuring uniqueness of elements in the resulting set.

- Update: Adds elements from another set or iterable to the current set.

- Intersection: Finds elements common to two or more sets.

- Intersection Update: Updates the set, retaining only elements found in both the set and other sets.

- Difference: Finds elements present in one set but not in another.

- Difference Update: Updates the set, removing elements found in other sets.

- Symmetric Difference: Finds elements present in either set, but not in both.

- Symmetric Difference Update: Updates the set, keeping only elements found in either set, but not in both.

### Subset and Superset Checks
Sets can be compared to check for containment:

- Issubset: Checks if one set is contained within another set. Returns True if all elements of the first set are present in the second set.

- Issuperset: Checks if one set contains all elements of another set. Returns True if the first set contains all elements of the second set.

These operations are handy for verifying relationships between sets, such as whether one set is a subset or superset of another. They provide useful functionality for set comparison and analysis.

## String in Python
A string in Python is a sequence of characters enclosed within single quotes `(' ')`, double quotes` (" ")`, or triple quotes `(''' ''' or """ """)`. Strings are immutable, meaning their contents cannot be changed after they are created. They are used to store and manipulate text.

### String Functions
- `len()`:

Returns the length of a string, i.e., the number of characters it contains.
- `str.lower()`:

Converts all uppercase characters in a string to lowercase.
- `str.upper()`:

Converts all lowercase characters in a string to uppercase.
- `str.strip()`:

Removes leading and trailing whitespace from a string.
- `str.replace(old, new)`:

Replaces all occurrences of the substring old with the substring new in a string.
- `str.split(separator)`:

Splits a string into a list of substrings based on the specified separator. If no separator is specified, it splits by whitespace.
- `str.join(iterable)`:

Joins the elements of an iterable (e.g., list or tuple) into a single string, with the string acting as a separator.
- `str.find(sub)`:

Returns the lowest index of the substring sub if it is found in the string. Returns -1 if the substring is not found.
- `str.startswith(prefix)`:

Returns True if the string starts with the specified prefix, otherwise returns False.
- `str.endswith(suffix)`:

Returns True if the string ends with the specified suffix, otherwise returns False.
### String Check Methods
- `str.isnumeric()`:

Returns True if all characters in the string are numeric characters.
- `str.isdigit()`:

Returns True if all characters in the string are digits.
- `str.isdecimal()`:

Returns True if all characters in the string are decimal characters.
- `str.isalpha()`:

Returns True if all characters in the string are alphabetic characters.
- `str.isalnum()`:

Returns True if all characters in the string are alphanumeric (either letters or numbers).
- `str.isspace()`:

Returns True if all characters in the string are whitespace characters.
- `str.islower()`:

Returns True if all cased characters in the string are lowercase.
- `str.isupper()`:

Returns True if all cased characters in the string are uppercase.
- `str.istitle()`:

Returns True if the string is titlecased, meaning each word starts with an uppercase letter followed by lowercase letters.
- `str.isidentifier()`:

Returns True if the string is a valid Python identifier, which can be used as a variable name.


## Dictionary in Python
A dictionary in Python is an unordered, mutable collection of key-value pairs. Keys must be unique and immutable, while values can be of any data type.

- Creating a Dictionary : 
  Dictionaries can be created using curly braces `{}` with key-value pairs or by using the `dict()` constructor.

- Accessing Values : 
  Values are accessed using their corresponding keys placed inside square brackets.

- Adding or Modifying Key-Value Pairs : 
  New key-value pairs can be added, and existing values can be modified by assigning a value to a key.

- del Statement : 
  The del statement deletes a specific key-value pair from the dictionary using the key.

- `pop()` Method : 
  The `pop()` method removes a key-value pair and returns the value associated with the specified key.

- Checking Key Existence : 
  The in keyword checks if a key exists in the dictionary, returning True if present and False otherwise.

- Keys, Values, Items : 
    - `keys()`: Returns a view object with all keys in the dictionary.
    - `values()`: Returns a view object with all values in the dictionary.
    - `items()`: Returns a view object with all key-value pairs as tuples.
- Copying a Dictionary : 
  The `copy()` method creates a shallow copy of the dictionary.

- Clearing a Dictionary : 
  The `clear()` method removes all key-value pairs from the dictionary.

- Getting a Value with Default : 
  The `get()` method retrieves the value for a specified key, returning a default value if the key is not found.

- Updating a Dictionary : 
  The `update()` method updates the dictionary with key-value pairs from another dictionary or an iterable of key-value pairs.

- Dictionary Size : 
  The `len()` function returns the number of key-value pairs in the dictionary.

- Converting Lists to Dictionaries : 
  Lists can be converted to dictionaries using the `zip()` function to pair elements as key-value pairs or by using dictionary comprehensions.


  ## Type Conversion in Python
Type conversion, or type casting, is the process of converting a value from one data type to another. Python provides built-in functions for explicit type conversion.
### Type conversion methods within the same data types in Python:

- Float to Integer :: 
`int()`: Converts a float to an integer by truncating the decimal part.

- String to Integer :: 
`int()`: Converts a string representation of a number to an integer. The string must contain a valid integer representation.

- Integer to Float :: 
`float()`: Converts an integer to a float.

- String to Float :: 
`float()`: Converts a string representation of a number to a float. The string must contain a valid float representation.

### Type conversion methods within different data structures in Python:

- Integer to String :: 
`str()`: Converts an integer to a string.

- Float to String :: 
`str()`: Converts a float to a string.

- Integer to Boolean :: 
`bool()`: Converts an integer to a boolean. Zero is converted to False, and any non-zero integer is converted to True.

- String to Boolean :: 
`bool()`: Converts a string to a boolean. An empty string is converted to False, while any non-empty string is converted to True.

- Tuple to List :: 
`list()`: Converts a tuple to a list.

- String to List :: 
`list()`: Converts a string to a list of characters.

- Set to List :: 
`list()`: Converts a set to a list.

- List to Tuple :: 
`tuple()`: Converts a list to a tuple.

- String to Tuple :: 
`tuple()`: Converts a string to a tuple of characters.

- Set to Tuple :: 
`tuple()`: Converts a set to a tuple.

- List to Set :: 
  `set()`: Converts a list to a set, removing duplicate elements.
  
- Tuple to Set :: 
`set()`: Converts a tuple to a set, removing duplicate elements.

- String to Set :: 
`set()`: Converts a string to a set of characters, removing duplicates.

- List to String :: 
`join()`: Converts a list of strings to a single string by concatenating the list elements with a specified separator.

- Tuple to String :: 
`join()`: Converts a tuple of strings to a single string by concatenating the tuple elements with a specified separator.

- Set to String :: 
`join()`: Converts a set of strings to a single string by concatenating the set elements with a specified separator. The order of elements in the resulting string is arbitrary due to the unordered nature of sets.

