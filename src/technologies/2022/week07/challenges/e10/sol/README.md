# Extending JavaScript Objects: Get First & Last Array Element

## Solution 😎

```javascript
Array.prototype.first = function() {
  return this[0];
};

Array.prototype.last = function() {
  return this[this.length-1];
};
```

## Video Solution 📹

[Extending JavaScript Objects: Get First & Last Array Element](https://edpuzzle.com/assignments/63be1f70f9b1e6411576f311/watch)
