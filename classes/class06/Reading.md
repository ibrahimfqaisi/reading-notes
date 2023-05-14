# reading

## Random Module

### Python's random module includes several functions for generating random numbers and sequences. Here are some of the most commonly used functions:
- #### randint(a, b) : 
Returns a random integer between the two specified numbers a and b (inclusive).

### random(): 
Returns a random float number between 0 and 1 (excluding 1). It generates pseudo-random numbers.

### choice(seq): 
Returns a random element from the given sequence (string, list, tuple, etc.).

### randrange([start], stop[, step]):
 Returns a randomly selected element from the range created by the start, stop, and step arguments. It's similar to Python's built-in range() function, but returns a random value from the specified range.

### shuffle(lst):
 Shuffles the elements in the given list in-place, changing the order of the elements randomly.


## Risk analysis :
Risk analysis is important in software testing to identify potential issues and prioritize testing. Common risks include new hardware and technology. To mitigate risks, allocate resources to high-risk areas and identify risk indicators. Identify different types of risks, assess them programmatically, and take three steps in risk analysis: 
- searching for risks
- analyzing impact
- identifying solutions.

## Test coverage :
User

Coverage analysis is useful for identifying untested portions of your code. It's recommended to periodically run coverage tools to examine these areas.

## how to calculate Big O notation for an algorithm:

- Identify the operation that takes the most time in the algorithm.
- Determine how many times that operation will be executed in the worst-case scenario.
- Express the number of operations in terms of the input size, n.
-  Simplify the expression by removing any constants or lower-order terms.