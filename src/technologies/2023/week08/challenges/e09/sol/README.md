<a href="https://www.core-code.io/">

![alt text](https://uploads-ssl.webflow.com/5eb2f56932c3562feab232e3/5f73550d00249e7e96c9f3de_Logo.png 'corecodeio')

</a>

<h1 align="center">Solution</h1>

# Inheriting from a Parent Class




## Solution 🏁
    
```python
class Animal:
    def __init__(self, name, species):
        self.name = name
        self.species = species

    def make_sound(self):
        pass

class Dog(Animal):
    def __init__(self, name, species, breed):
        super().__init__(name, species)
        self.breed = breed

    def bark(self):
        print("woof")

    def make_sound(self):
        self.bark()

# create an instance of the Dog class
my_dog = Dog("Fido", "Canis lupus familiaris", "Labrador Retriever")

# test the methods
my_dog.make_sound()  # output: woof

```

Here, we defined a class called `Animal` with an `__init__` method and a `make_sound` method. We then created a subclass of `Animal` called `Dog` and defined its own `__init__` method and a bark method. We also overrode the `make_sound` method of the `Animal` class with the `bark` method of the `Dog` class.

We created an instance of the `Dog` class called `my_dog` and tested its methods by calling the `make_sound` method. Since we overrode the `make_sound` method in the Dog class, when we called the `make_sound` method on `my_dog`, it called the bark method and printed "woof".

The key concept illustrated in this exercise is inheritance, where we created a new class that inherited attributes and methods from its parent class. In this case, `Dog` inherited from `Animal` and added its own attributes and methods.


## Video Solution 📹

[Video](https://youtu.be/zJq6NMut8gk)