# Objects

## Solution 1 😎

```javascript
function animal(obj) {
  return 'This ' + obj.color + ' ' + obj.name + ' has ' + obj.legs + ' legs.';
}
```

## Solution 2 😎

```javascript
function animal(obj) {
  return 'This '
    .concat(obj.color)
    .concat(' ')
    .concat(obj.name)
    .concat(' has ')
    .concat(obj.legs)
    .concat(' legs.');
}
```

## Solution 3 😎

```javascript
function animal(obj) {
  return `This ${obj.color} ${obj.name} has ${obj.legs} legs.`;
}
```

## Video Solution 📹

[Objects](https://edpuzzle.com/assignments/6386b470d835284121d8e443/watch)
