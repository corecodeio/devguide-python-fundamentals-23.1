<a href="https://www.core-code.io/">

![alt text](https://uploads-ssl.webflow.com/5eb2f56932c3562feab232e3/5f73550d00249e7e96c9f3de_Logo.png 'corecodeio')

</a>

<h1 align="center">Solution</h1>

# Create a Try/Except where code is executed if no exception is raised and regardless of whether an exception is raised or not and specifically if an exception is raised

## Solution 🏁

```python

# create a simple function that takes a list and an index and returns the element at that index
def get_element_at_index(my_list, index):
    try:
        return my_list[index]
    except IndexError:
        print(f"IndexError: index {index} is out of range")
    else:
        print("No exception raised")
    finally:
        print("Finally block executed")

# test the function with a valid index
my_list = [1, 2, 3, 4, 5]
print(get_element_at_index(my_list, 2)) # output: 3
# prints "No exception raised" and "Finally block executed"

# test the function with an invalid index
print(get_element_at_index(my_list, 10)) # output: None
# prints "IndexError: index 10 is out of range" and "Finally block executed"
```

The code above demonstrates how to create a `try/except` block that includes a `finally` block and an `else` block. The `try` block contains the code that may raise an exception, while the `except` block handles the exception and prints an error message. The `else` block is used to execute code only if no exception is raised, and the `finally` block is used to execute code regardless of whether an exception is raised or not. This pattern is commonly used to ensure that certain cleanup code, such as closing a file or releasing a resource, is always executed, even if an exception occurs.

## Video Solution 📹

<iframe width="560" height="315" src="https://www.youtube.com/embed/DM751zfjneQ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
