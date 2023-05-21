## List Comprehension

**What is a list comprehension?**  
A list comprehension is a concise way to create a list in Python. It is an alternative to using a for loop.

**Syntax**  
The syntax for a list comprehension is as follows:

```python
[expression for item in iterable]
```
The expression is evaluated for each item in the iterable, and the results are stored in the list.

### Example
The following example creates a list of squares of numbers from 1 to 10:
```python
squares = [x ** 2 for x in range(1, 11)]
```

This is equivalent to the following for loop:

```python
squares = [x ** 2 for x in range(1, 11)]
```

### Advantages
List comprehensions have several advantages over for loops:

- They are more concise and easier to read.
- They can be used to create more complex lists.
- They can be used to filter lists.

### Disadvantages

List comprehensions can be more difficult to debug than for loops.
