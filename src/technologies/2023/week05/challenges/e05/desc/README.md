# Variables

## Description

In Python, a variable is a name that is used to refer to a value stored in the computer's memory. It is a container that holds a value, such as a number, string, or object. Variables are created when you assign a value to a name using the equal sign (=) operator. For example, the following code creates a variable called "x" and assigns it the value of 10:

```python
a = 10
```
You can then use the variable "a" in expressions, such as:

```python
b = a + 4
b # 14
```
You can change the value of a variable by assigning a new value to it: `a = 20`.

### Name conventions

In Python, variable names must follow certain conventions. Here are some of the most important conventions:

1. Variable names must start with a letter or underscore (_). They cannot start with a number.
2. Use lowercase letters for variable names, and underscores to separate words in the name. This convention is known as "snake_case". For example:

```python
calculation_result = 12
```
3. Variable names can only contain letters, numbers, and underscores. They cannot contain spaces or special characters.
4. Variable names are case-sensitive. This means that `myVar` and `myvar` are two different variables.
5. It is recommended to use descriptive variable names that reflect the purpose of the variable. For example, `age` would be a better variable name than just `a`.
6. Additionally, reserved words in Python cannot be used as variable names, since they have special meanings in the language. These words include: "and", "or", "if", "else", "for", "while", etc.

### Assign multiple values
You can assign multiple values to multiple variables in a single line of code in Python by separating the values with commas.

**Different values**

For example, to assign the values 1, 2, and 3 to variables a, b, and c, respectively, you can use the following code:

```python
dim_x, dim_y, dim_z = 1, 2, 3
```
This assigns the value 1 to variable `dim_x`, the value 2 to variable `dim_y`, and the value 3 to variable `dim_z`.

**Same value**

You can also use this technique to assign the same value to multiple variables at once. For example:

```python
dim_x = dim_y = dim_z = 0
```
This assigns the value 0 to the three variables, at the same time.


**NOTE:** number of variables on the left-hand side of the equal sign must match the number of values on the right-hand side of the equal sign, otherwise your program will throw a `ValueError` exception.

### Output variables

You can output the value of a variable in Python using the "print" function. See the next example:

```python
temperature = 23
print(temperature) # 23
```

It assigns the value 23 to the variable `temperature` and then prints the value to the console using the `print` function. 

**Format**

You can also include variable values in a string using string formatting. One way to do this is by using f-strings, which is a feature introduced in Python 3.6. 

```python
name = "Bob"
age = 30
print(f"My name is {name} and I am {age} years old.")
```

This code creates two variables, `name` and `age`, and then includes their values in a string using curly braces {} and the `f` prefix. The output would be:

> My name is Bob and I am 30 years old.

### Global variables

To create a global variable in Python, you simply define it outside of any function or class. It's a variable that is defined outside of any function or class, and can be accessed and modified by any part of the program.

You need to use the keyword `global` to specify this kind of variable:

```python
temperature = 10   # This is a global variable

def my_function():
  global temperature
  temperature = 20

my_function()
print(temperature)   # This will output 20
```

**IMPORTANT**: Note that it is generally **recommended to avoid using global variables as much as possible**, since they can make it difficult to reason about the behavior of a program and can lead to unexpected results if they are modified by multiple parts of the program. Instead, it is often better to use function parameters or class attributes to pass data between different parts of a program.

---


In the next [section](../e06/desc/) we'll practice more about this...


## Helpful Resources

- [Python Variables](https://www.w3schools.com/python/python_variables.asp)


## More Help?

Slack us 😉
