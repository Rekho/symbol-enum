# Javascript enum

Enum type based on symbols. Using symbol values ensure type safety of the enum as each symbol value is unique.

Example:
```javascript
let color = new Enum('RED', 'GREEN');
console.log('Red value symbol: ' + color.RED.toString() + '<br>'); // Symbol(RED)
console.log('Red value name: ' + color.getName(color.RED) + '<br>');// RED
console.log('Size: ' + color.size + '<br>'); // 2
console.log('Values: ' + color.values() + '<br>'); // Symbol(RED), Symbol(GREEN)
console.log('All names: ' + color.toString()); // RED,GREEN
```

[Plunker demo](http://plnkr.co/edit/2RjZuQ1LNl8UI6nMlbOk?p=preview)
