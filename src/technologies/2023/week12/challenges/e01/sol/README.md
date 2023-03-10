# Print Hello world and CV info

## Solution 😎

```python
from flask import Flask

app = Flask(__name__)

@app.route('/')
def index():
    hello = 'Hello World from Flask! <br>'
    myInfo = """
        <h1>My name is: </h1>
        <h2>My age is: </h2>
        <h3>My address is: </h3>
        <h4>My phone number is: </h4>
    """

    return hello + myInfo

if __name__ == '__main__':
    app.run(debug=True)
```

## Video Solution 📹

<iframe width="560" height="315" src="https://www.youtube.com/embed/UubMBQOxDH0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
