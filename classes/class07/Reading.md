# Python Scope & the LEGB Rule: Resolving Names in Your Code

* Scope is a region in a program where a name can be used.
* There are four types of scopes in Python: local, enclosing, global, and built-in.
* The LEGB rule is a way of determining which scope to search for a name when it is used in a program.
* The LEGB rule stands for:
    * Local
    * Enclosing
    * Global
    * Built-in
* The local scope is the smallest scope and contains the names that are defined within a function.
* The enclosing scope is the next largest scope and contains the names that are defined in the enclosing function.
* The global scope is the next largest scope and contains the names that are defined at the top level of a module.
* The built-in scope is the largest scope and contains the names that are built into Python.
* When a name is used in a program, Python searches the scopes in the following order:
    1. Local scope
    2. Enclosing scope
    3. Global scope
    4. Built-in scope
* If a name is found in a scope, Python stops searching and uses that name.
* If a name is not found in any of the scopes, Python raises an error.

## Additional Information

* Variables that are defined in a local scope cannot be accessed from outside of that scope.
* Variables that are defined in an enclosing scope can be accessed from within the local scope.
* Variables that are defined in the global scope can be accessed from anywhere in the program.
* Variables that are defined in the built-in scope can be accessed from anywhere in the program, but it is not recommended to do so.

## References

* [Python Scope & the LEGB Rule: Resolving Names in Your Code](https://stackabuse.com/python-scope-legb-rule/)
