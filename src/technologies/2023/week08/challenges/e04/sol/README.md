<a href="https://www.core-code.io/">

![alt text](https://uploads-ssl.webflow.com/5eb2f56932c3562feab232e3/5f73550d00249e7e96c9f3de_Logo.png 'corecodeio')

</a>

<h1 align="center">Solution</h1>

# Implement a Binary Search Tree in Python and search it iteratively until you find the value you are looking for.



## Solution 🏁
    
```python
class TreeNode:
    def __init__(self, val):
        self.val = val
        self.left = None
        self.right = None

class BinarySearchTree:
    def __init__(self):
        self.root = None

    def insert(self, val):
        if self.root is None:
            self.root = TreeNode(val)
        else:
            current = self.root
            while True:
                if val < current.val:
                    if current.left is None:
                        current.left = TreeNode(val)
                        break
                    else:
                        current = current.left
                elif val > current.val:
                    if current.right is None:
                        current.right = TreeNode(val)
                        break
                    else:
                        current = current.right
                else:
                    break

    def search(self, val):
        current = self.root
        while current is not None:
            if val == current.val:
                return True
            elif val < current.val:
                current = current.left
            else:
                current = current.right
        return False

```

In this implementation, the TreeNode class represents a single node in the binary search tree, and the BinarySearchTree class represents the entire tree. The insert method is used to insert a new node into the tree, while the search method is used to iteratively search the tree for a given value.

To use this implementation, you can create a new instance of the BinarySearchTree class, insert some values into the tree using the insert method, and then search the tree for a specific value using the search method. The following code shows how to use this implementation:

```python
# Create a new binary search tree
bst = BinarySearchTree()

# Insert some values into the tree
bst.insert(5)
bst.insert(3)
bst.insert(7)
bst.insert(1)
bst.insert(9)

# Search the tree for a value
print(bst.search(7))  # Output: True
print(bst.search(2))  # Output: False
```

## Video Solution 📹

[Counting Even and Odd Numbers](https://edpuzzle.com/assignments/6386b321c511ef40e3f4fb07/watch)