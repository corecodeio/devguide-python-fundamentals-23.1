<a href="https://www.core-code.io/">

![alt text](https://uploads-ssl.webflow.com/5eb2f56932c3562feab232e3/5f73550d00249e7e96c9f3de_Logo.png 'corecodeio')

</a>

<h1 align="center">Solution</h1>

# Sort a list of tuples based on multiple keys using Python's built-in sorted() function.



## Solution 🏁
    
```python
input = [('a', 1), ('b', 2), ('c', 3), ('d', 4), ('e', 5)]
output = sorted(input, key=lambda x: x[1]) # [('a', 1), ('b', 2), ('c', 3), ('d', 4), ('e', 5)]
print(output)

```

This code sorts a list of tuples input based on the second element of each tuple. The sorted function is used to sort the list, and the key argument is set to a lambda function that extracts the second element of each tuple for use in the sorting process. The resulting sorted list is assigned to the variable output, which is then printed to the console. The output of this code would be a sorted list of tuples where the tuples are sorted in ascending order based on their second element.

## Video Solution 📹

[Counting Even and Odd Numbers](https://edpuzzle.com/assignments/6386b321c511ef40e3f4fb07/watch)