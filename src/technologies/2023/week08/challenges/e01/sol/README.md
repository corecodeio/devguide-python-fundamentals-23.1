<a href="https://www.core-code.io/">

![alt text](https://uploads-ssl.webflow.com/5eb2f56932c3562feab232e3/5f73550d00249e7e96c9f3de_Logo.png 'corecodeio')

</a>

<h1 align="center">Solution</h1>

# Given a list of zip codes, sort them in ascending order using the selection sort algorithm.



## Solution 🏁
    
```python
input = ["12345", "1234", "123456", "123", "1234567"]

def selection_sort(input):
    for i in range(len(input)):
        min_index = i
        for j in range(i + 1, len(input)):
            if len(input[min_index]) > len(input[j]):
                min_index = j
        input[i], input[min_index] = input[min_index], input[i]
    return input

output = selection_sort(input)

print(output)
```

This code defines a list of strings called 'input', and then defines a function called 'selection_sort' which implements the selection sort algorithm to sort the strings in the input list in ascending order based on their length. The function iterates over each element of the list, and compares its length with the lengths of the remaining elements to find the minimum value. It then swaps the minimum value with the current element. The sorted list is returned as the output of the function. Finally, the sorted list is printed out to the console by calling the selection_sort function on the input list and assigning the result to a variable called 'output', which is then printed out.

## Video Solution 📹

[Video](https://youtu.be/U_CrBMOJrb0)