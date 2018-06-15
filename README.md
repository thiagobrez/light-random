# light-random

Ultra-lightweight, cryptographically weak, alphanumerical, package-independent random string generator.

### Installation

`npm install --save light-random`

or

`yarn add light-random`

### API

**`lightRandom(length: number): string`**

### Usage

```javascript
var lightRandom = require('light-random');

lightRandom();
//default length: 8
//outputs 'bkiVCGkd'

lightRandom(15);
//outputs 'NPf78EK3oNPiU3t'
```

### License

MIT.