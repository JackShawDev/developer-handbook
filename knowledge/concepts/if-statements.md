# If Statements

## What is it?

An `if` statement allows a program to make decisions. It evaluates a Boolean value and executes different code depending on whether the condition is `True` or `False`.

---

## Why is it Important?

Without decision making, every program would execute exactly the same instructions every time, `if` statements allow software to respond to user input and changing conditions.

---

## How do I use it?

```python
age = 24

if age >= 18:
    print("Access granted.")
else:
    print("Access denied.")
```

Python first evaluates the condition

If the condition is `True`, the indented block executes

If the condition is `False`, Python skips to the `else` block

---

### Multiple Conditions

Python provides `elif` ("else if") for additional conditions

```python
if age < 5:
    print("Free")
elif age <= 15:
    print("£5")
else:
    print("£10")
```

Only one branch of an `if` / `elif` / `else` chain executes

---

## Key Takeaways

- `if` evaluates a Boolean condition
- `else` handles every remaining case
- `elif` allows additional conditions
- Indentation determines which code belongs to each branch

---

## Related Concepts

- Boolean
- Comparison Operators
- Variables

---

## Current Scope

This page currently covers:

- `if`
- `elif`
- `else`
- Basic decision making

Future topics to learn:

- Nested `if` statements
- Complex conditions
- Pattern matching

---

## Further Reading

### Official Documentation

https://docs.python.org/3/tutorial/controlflow.html