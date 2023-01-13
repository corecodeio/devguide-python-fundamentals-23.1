# Count strings in objects

## Solution 😎

```javascript
function strCount(obj){
  let count = 0
  for (key in obj){
    if (typeof obj[key] == 'string') count++;
    if (typeof obj[key] == 'object') count+= strCount(obj[key]);
  }
  
  return count
}
```

## Video Solution 📹

[Count strings in objects](https://edpuzzle.com/assignments/63be1f5fc212cc410e644312/watch)
