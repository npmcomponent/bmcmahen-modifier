*This repository is a mirror of the [component](http://component.io) module [bmcmahen/modifier](http://github.com/bmcmahen/modifier). It has been modified to work with NPM+Browserify. You can install it using the command `npm install npmcomponent/bmcmahen-modifier`. Please do not open issues or send pull requests against this repo. If you have issues with this repo, report it to [npmcomponent](https://github.com/airportyh/npmcomponent).*

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
