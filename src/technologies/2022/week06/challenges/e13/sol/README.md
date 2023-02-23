# Find Common Elements in Lists

## Solution 😎

```python
l1 = [4, 5, 34, 9]
l2 = [4, 5, 80, 10]
result = list(set(l1) & set(l2))

print('first list:', l1)
print('second list:', l2)
print('result:', result)
```

This code takes two lists, and first converts them to sets using the `set()` function. Then, it uses the `&` operator to find the intersection of the two sets, and converts the resulting set back to a list using the `list()` function.

## Video Solution 📹

[Find Common Elements in Lists](https://drive.google.com/file/d/12yzvG84fCMlpN8Rt2kn0LexoCPC84hur/view?usp=sharing)
