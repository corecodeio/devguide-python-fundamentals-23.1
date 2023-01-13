# String: toUpperCase()

## Solution 1 😎

```javascript
function toCase(str) {
  return str.toLowerCase() + '-' + str.toUpperCase();
}
```

## Solution 2 😎

```javascript
function toCase(str) {
  return str.toLowerCase().concat('-').concat(str.toUpperCase());
}
```

## Solution 3 😎

```javascript
function toCase(str) {
  return `${str.toLowerCase()}-${str.toUpperCase()}`;
}
```

## Video Solution 📹

[String: toUpperCase()](https://edpuzzle.com/assignments/6386b28c048b2a40fd892803/watch)
