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
