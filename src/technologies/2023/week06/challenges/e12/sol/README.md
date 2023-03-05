# Merge Lists without Duplicates

## Solution 😎

```python
l1 = [4, 5, 34, 9]
l2 = [4, 5, 80, 10]
result = list(set(l1 + l2))

print('first list:', l1)
print('second list:', l2)
print('result:', result)
```

This code takes two lists as input, and first merges them using the `+` operator. Then, it converts the merged list to a set using the `set()` function to remove duplicates, and converts the resulting set back to a list using the `list()` function.

## Video Solution 📹

[Merge Lists without Duplicates](https://drive.google.com/file/d/19xGZD-WSTzD2xnxh-7mBsUnsZOaQEVOt/view?usp=sharing)
