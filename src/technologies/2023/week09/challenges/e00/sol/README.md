<a href="https://www.core-code.io/">

![alt text](https://uploads-ssl.webflow.com/5eb2f56932c3562feab232e3/5f73550d00249e7e96c9f3de_Logo.png 'corecodeio')

</a>

<h1 align="center">Solution</h1>

# Create an iterator to loop through list of names

Write a program that creates an iterator to loop through a list of names and prints each name in uppercase. Use the iter function to create the iterator and the next function to retrieve each value from the iterator.

## Solution 🏁
    
```python
names = ["Alice", "Bob", "Charlie", "David", "Emily"]
name_iter = iter(names)
while True:
    try:
        name = next(name_iter)
        print(name.upper())
    except StopIteration:
        break

```

In this program, we created an iterator called `name_iter` by calling the iter function on a list of names. We then used a `while` loop to call the `next` function on the iterator to retrieve each name, and printed it in uppercase using the `upper` method. We used a `try` and `except` block to catch the `StopIteration` exception, which is raised when the iterator reaches the end of the list.

## Video Solution 📹

<iframe width="560" height="315" src="https://www.youtube.com/embed/pxnpLypu1GY" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>