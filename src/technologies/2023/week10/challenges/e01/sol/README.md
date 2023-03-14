<a href="https://www.core-code.io/">

![alt text](https://uploads-ssl.webflow.com/5eb2f56932c3562feab232e3/5f73550d00249e7e96c9f3de_Logo.png 'corecodeio')

</a>

<h1 align="center">Solution</h1>

# Write Python Dictionary to JSON string

## Solution 🏁

```python
import json

# define a function to write a dictionary to a JSON file
def dict_to_json(dict_data, file_name):
    with open(file_name, 'w') as f:
        json.dump(dict_data, f)

# create a Python dictionary
person = {"name": "John", "age": 30, "city": "New York"}

# write the dictionary to a JSON file using the function
dict_to_json(person, "person.json")

# read the JSON file and convert it to a Python dictionary
with open("person.json") as f:
    person_dict = json.load(f)

# print the dictionary
print(person_dict)  # {'name': 'John', 'age': 30, 'city': 'New York'}
```

The code above demonstrates how to define a function that takes a Python dictionary and writes it to a JSON file using the `json.dump()` method. This function is useful for situations where you need to write multiple dictionaries to JSON files in a single script. In the example above, the `dict_to_json()` function is defined to take a dictionary and a file name as arguments and writes the dictionary to the file using the `json.dump()` method inside the function. The function is then used to write the `person` dictionary to a file called "person.json". The file is then read and converted back to a dictionary using the `json.load()` method and printed to the console. The expected output is shown on the right side of the print statement.

## Video Solution 📹

[Video](https://youtu.be/k8YvvjRBNok)
