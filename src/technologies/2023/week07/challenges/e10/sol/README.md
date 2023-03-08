# Filtering a List of Strings by a Given Substring

## Solution 😎

```python
words = ["apple", "banana", "cherry", "date", "elderberry"]

def sort_by_length(word_list):
    return sorted(word_list, key=lambda x: len(x))

sorted_words = sort_by_length(words)

print("Original list:", words)
print("The sorted list is:", sorted_words)
```

In this program, we define a list of strings called `words`. We then define a function called `sort_by_length` that takes one argument `word_list`, sorts the list by length using the `sorted()` function and a lambda function that specifies the sorting key to be the length of each string, and returns the sorted list. We then call the `sort_by_length` function with the words list as an argument, and store the sorted list in a variable called `sorted_words`. Finally, we print out the sorted list.

## Video Solution 📹

[Sorting a List of Strings by Length](https://drive.google.com/file/d/1eQqvE_velWHbD1T-HZ-Mp9Pmp-dYCgz1/view?usp=share_link)
