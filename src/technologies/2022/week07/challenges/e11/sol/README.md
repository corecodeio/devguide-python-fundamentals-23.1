# Object Oriented Piracy

## Solution 😎

```javascript
function Ship(draft,crew) { 
  this.draft = draft;
  this.crew = crew;
  
  this.isWorthIt = function (){
    return (this.draft - this.crew * 1.5) > 20;
  }
}
```

## Video Solution 📹

[Object Oriented Piracy](https://edpuzzle.com/assignments/63be1fac7b20954154140ad6/watch)
