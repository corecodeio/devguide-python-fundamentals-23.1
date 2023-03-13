# Calculating Factorial of a Number

## Solution 😎

```python
def factorial(n):
    if n == 1:
        return 1
    else:
        return n * factorial(n-1)

number = 5
result = factorial(number)

print("The factorial of", number, "is", result)
```

## Video Solution 📹

[Calculating Factorial of a Number](https://edpuzzle.com/assignments/63be1fca883672415be0f901/watch)
<iframe width="560" height="315" src="https://www.youtube.com/embed/NUo2ieK5gZY" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
