# Checking for Palindromes

## Solution 😎

```python
string = "Anna"

lower_string = string.lower()
reversed_string = ""
index = len(lower_string) - 1
while index >= 0:
    reversed_string += lower_string[index]
    index -= 1
is_pelindrome = lower_string == reversed_string

print('string:', string)
print('palindrome?', is_pelindrome)
```

In this program, we convert the string to `lower-case` string, then we use a `While Loop` to iterate through the string in reverse order and construct a new string variable reversed_string. We then use an If-Else statement to check if the original string and the reversed string are equal. If they are, we return True (the string is a palindrome), and if they are not, we return False.

## Video Solution 📹

[Checking for Palindromes](https://edpuzzle.com/assignments/6386b331fbf1084156e46dda/watch)
