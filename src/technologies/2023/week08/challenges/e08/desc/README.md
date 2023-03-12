<a href="https://www.core-code.io/">

![alt text](https://uploads-ssl.webflow.com/5eb2f56932c3562feab232e3/5f73550d00249e7e96c9f3de_Logo.png 'corecodeio')

</a>

<h1 align="center">Description</h1>

# Creating a Bank Account Class


## Description

Create a class called BankAccount that has the following attributes:

```python
owner #(a string representing the owner's name)
balance #(a float representing the balance)
```

The class should also have the following methods:

```python
deposit(amount) #(adds amount to the balance)
withdraw(amount) #(subtracts amount from the balance, but only if the balance is sufficient)
get_balance() #(returns the current balance)
```

Next, create an instance of the class for a bank account with an owner named "John Doe" and an initial balance of $100. Test the deposit, withdraw, and get_balance methods to make sure they work as expected.


## Expected output
```python
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


## How to submit my solution?
    
Add your solution to your README file

## More Help?

Slack us 😉

# Solution

## PLEASE DON'T CHECK THE SOLUTION UNTIL YOU HAVE FINISH YOURS

### Take in mind that this is an example solution, your implementation can be different and that's ok

[Solution](../sol)
