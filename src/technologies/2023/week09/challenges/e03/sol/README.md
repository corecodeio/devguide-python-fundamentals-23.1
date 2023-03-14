<a href="https://www.core-code.io/">

![alt text](https://uploads-ssl.webflow.com/5eb2f56932c3562feab232e3/5f73550d00249e7e96c9f3de_Logo.png 'corecodeio')

</a>

<h1 align="center">Solution</h1>

# Creating a custom Module



## Solution 🏁
    
```python
# File: factorial.py

def factorial(n):
    if n == 0:
        return 1
    else:
        return n * factorial(n-1)
```


```python
# File: main.py

import factorial

num = int(input("Enter a number: "))
print("The factorial of", num, "is", factorial.factorial(num))

```

In this program, we created a custom module called factorial that defines a function to calculate the factorial of a number using recursion. We then imported the factorial module into a separate file called main.py, prompted the user to input a number, and used the factorial function from the factorial module to calculate the factorial of the number and print the result to the console.

## Video Solution 📹

[Video](https://youtu.be/YmhRIHYiAGA)