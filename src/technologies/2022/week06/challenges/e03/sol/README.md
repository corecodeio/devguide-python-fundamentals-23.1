# String greeting

## Solution 😎

```python
name = input('What is your name? ')
age = input('What is your age? ')

print('Hello, {}! You are {} year old.'.format(name, age))
```

The first line of the code uses the built-in `input()` function to prompt the user to enter their name. The entered value is then stored in the `name` variable.

The second line of the code uses the `input()` function again to prompt the user to enter their age. The entered value is then stored in the `age` variable.

The third line of the code uses the `print()` function to display a personalized greeting message using the name and age values. The `format()` method is used to insert the name and age values into the greeting message. The `{}` placeholders in the string are replaced by the corresponding `format()` arguments, in the order they appear. This allows for dynamic text output, as the value of name and age can be different each time the code is executed.

## Video Solution 📹

[String greeting](https://drive.google.com/file/d/1F7U8TCNx_Rj6Ft_bt6Uolm-hsQUfxT7L/view?usp=sharing)
