# Find second largest element

## Solution 😎

```python
numbers = [4, 5, 34, 9, 12, 0, 873]

print('numbers:', numbers)
if len(numbers) < 2:
    print('There isn\'t a second largest element')
else:
    sorted_numbers = sorted(numbers, reverse=True)
    print('The second largest element is', sorted_numbers[1])
```

In this solution, we first check if the length of the resulting set is less than 2 (i.e. there are less than two elements in the list), in which case we can not get the second largest element. Otherwise, we sort the set in descending order using the `sorted()` function with the `reverse=True` argument, and print the second element (i.e. the second largest number) using indexing.

## Video Solution 📹

[Find Largest Element](https://drive.google.com/file/d/1-tPSwAnrREGvlUZX56Ke_m0118-mUWt8/view?usp=sharing)
