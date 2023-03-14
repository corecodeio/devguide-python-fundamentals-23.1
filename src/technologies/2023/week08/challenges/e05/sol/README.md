<a href="https://www.core-code.io/">

![alt text](https://uploads-ssl.webflow.com/5eb2f56932c3562feab232e3/5f73550d00249e7e96c9f3de_Logo.png 'corecodeio')

</a>

<h1 align="center">Solution</h1>

# Implement the interpolation search algorithm to search a list of integers.



## Solution 🏁
    
```python
def interpolation_search(input, value):
    low = 0
    high = len(input) - 1
    while low <= high and value >= input[low] and value <= input[high]:
        if low == high:
            if input[low] == value:
                return low
            return -1
        pos = low + int(((float(high - low) / (input[high] - input[low])) * (value - input[low])))
        if input[pos] == value:
            return pos
        if input[pos] < value:
            low = pos + 1
        else:
            high = pos - 1
    return -1

```

This is an implementation of the interpolation search algorithm. 
The interpolation_search function takes two arguments - an input array and a value to search for - and returns the index of the value in the array if it is found, or -1 if it is not found. The algorithm works by using interpolation to estimate the position of the value in the array based on its value and the values of the first and last elements in the array. It then performs a binary search on the portion of the array between the estimated position and the last position searched. This approach can be more efficient than a traditional binary search for certain types of data, particularly if the data is evenly distributed.

## Video Solution 📹

[Video](https://youtu.be/U8IjI85Uc0c)