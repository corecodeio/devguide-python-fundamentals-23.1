<a href="https://www.core-code.io/">

![alt text](https://uploads-ssl.webflow.com/5eb2f56932c3562feab232e3/5f73550d00249e7e96c9f3de_Logo.png 'corecodeio')

</a>

<h1 align="center">Solution</h1>

# Creating an Array of Objects




## Solution 🏁
    
```python

class Person:
    def __init__(self, name, age):
        self.name = name
        self.age = age

# create an array of Person objects
people = [
    Person("Alice", 25),
    Person("Bob", 30),
    Person("Charlie", 35)
]

# iterate over the array and print out the name and age of each person
for person in people:
    print(f"Name: {person.name}, Age: {person.age}")

```

Here, we created a class called `Person` with two attributes: `name` and `age`. We then created an array called `people` and initialized it with three `Person` objects.

Next, we used a for loop to iterate over the array and print out the name and age of each person. Within the loop, we accessed the name and age attributes of each `Person` object by calling `person.name` and `person.age`, respectively.

The key concept illustrated in this exercise is creating an array of objects, where each element in the array is an instance of a class. We then accessed the attributes of each object by iterating over the array and calling the appropriate methods on each object.


## Video Solution 📹

[Video](https://drive.google.com/file/d/1mTioEqemsJ7isHP7MuOX6OISLWKJz2ZC/view?usp=share_link)