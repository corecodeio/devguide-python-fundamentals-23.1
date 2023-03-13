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

[Checking for Palindromes](https://drive.google.com/file/d/1E6IHiQWv1SnDTntyoylrrWibiR3W2i3X/view?usp=sharing)
<iframe width="560" height="315" src="https://www.youtube.com/embed/k16JlSJ8AK0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
