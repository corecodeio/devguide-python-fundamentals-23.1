# Code Refactor

## Solution 😎

```python
# Inefficient code example: calculating the sum of all odd numbers between 1 and 1000000
total = 0
for i in range(1, 1000000):
    if i % 2 == 1:
        total += i
print(total)
```

This code calculates the sum of all odd numbers between 1 and 1000000 by iterating over every number in that range and checking if it's odd before adding it to the total variable. However, this approach is inefficient because it iterates over a million numbers, even though only half of them are odd.

To make this code more efficient, we can use the `range()` function with a step of 2 to generate only odd numbers and calculate their sum directly, like this:

```python
# Efficient code example: calculating the sum of all odd numbers between 1 and 1000000
total = sum(range(1, 1000000, 2))
print(total)
```

This code uses the `range()` function with a step of 2 to generate only odd numbers between 1 and 1000000, and then uses the `sum()` function to calculate their sum directly. This approach is much more efficient because it only iterates over 500000 numbers (half of the original range), making it faster and using less memory.

In general, when writing Python code, it's important to consider the time and memory complexity of the algorithms used, and to try to optimize them when possible to improve performance.

## Video Solution 📹

[Code Refactor](https://drive.google.com/file/d/1K3gVU4KOF_-bEnjc7a3GGI8SBjjtJFG6/view?usp=share_link)
