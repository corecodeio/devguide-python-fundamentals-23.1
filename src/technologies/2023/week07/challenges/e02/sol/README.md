# Removing Duplicates from a List

## Solution 😎

```javascript
elements = [30, 3, 5, 6, 6, 9, 9, 0, 1, 2, 3]

unique = []
for item in elements:
  if item not in unique:
    unique.append(item)

print('original list:', elements)
print('list with unique elements in the same order:', unique)
```

 We loop through each element in the input list and check if it is already in the unique list. If it is not, we add it to the unique list. We print the unique list as the result.

## Video Solution 📹

[Removing Duplicates from a List](https://drive.google.com/file/d/1czVXhb7MG5Ntc-KZIpwen_inVVYZP2NL/view?usp=sharing)
<iframe width="560" height="315" src="https://www.youtube.com/embed/-iEGP95x1H0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
