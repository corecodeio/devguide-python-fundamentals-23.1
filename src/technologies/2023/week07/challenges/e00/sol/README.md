# Counting occurrences of letters in a string

## Solution 😎

```python
string = '000 - HELLO! hello! HELLO! - 000'

letters = {}

for char in string.lower():
  if char.isalpha():
    if char in letters:
      letters[char] += 1
    else:
      letters[char] = 1

print('input:', string)
print('result:', letters)
```

## Video Solution 📹

[Counting occurrences of letters in a string](https://edpuzzle.com/assignments/6386b2ca7e86f04117b1f5c6/watch)
