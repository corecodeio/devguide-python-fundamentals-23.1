# Temperature

## Solution 😎

```python
celsius = float(input("Enter temperature in Celsius: "))
fahrenheit = (celsius * 9/5) + 32
print("{:.2f} degrees Celsius is equivalent to {:.2f} degrees Fahrenheit.".format(celsius, fahrenheit))
```

The program first prompts the user to enter a temperature in Celsius using the `input()` function and saves the user's input as a string. It then uses the `float()` function to convert the user's input from a string to a `floating-point` number.

Next, it uses the formula `F = (C * 9/5) + 32` to convert the temperature from Celsius to Fahrenheit and saves the result in a variable called fahrenheit.

Finally, it uses the `format()` method to create a formatted string that displays the original temperature in Celsius and the equivalent temperature in Fahrenheit. The `:.2f` format specifier is used to round the temperature values to two decimal places. The `format()` method takes two arguments, celsius and fahrenheit, which are inserted into the formatted string in the places marked by the `{}` placeholders.

The program then prints the formatted string to the console using the `print()` function.

## Video Solution 📹

[Temperature](https://drive.google.com/file/d/1l-8CWCz2TjAP1UBMfpsx8XJ-6hh3sgnT/view?usp=sharing)
