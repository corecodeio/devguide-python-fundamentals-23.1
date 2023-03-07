<a href="https://www.core-code.io/">

![alt text](https://uploads-ssl.webflow.com/5eb2f56932c3562feab232e3/5f73550d00249e7e96c9f3de_Logo.png 'corecodeio')

</a>

<h1 align="center">Solution</h1>

# Implementing Merge Sort to Sort a List of Integers



## Solution 🏁
    
```python
input = [5, 4, 3, 2, 1]

def merge_sort(input):
    if len(input) > 1:
        mid = len(input) // 2
        left = input[:mid]
        right = input[mid:]

        merge_sort(left)
        merge_sort(right)

        i = j = k = 0

        while i < len(left) and j < len(right):
            if len(left[i]) < len(right[j]):
                input[k] = left[i]
                i += 1
            else:
                input[k] = right[j]
                j += 1
            k += 1

        while i < len(left):
            input[k] = left[i]
            i += 1
            k += 1

        while j < len(right):
            input[k] = right[j]
            j += 1
            k += 1

    return input

output = merge_sort(input)

print(output)
```

This is an implementation of the merge sort algorithm, which uses the divide-and-conquer strategy. The code defines a function called merge_sort that takes a list called input as an argument. If the length of the input list is greater than 1, the function splits the list into two halves and recursively calls merge_sort on each half to sort them. Then, it merges the sorted halves by comparing the lengths of the strings at the current indices in each half and appending the shorter one to a new input list. The function then returns the sorted input list.

## Video Solution 📹

[Counting Even and Odd Numbers](https://edpuzzle.com/assignments/6386b321c511ef40e3f4fb07/watch)