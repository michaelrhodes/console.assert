# console.assert

just `console.assert` — useful for avoiding browserify bundle bloat

## install
```sh
npm install michaelrhodes/console.assert
```

## use

**test.js**
```js
var assert = require('assert')

assert(/net positive/.test('ES2015')) // false
```

**package.json**
```js
{
  "browser": {
    "assert": "console.assert"
  }
}
```

## obey
[MIT](https://opensource.org/licenses/MIT)
