<a href="https://www.core-code.io/">

![alt text](https://uploads-ssl.webflow.com/5eb2f56932c3562feab232e3/5f73550d00249e7e96c9f3de_Logo.png 'corecodeio')

</a>

<h1 align="center">Solution</h1>

# Use PIP to install the package called requests and use it to make a GET request to the following URL: https://jsonplaceholder.typicode.com/todos/1

The `requests` package is a popular Python library used for making HTTP requests. This solution demonstrates how to use PIP to install the `requests` package and use it to make a GET request to a URL.

## Solution 🏁

Open your terminal/command prompt and type the following command:

```bash
pip install requests

# or

pip3 install requests
```

In your code, import the `requests` package and use it to make a GET request to the following URL: https://jsonplaceholder.typicode.com/todos/1

```python
import requests
response = requests.get("https://jsonplaceholder.typicode.com/todos/1")
response_body = response.json()
print(response_body) # {'userId': 1, 'id': 1, 'title': 'delectus aut autem', 'completed': False}
```


The code above demonstrates how to install the `requests` package using PIP and use it to make a GET request to a URL. The `requests.get()` method is used to make a GET request to the URL "https://jsonplaceholder.typicode.com/todos/1" and return a `Response` object. The `Response` object has a `json()` method that returns the response body as a Python dictionary. The response body is assigned to the variable `response_body`, which is then printed to the console.

## Video Solution 📹

<iframe width="560" height="315" src="https://www.youtube.com/embed/EOrZCxtJU-0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
