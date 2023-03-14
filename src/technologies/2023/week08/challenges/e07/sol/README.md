<a href="https://www.core-code.io/">

![alt text](https://uploads-ssl.webflow.com/5eb2f56932c3562feab232e3/5f73550d00249e7e96c9f3de_Logo.png 'corecodeio')

</a>

<h1 align="center">Solution</h1>

# Implement the radix sort algorithm to sort a list of integers in ascending order.




## Solution 🏁
    
```python
input = [5, 4, 3, 2, 1]
def radix_sort(input):
    max_length = False
    tmp, placement = -1, 1

    while not max_length:
        max_length = True
        # declare and initialize buckets
        buckets = [list() for _ in range(10)]

        # split input between lists
        for i in input:
            tmp = i // placement
            buckets[tmp % 10].append(i)
            if max_length and tmp > 0:
                max_length = False

        # empty lists into input array
        a = 0
        for b in range(10):
            buck = buckets[b]
            for i in buck:
                input[a] = i
                a += 1

        # move to next
        placement *= 10
    return input

output = radix_sort(input)
print(output)

```

This is an implementation of the radix sort algorithm in Python. It sorts a list of integers by comparing their digits from the least significant digit to the most significant digit. The algorithm works by repeatedly dividing the input integers by the current "placement" (which starts at 1) and then placing each integer into a "bucket" corresponding to the digit in the current "placement". After all integers have been placed in the buckets, the buckets are emptied back into the input array in order of the digits. This process is repeated until all digits have been compared, resulting in a sorted list of integers. In this implementation, buckets is a list of 10 empty lists, and placement is multiplied by 10 at the end of each iteration to move to the next digit. Once the input list has been fully sorted, it is returned by the function.


## Video Solution 📹

[Video](https://youtu.be/j378XC7icKY)