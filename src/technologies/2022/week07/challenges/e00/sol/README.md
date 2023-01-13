# String: substr()

## Solution 1 😎

```javascript
function firstWord(str) {
  let firstBlank = str.indexOf(' ');
  return str.substring(0, firstBlank);
}
```

## Solution 2 😎

```javascript
function firstWord(str) {
  return str.substring(0, str.indexOf(' '));
}
```

## Video Solution 📹

[String: substr()](https://edpuzzle.com/assignments/6386b2ca7e86f04117b1f5c6/watch)
