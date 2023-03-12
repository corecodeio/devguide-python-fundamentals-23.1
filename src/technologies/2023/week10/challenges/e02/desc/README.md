<a href="https://www.core-code.io/">

![alt text](https://uploads-ssl.webflow.com/5eb2f56932c3562feab232e3/5f73550d00249e7e96c9f3de_Logo.png 'corecodeio')

</a>

<h1 align="center">Description</h1>

# Intro to Regular Expressions (Regex)
Regular expressions, or RegEx, are patterns used to match character combinations in strings. In Python, the built-in `re` module is used to work with RegEx. The `re` module provides methods that allow us to search a string for a match, and then return the results of that search. 

## Description

Implement the following on a Python script:
- RegEx Multiple Matches
  - Match a string that starts with "Hello" and is followed by one or more word characters
  - Match a string that contains any number of digits followed by a space and then any number of non-digit characters
  - Match a string that contains one or more occurrences of the word "cat"
  - Match a string that starts with any number of word characters, followed by a hyphen, and ends with any number of word characters

## Expected output
```python
# Example 1: Match a string that starts with "Hello" and is followed by one or more word characters
pattern1 = r"MODIFY ME"
string1 = "Hello World"
match1 = re.match(pattern1, string1)
print(match1)  # <re.Match object; span=(0, 11), match='Hello World'>

# Example 2: Match a string that contains any number of digits followed by a space and then any number of non-digit characters
pattern2 = r"MODIFY ME"
string2 = "123 abc 456 def"
match2 = re.search(pattern2, string2)
print(match2)  # <re.Match object; span=(0, 8), match='123 abc '>

# Example 3: Match a string that contains one or more occurrences of the word "cat"
pattern3 = r"MODIFY ME"
string3 = "I have a cat and a cattle"
match3 = re.findall(pattern3, string3)
print(match3)  # ['cat', 'cat']

# Example 4: Match a string that starts with any number of word characters, followed by a hyphen, and ends with any number of word characters
pattern4 = r"MODIFY ME"
string4 = "python-script"
match4 = re.match(pattern4, string4)
print(match4)  # <re.Match object; span=(0, 13), match='python-script'>
``` 

## Helpful Resources


## How to submit my solution?

Add your solution to your README file

## More Help?

Slack us 😉

# Solution

## PLEASE DON'T CHECK THE SOLUTION UNTIL YOU HAVE FINISH YOURS

### Take in mind that this is an example solution, your implementation can be different and that's ok

[Solution](../sol)
