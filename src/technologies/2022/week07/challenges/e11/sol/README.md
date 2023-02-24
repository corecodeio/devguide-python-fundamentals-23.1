# Filtering a List of Strings by a Given Substring

## Solution 😎

```python
words = ["apple", "banana", "cherry", "date", "elderberry"]
substring = "erry"

def filter_substring(word_list, substring):
    return list(filter(lambda x: substring in x, word_list))

filtered_words = filter_substring(words, substring)

print("The filtered words are:", filtered_words)
```

## Video Solution 📹

[Filtering a List of Strings by a Given Substring](https://edpuzzle.com/assignments/63be1fac7b20954154140ad6/watch)
