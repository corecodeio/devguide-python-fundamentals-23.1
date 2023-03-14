<a href="https://www.core-code.io/">

![alt text](https://uploads-ssl.webflow.com/5eb2f56932c3562feab232e3/5f73550d00249e7e96c9f3de_Logo.png 'corecodeio')

</a>

<h1 align="center">Solution</h1>

# JSON from file to Python Dictionary

## Solution 🏁
    
```python
import json

# define a function to read a JSON file and return a dictionary
def json_to_dict(file_name):
    with open(file_name) as f:
        data = json.load(f)
    return data

# read a JSON file and convert it to a Python dictionary using the function
person_dict = json_to_dict("person.json")

# print the dictionary
print(person_dict)  # {'name': 'John', 'age': 30, 'city': 'New York'}
print(type(person_dict))  # <class 'dict'

```

The code above demonstrates how to define a function that reads a JSON file and returns a Python dictionary using the `json.load()` method. This function is useful for situations where you need to read multiple JSON files and convert them to dictionaries in a single script. In the example above, the `json_to_dict()` function is defined to take a file name as an argument and returns a dictionary loaded from the file. The file is then read and converted to a dictionary using the `json.load()` method inside the function, and the resulting dictionary is printed to the console outside the function. The expected output is shown on the right side of the print statement.

## Video Solution 📹

[Video](https://youtu.be/iALKdLiL_qo)