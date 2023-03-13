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

[Calculating Factorials](https://drive.google.com/file/d/1j08etyS9PM_ks32mAIHMvDN_PZXalg-I/view?usp=share_link)
<iframe width="560" height="315" src="https://www.youtube.com/embed/BQMdGP0rPaU" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
