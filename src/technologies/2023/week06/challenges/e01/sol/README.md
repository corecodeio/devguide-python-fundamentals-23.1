# Weather suggestion

## Solution 😎

```python
# Declare two boolean variables
is_raining = True
is_cold = False

# Check the conditions and make decisions

print('Is it raining?', is_raining)
print('Is it cold?', is_cold)
print('')

if is_raining and is_cold:
  print("Bring a coat and an umbrella")
elif is_raining:
  print("Bring an umbrella")
elif is_cold:
  print("Bring a coat")
else:
  print("There's no need to bring anything special")
```

This code declares two boolean variables, it is raining and it is cold, which indicate if it is raining and if it is cold. It then uses an `if-elif-else` conditional structure to make decisions based on these conditions.

If rainy and cold are true (both conditions are true), the program will print `"Bring a coat and an umbrella."` If only rain is true, the program will print `"Bring an umbrella"`. If only cold is true, the program will print `"Bring a coat"`. If both variables are false (it's not cold and raining), the program will print `"No need to bring anything special"`.

This example shows how boolean values can be useful for controlling program flow and making decisions based on conditions.

## Video Solution 📹

[Weather suggestion](https://drive.google.com/file/d/15bbcC4yPB1_TN-1jTpE9XhdC2O8pU50Y/view?usp=sharing)
