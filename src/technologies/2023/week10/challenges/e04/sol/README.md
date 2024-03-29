<a href="https://www.core-code.io/">

![alt text](https://uploads-ssl.webflow.com/5eb2f56932c3562feab232e3/5f73550d00249e7e96c9f3de_Logo.png 'corecodeio')

</a>

<h1 align="center">Solution</h1>

# Creating a requirements.txt File and Installing Dependencies in a Virtual Environment

## Solution 🏁

```bash
# create a `requirements.txt` file using the `pip freeze` command
# open the command prompt or terminal and navigate to the root directory of your project, then enter the following command:
pip freeze > requirements.txt

# create a local virtual environment using the `virtualenv` package
# enter the following command in the command prompt or terminal:
virtualenv venv

# activate the virtual environment
# on Windows:
# venv\Scripts\activate
# on macOS/Linux:
source venv/bin/activate

# install dependencies from the `requirements.txt` file
# enter the following command in the command prompt or terminal:
pip install -r requirements.txt
```

The code above demonstrates how to create a `requirements.txt` file using the `pip freeze` command, create a local virtual environment using the `virtualenv` package, and install dependencies from the `requirements.txt` file. The `pip freeze` command is used to generate a list of dependencies for the current Python environment and save them to a `requirements.txt` file. The `virtualenv` package is used to create a local virtual environment for the project, which provides a separate Python environment with its own dependencies. The `pip install -r requirements.txt` command is used to install the dependencies listed in the `requirements.txt` file into the virtual environment. This ensures that the project dependencies are isolated from the system-level Python environment and can be easily managed and shared.

## Video Solution 📹

<iframe width="560" height="315" src="https://www.youtube.com/embed/kbzFasLVkG4" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
