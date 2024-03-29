<a href="https://www.core-code.io/">

![alt text](https://uploads-ssl.webflow.com/5eb2f56932c3562feab232e3/5f73550d00249e7e96c9f3de_Logo.png 'corecodeio')

</a>

<h1 align="center">Solution</h1>

# Nested Functions



## Solution 🏁
    
```python
def outer():
    x = 5
    def inner():
        nonlocal x
        print(x)
    inner()
    x = 10
    inner()
    
outer() 
```

In this program, we defined a function called `outer` that creates a variable called `x` and a nested function called `inner` that prints the value of `x`. We then called `inner` to print the value of `x`, which was set to 5.

We then updated the value of `x` to 10 and called `inner` again to confirm that the value of `x` was updated. We used the nonlocal keyword to indicate that we were updating the value of `x` in the `outer` function, not creating a new variable called `x` in the `inner` function.

## Video Solution 📹

<iframe width="560" height="315" src="https://www.youtube.com/embed/dRqEua7Wy6g" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>