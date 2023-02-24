# Calculating Factorials

## Solution 😎

```python
num = 5

factorial = 1

for i in range(1, num + 1):
    factorial *= i

print(f"The factorial of {num} is {factorial}.")
```

In this program, we use a for loop to iterate through the numbers 1 to the input number. We use a variable to keep track of the current factorial value, and update it on each iteration of the loop. Finally, we print the result using an f-string.

## Video Solution 📹

[Calculating Factorials](https://edpuzzle.com/assignments/6386b331fbf1084156e46dda/watch)
