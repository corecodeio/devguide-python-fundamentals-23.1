# Flattening a List of Lists

## Solution 😎

```python
lists = [
    [1, 2, 3, 4],
    [5, 6, 7, 8],
    [9, 10, 11, 12]
]

flattened_list = []
for sublist in lists:
  flattened_list.extend(sublist)

print('original list of lists:', lists)
print('result:', flattened_list)
```

## Video Solution 📹

[Flattening a List of Lists](https://edpuzzle.com/assignments/6386bfcf7e4fbc41006e8862/watch)

<iframe width="560" height="315" src="https://www.youtube.com/embed/-bKl6GH1xfI" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
