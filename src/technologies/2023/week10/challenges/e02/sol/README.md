<a href="https://www.core-code.io/">

![alt text](https://uploads-ssl.webflow.com/5eb2f56932c3562feab232e3/5f73550d00249e7e96c9f3de_Logo.png 'corecodeio')

</a>

<h1 align="center">Solution</h1>

# Intro to Regular Expressions (Regex)

## Solution 🏁

```python
# Example 1: Match a string that starts with "Hello" and is followed by one or more word characters
pattern1 = r"Hello \w+"
string1 = "Hello World"
match1 = re.match(pattern1, string1)
print(match1)  # <re.Match object; span=(0, 11), match='Hello World'>

# Example 2: Match a string that contains any number of digits followed by a space and then any number of non-digit characters
pattern2 = r"\d+\s\D+"
string2 = "123 abc 456 def"
match2 = re.search(pattern2, string2)
print(match2)  # <re.Match object; span=(0, 8), match='123 abc '>

# Example 3: Match a string that contains one or more occurrences of the word "cat"
pattern3 = r"\bcat+\b"
string3 = "I have a cat and a cattle"
match3 = re.findall(pattern3, string3)
print(match3)  # ['cat', 'cat']

# Example 4: Match a string that starts with any number of word characters, followed by a hyphen, and ends with any number of word characters
pattern4 = r"\w+-\w+"
string4 = "python-script"
match4 = re.match(pattern4, string4)
print(match4)  # <re.Match object; span=(0, 13), match='python-script'>
```

The code above demonstrates several simple examples of creating RegEx patterns and matching them against strings using the `re` module in Python. In each example, a pattern is created using a combination of metacharacters, quantifiers, and other elements to specify a particular sequence of characters to match against a string. The `re.match()`, `re.search()`, or `re.findall()` method is then used to test the pattern against a string and return a match object. The expected output of each example is also shown on the right side of each print statement.

## Video Solution 📹

[Video](https://youtu.be/Q0tM6eloxWw)
