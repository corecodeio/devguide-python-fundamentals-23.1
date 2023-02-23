# Reverse Dictionary

## Solution 😎

```python
original_dict = {'a': 1, 'b': 2, 'c': 3}

reversed_dict = {value: key for key, value in original_dict.items()}

print('dictionary:', original_dict)
print('reversed dictionary:', reversed_dict)
```

The code first defines an `original_dict` variable with some key-value pairs. The goal is to reverse this dictionary, so that the keys become values and vice versa.

To do this, the code defines a new dictionary `reversed_dict` and uses a dictionary comprehension to populate it. The comprehension iterates over the key-value pairs in `original_dict` using the `items()` method, and for each pair it creates a new entry in `reversed_dict` with the value as the key and the key as the value.

Note that the syntax of the comprehension is `{value: key for key, value in original_dict.items()}`. Here, value: key represents the key-value pair that is being created in the new dictionary, and key, value represents the unpacking of the key-value pairs from `original_dict.items()` that we are iterating over.

Finally, the code prints the reversed dictionary to verify that it has been constructed correctly.

## Video Solution 📹

[Reverse Dictionary](https://drive.google.com/file/d/18sFzSlPgCLRg88bQRpTsPaseXvqTrFbX/view?usp=sharing)
