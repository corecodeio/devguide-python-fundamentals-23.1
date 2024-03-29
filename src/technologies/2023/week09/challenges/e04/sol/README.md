<a href="https://www.core-code.io/">

![alt text](https://uploads-ssl.webflow.com/5eb2f56932c3562feab232e3/5f73550d00249e7e96c9f3de_Logo.png 'corecodeio')

</a>

<h1 align="center">Solution</h1>

# Formatting dates



## Solution 🏁
    
```python
import datetime

now = datetime.datetime.now()
print("The current date and time is:", now.strftime("%Y-%m-%d %H:%M:%S")) # Output: in format "YYYY-MM-DD HH:MM:SS" eg. "2023-05-21 12:00:00"

```

In this program, we imported the datetime module and used the now function to create a datetime object representing the current date and time. We then used the strftime method to format the datetime object as a string in the format "YYYY-MM-DD HH:MM:SS", and printed the result to the console.

## Video Solution 📹

<iframe width="560" height="315" src="https://www.youtube.com/embed/YmhRIHYiAGA" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>