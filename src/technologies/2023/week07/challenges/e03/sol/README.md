# Counting Even and Odd Numbers

## Solution 😎

```python
numbers = [1, 2, 3, 4, 5, 6, 7, 8, 9]

even_count = 0
odd_count = 0

for num in numbers:
    if num % 2 == 0:
        even_count += 1
    else:
        odd_count += 1

print("elements:", numbers)
print(f"There are {even_count} even numbers and {odd_count} odd numbers in the list.")
```

In this program, we use a for loop to iterate through each number in the list. We use an if/else statement to check if the number is even or odd, and increment the corresponding counter variable. Finally, we print the results using an f-string.

## Video Solution 📹

[Counting Even and Odd Numbers](https://drive.google.com/file/d/1GAp5H06nHVCflZCna1d0VRlUzcRCWW6g/view?usp=sharing)
<iframe width="560" height="315" src="https://www.youtube.com/embed/O_-W0a8Cx_g" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
