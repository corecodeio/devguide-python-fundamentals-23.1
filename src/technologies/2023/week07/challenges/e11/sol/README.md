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

[Filtering a List of Strings by a Given Substring](https://drive.google.com/file/d/1JS5uCMXEc9_osU2b5TMFR0RtHaY7nycj/view?usp=share_link)
