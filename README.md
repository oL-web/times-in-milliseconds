# times-in-milliseconds

An object containting human-readable times in milliseconds. For lazy people who want to write times like ms.SECOND instead of 1000. Runs in both browser and node.js.

## Usage

```javascript
var ms = require("times-in-milliseconds");

var interval = setInterval(function(){}, ms.MINUTE); // 60000 milliseconds, runs once per minute

var interval2 = setInterval(function(){}, ms.HOUR * 4); // 3600000 milliseconds * 4, runs once per 4 hours
```

And so on...
Available properties are MILLISECOND, SECOND, MINUTE, HOUR, DAY and WEEK. These are just numbers so you can add them together or multiply etc.

## Installation

You can install this package from npm:
```bash
npm install times-in-milliseconds
npm install --save times-in-milliseconds
npm install --save-dev times-in-milliseconds
```

## Is there something wrong?

Please tell me!