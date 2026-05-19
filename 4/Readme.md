# Python Data Types Report

## Introduction

Python is a high-level programming language that supports different types of data. These data types are used to store values in variables. Python automatically identifies the type of data assigned to a variable. Data types help programmers organize and process information efficiently.

---

# Types of Data in Python

## 1. Integer (`int`)

Integer data types store whole numbers without decimal points.

Example values:

* 5
* 20
* -10

Integers are commonly used for counting and mathematical calculations.

---

## 2. String (`str`)

String data types store text or characters enclosed within quotation marks.

Example values:

* `"Hello World"`
* `"Apple"`

Strings are used to store names, messages, and sentences.

---

## 3. Boolean (`bool`)

Boolean data types store only two possible values:

* `True`
* `False`

These are mainly used in decision making and conditions.

---

## 4. Float (`float`)

Float data types store decimal numbers.

Example values:

* 20.5
* 3.14

Floats are used in calculations involving fractions or precise values.

---

## 5. Complex (`complex`)

Complex data types store complex numbers containing a real and imaginary part.

Example value:

* `1j`

Complex numbers are mainly used in advanced mathematics and engineering.

---

## 6. List (`list`)

Lists are ordered collections that can store multiple items.

Example:

* `["apple", "banana", "cherry"]`

Lists are changeable, meaning elements can be added or removed.

---

## 7. Tuple (`tuple`)

Tuples are ordered collections similar to lists but cannot be changed after creation.

Example:

* `("apple", "banana", "cherry")`

Tuples are used when data should remain constant.

---

## 8. Range (`range`)

The range data type represents a sequence of numbers.

Example:

* `range(0, 6)`

Ranges are mostly used in loops and iterations.

---

## 9. Dictionary (`dict`)

Dictionaries store data in key-value pairs.

Example:

* `{"name": "John", "age": 36}`

Dictionaries are useful for storing related information together.

---

## 10. Set (`set`)

Sets store multiple unique items.

Example:

* `{"apple", "banana", "cherry"}`

Sets do not allow duplicate values.

---

## 11. Frozen Set (`frozenset`)

A frozenset is similar to a set but cannot be modified after creation.

Example:

* `frozenset({"apple", "banana", "cherry"})`

It is used when fixed unique data is needed.

---

## 12. Bytes (`bytes`)

Bytes store binary data.

Example:

* `b"Hello"`

Bytes are commonly used in file handling and networking.

---

## 13. Bytearray (`bytearray`)

Bytearray stores binary data that can be modified.

Example:

* `bytearray(5)`

It is similar to bytes but changeable.

---

## 14. Memoryview (`memoryview`)

Memoryview allows access to the internal data of an object without copying it.

Example:

* `memoryview(bytes(5))`

It improves performance while handling large binary data.

---

## 15. None Type (`NoneType`)

The `NoneType` represents the absence of a value.

Example:

* `None`

It is used when a variable has no assigned value.

---

# Conclusion

Python provides many built-in data types for storing different kinds of information. Each data type has its own purpose and features. Understanding data types is important because they help programmers write efficient and organized programs. Python’s flexibility and automatic type detection make it easy to work with different forms of data.
