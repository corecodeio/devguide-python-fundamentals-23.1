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

We loop through each character in the input string, converting it to lowercase using the lower() function. We then check if the character is a letter using the isalpha() function. If it is, we check if it already exists in the dictionary - if it does, we increment its count, and if it doesn't, we add it to the dictionary with a count of 1.

## Video Solution 📹

[Counting occurrences of letters in a string](https://edpuzzle.com/assignments/6386b2ca7e86f04117b1f5c6/watch)
