# Sorting a List of Strings by Length Using Bubble Sort

Given a list of strings, sort them by length in ascending order using the bubble sort algorithm.

## Solution 🏁
    
```python
strings = ["abc", "a", "ab", "abcd", "abcde"]

def bubble_sort(input):
    for i in range(len(input)):
        for j in range(len(input) - 1):
            if len(input[j]) > len(input[j + 1]):
                input[j], input[j + 1] = input[j + 1], input[j]
    return input

output = bubble_sort(strings)
print(output)
```

The function uses two nested loops to compare adjacent elements in the list. The outer loop iterates over each element in the list, and the inner loop iterates over each element in the list except for the last one. The inner loop compares the current element with the next element in the list. If the current element's length is greater than that of the next element, the two elements are swapped. This process continues until the list is sorted.

## Video Solution 📹

[Counting Even and Odd Numbers](https://edpuzzle.com/assignments/6386b321c511ef40e3f4fb07/watch)