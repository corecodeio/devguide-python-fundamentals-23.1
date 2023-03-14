<a href="https://www.core-code.io/">

![alt text](https://uploads-ssl.webflow.com/5eb2f56932c3562feab232e3/5f73550d00249e7e96c9f3de_Logo.png 'corecodeio')

</a>

<h1 align="center">Solution</h1>

# Use a global variable



## Solution 🏁
    
```python
x = 5

def change_x():
    global x
    x = 10
    
change_x()
print(x)
```

In this program, we defined a global variable called `x` and a function called `change_x` that changes the value of `x` to 10 using the `global` keyword. We then called `change_x` to update the value of `x`, and printed the value of `x` to confirm that it was updated.

## Video Solution 📹

[Video](https://youtu.be/uWjR2eIQVLM)