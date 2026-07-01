# Data Types

## What is it?

A data type defines the kind of value that a variable stores and determines the operations that it can perform. For example, text and numbers are typically stored using different data types because they are used in different ways.

---

## Why is it Important?

Python needs to know what kind of data it is working with.

For example:

- Numbers can be used in mathematical calculations
- Text can be combined and displayed
- Some operations are only valid for specific data types

Understanding data types helps prevent errors and allows programs to behave as expected.

---

## How do I use it?

### String (`str`)

A string stores text

```python
name = "Jack"
```

Strings are enclosed in quotation marks

---

### Integer (`int`)

An integer stores a whole number

```python
age = 24
```

Integers can be used in mathematical calculations

---

### Type Conversion

The `input()` function always returns a string

If numerical calculations are required, the value must first be converted

```python
age = int(input("How old are you? "))
```

Likewise, numbers can be converted into strings when building text

```python
message = "Age: " + str(age)
```

---

## Key Takeaways

- Every value in Python has a data type
- `input()` always returns a string
- Strings store text
- Integers store whole numbers
- Values can be converted between compatible data types

---

## Related Concepts

- Variables
- Python Interpreter
- Source Code

---

## Current Scope

This page currently covers:

- Strings (`str`)
- Integers (`int`)
- Basic type conversion
- `input()`

Future topics to learn:

- Floating-point numbers (`float`)
- Boolean values (`bool`)
- Lists
- Dictionaries
- Tuples
- Sets
- Type checking with `type()`

---

## Further Reading

### Official Documentation

- https://docs.python.org/3/library/stdtypes.html

### Additional Reading

- https://docs.python.org/3/tutorial/introduction.html