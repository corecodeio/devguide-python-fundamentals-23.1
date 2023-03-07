<a href="https://www.core-code.io/">

![alt text](https://uploads-ssl.webflow.com/5eb2f56932c3562feab232e3/5f73550d00249e7e96c9f3de_Logo.png 'corecodeio')

</a>

<h1 align="center">Solution</h1>

# Implementing Quickselect to Find the Kth Smallest Element in a List



## Solution 🏁
    
```python
input = [5, 4, 3, 2, 1]

def quickselect(input, k):
    if len(input) == 1:
        return input[0]
    pivot = input[0]
    left = []
    right = []
    for i in range(1, len(input)):
        if input[i] < pivot:
            left.append(input[i])
        else:
            right.append(input[i])
    if len(left) == k - 1:
        return pivot
    elif len(left) > k - 1:
        return quickselect(left, k)
    else:
        return quickselect(right, k - len(left) - 1)

output = quickselect(input, 3)

print(output)
```

This is an implementation of the quickselect algorithm, which is used to find the k-th smallest element in an unsorted list. The quickselect function takes two arguments: input, which is the unsorted list, and k, which is the index of the k-th smallest element that we want to find. The function starts by selecting a pivot element from the list and partitioning the list into two sublists: left, which contains all elements smaller than the pivot, and right, which contains all elements greater than or equal to the pivot. If the length of left is equal to k-1, the pivot is the k-th smallest element and the function returns it. If the length of left is greater than k-1, then we recursively call quickselect on the left sublist to find the k-th smallest element in that sublist. Otherwise, we recursively call quickselect on the right sublist to find the (k-len(left)-1)-th smallest element in that sublist. This process continues until the k-th smallest element is found and returned.

## Video Solution 📹

[Counting Even and Odd Numbers](https://edpuzzle.com/assignments/6386b321c511ef40e3f4fb07/watch)