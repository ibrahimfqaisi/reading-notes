## Q1: What is the basic syntax of Python list comprehension, and how does it differ from using a for loop to create a list? Provide an example of a list comprehension that squares the elements in a given list of integers.

 The basic syntax of Python list comprehension is as follows:
``` 
new_list = [expression for item in iterable]
```
 List comprehension allows you to create a new list by applying an expression to each item in the iterable.

 It differs from using a for loop to create a list by providing a more concise and readable way to generate lists in a single line of code.

 Here's an example of a list comprehension that squares the elements in a given list of integers:
```
numbers = [1, 2, 3, 4, 5]
squared_numbers = [x**2 for x in numbers]
```

## Q2: What is a decorator in Python?

In Python, a decorator is a way to modify the behavior of a function without changing its source code.

Decorators allow you to wrap a function with another function, adding functionality before and/or after the wrapped function executes.


## Q3: Explain the concept of decorators in Python. How do they work, and what are some common use cases for them? Provide an example of a simple decorator function from the reading.

Decorators in Python are a way to enhance the functionality of functions without modifying their code directly.

They work by using the @decorator syntax, where the decorator replaces the original function with the decorated version.

Some common use cases for decorators include logging, authentication, performance monitoring, and adding additional functionality to functions.
```
def uppercase_decorator(func):
    def wrapper():
        original_result = func()
        modified_result = original_result.upper()
        return modified_result
    return wrapper

@uppercase_decorator
def say_hello():
    return "hello"

print(say_hello())
```