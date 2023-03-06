# Increment

## Solution 😎

```javascript
elements = [30, 3, 5, 6, 6, 9, 9, 0, 1, 2, 3]

unique = []
for item in elements:
  if item not in unique:
    unique.append(item)

print('original list:', elements)
print('list with unique elements in the same order:', unique)
```

 We loop through each element in the input list and check if it is already in the unique list. If it is not, we add it to the unique list. We print the unique list as the result.

## Video Solution 📹

[Increment](https://edpuzzle.com/assignments/6386b30eca67c040c18d944e/watch)
