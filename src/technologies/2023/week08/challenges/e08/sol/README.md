<a href="https://www.core-code.io/">

![alt text](https://uploads-ssl.webflow.com/5eb2f56932c3562feab232e3/5f73550d00249e7e96c9f3de_Logo.png 'corecodeio')

</a>

<h1 align="center">Solution</h1>

# Creating a Bank Account Class




## Solution 🏁
    
```python
class BankAccount:
    def __init__(self, owner, balance=0.0):
        self.owner = owner
        self.balance = balance

    def deposit(self, amount):
        self.balance += amount

    def withdraw(self, amount):
        if self.balance >= amount:
            self.balance -= amount
        else:
            print("Insufficient funds")

    def get_balance(self):
        return self.balance

# create an instance of the class
john_account = BankAccount("John Doe", 100.0)

# test the methods
print(john_account.get_balance())  # output: 100.0

john_account.deposit(50.0)
print(john_account.get_balance())  # output: 150.0

john_account.withdraw(25.0)
print(john_account.get_balance())  # output: 125.0

john_account.withdraw(200.0)  # output: Insufficient funds
print(john_account.get_balance())  # output: 125.0

```

Here, we created a Python class called BankAccount that has three methods: `__init__`, deposit, withdraw, and `get_balance`. The `__init__` method initializes the attributes of the class, including the owner's name and the account balance. The deposit method adds a specified amount to the account balance, the withdraw method subtracts a specified amount from the account balance, but only if the balance is sufficient. If the balance is `insufficient`, it prints a message stating "Insufficient funds". Finally, the `get_balance` method returns the current balance of the account.

We then created an instance of the class called `john_account` and tested the methods to make sure they work as expected. We first printed the initial balance of the account, then deposited `50`, and then withdrew `25` to make sure the balance was updated accordingly. Finally, we tested withdrawing an amount that was greater than the balance to make sure that the method handles `insufficient` funds.


## Video Solution 📹

<iframe width="560" height="315" src="https://www.youtube.com/embed/i3XrxmdMAl4" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>