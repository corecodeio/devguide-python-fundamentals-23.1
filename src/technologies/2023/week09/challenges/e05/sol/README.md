<a href="https://www.core-code.io/">

![alt text](https://uploads-ssl.webflow.com/5eb2f56932c3562feab232e3/5f73550d00249e7e96c9f3de_Logo.png 'corecodeio')

</a>

<h1 align="center">Solution</h1>

# Calculating the number of days between two dates



## Solution 🏁
    
```python
import datetime

date1 = datetime.date(2023, 3, 1)
date2 = datetime.date(2023, 3, 15)
delta = date2 - date1
print("There are", delta.days, "days between", date1.strftime("%Y-%m-%d"), "and", date2.strftime("%Y-%m-%d")) # Output: There are 14 days between 2023-03-01 and 2023-03-15

```

In this program, we imported the datetime module and created two date objects representing March 1st and March 15th, 2022. We then subtracted the first date from the second date to calculate a timedelta object, and used the days attribute to retrieve the number of days between the two dates. Finally, we formatted the dates as strings using the strftime method and printed the result to the console.

## Video Solution 📹

<iframe width="560" height="315" src="https://www.youtube.com/embed/un5FLs8K--A" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>