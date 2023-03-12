<a href="https://www.core-code.io/">

![alt text](https://uploads-ssl.webflow.com/5eb2f56932c3562feab232e3/5f73550d00249e7e96c9f3de_Logo.png 'corecodeio')

</a>

<h1 align="center">Solution</h1>

# Type Exception with Non-String Argument

## Solution 🏁

```python
# We will define a function that expects a string argument, and we will use the `isinstance()` function to check if the argument is a string. If it is not a string, we will raise a `TypeError` exception.

def greet(name):
    """
    This function takes a string argument `name` and prints a greeting message.
    """
    if not isinstance(name, str):
        raise TypeError("Name must be a string")
    print("Hello, " + name + "!")
    
# Code Output:
    
greet("John") # Hello, John!
greet(123) # TypeError: Name must be a string
```

# In this exercise, we learned how to use the `isinstance()` function to check the type of an argument passed to a function. We used this to raise a `TypeError` exception when a non-string argument is passed to our `greet()` function. This helps to ensure that our code is robust and handles unexpected inputs gracefully. 

## Video Solution 📹

[Counting Even and Odd Numbers](https://edpuzzle.com/assignments/6386b321c511ef40e3f4fb07/watch)
