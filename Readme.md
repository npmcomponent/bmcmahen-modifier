
# modifier

  check if the keyup event is a modifier.

## Installation

  Install with [component(1)](http://component.io):

    $ component install bmcmahen/modifier

## Usage

```javascript
var isModifier = require('modifier');
el.onkeyup = function(e){
  if (isModifier(e)) {
    console.log(' i am a modifier! ');
  }
};
```

## License

  MIT
