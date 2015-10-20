imacros-autotype
===============
Simple, accurate, typing simulation for iMacros.

Designed to work with [Browserify](http://browserify.org/).


##### This is a port of Michael Monteleone's [jquery.autotype](https://github.com/mmonteleone/jquery.autotype) plugin thus all credits go to him.

# Usage

```javascript
var autotype = require('autotype');
var qwery = require('qwery'); // qwery is a simple selector engine

var inputBox = qwery('#input');
autotype(inputBox, 'Super simple!');
```
