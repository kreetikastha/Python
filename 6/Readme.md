# Python String Report

## Introduction

Strings are one of the most commonly used data types in Python. A string is a sequence of characters enclosed within single quotes (`' '`) or double quotes (`" "`). Strings are used to store and manipulate text data such as names, messages, and sentences.

Python provides many features and operations for working with strings, including accessing characters, looping through text, checking string content, and creating multiline strings.

---

# String Creation in Python

Strings can be created using single or double quotation marks.

Examples:

* `"Hello"`
* `'Hello'`

Both methods produce the same result.

---

# Using Quotes Inside Strings

Python allows quotes inside strings by using different quotation marks.

Examples:

* `"It's alright"`
* `"He is called 'Johnny'"`
* `'He is called "Johnny"'`

This helps in writing sentences containing quotation marks without errors.

---

# Assigning Strings to Variables

A string can be stored in a variable.

Example:

* `a = "Hello"`

The variable stores the text value and can be printed or used later in the program.

---

# Multiline Strings

Python supports multiline strings using triple quotation marks.

Example:

```python
"""Text"""
```

or

```python
'''Text'''
```

Features:

* Allows writing long paragraphs
* Maintains line breaks
* Useful for documentation and large text blocks

---

# Accessing Characters in a String

Each character in a string has an index number. Indexing starts from `0`.

Example:

* In `"Hello, World!"`
* Index `1` gives `e`

Features:

* Used to access specific characters
* Helpful in string manipulation

---

# Looping Through a String

Strings can be traversed using loops.

Example:

* Iterating through `"banana"` prints each character separately.

Features:

* Useful for processing each character individually
* Commonly used in text analysis

---

# String Length

Python provides the `len()` function to determine the number of characters in a string.

Example:

* `"Hello, World!"` has length `13`

Features:

* Counts all characters including spaces and punctuation
* Useful for validation and analysis

---

# Checking Strings

Python allows checking whether a word or phrase exists inside a string using:

* `in`
* `not in`

---

## Using `in`

The `in` keyword returns `True` if the specified text exists in the string.

Example:

* `"free" in txt`

Features:

* Used for searching text
* Returns Boolean values (`True` or `False`)

---

## Using `not in`

The `not in` keyword returns `True` if the specified text does not exist in the string.

Example:

* `"expensive" not in txt`

Features:

* Checks absence of text
* Useful in conditions and validations

---

# Conditional Statements with Strings

String checks can be used with `if` statements.

Examples:

* Printing a message if `"free"` is present
* Printing a message if `"expensive"` is not present

Features:

* Helps in decision-making
* Widely used in applications and data processing

---

# Type Conversion

Python can convert values into strings using the `str()` function.

Examples:

* `str("s1")`
* `str(2)`
* `str(3.0)`

Features:

* Converts numbers into text format
* Useful for displaying data

---

# Float Conversion

Python also converts values into floating-point numbers using the `float()` function.

Examples:

* `float(1)`
* `float("3")`
* `float("4.2")`

Features:

* Converts integers and strings into decimal numbers
* Used in mathematical calculations

---

# Conclusion

Strings are an essential part of Python programming used for storing and handling textual data. Python provides many built-in features for string creation, manipulation, searching, and formatting. Understanding strings and their operations helps programmers develop efficient applications involving text processing, validation, and user interaction.
