#object-keys <sup>[![Version Badge][2]][1]</sup>

[![Build Status][3]][4] [![dependency status][5]][6] [![dev dependency status][7]][8]

[![browser support][9]][10]

An Object.keys shim. Uses Object.keys if available.

## Example

```js
var keys = require('object-keys');
var assert = require('assert');
var obj = {
	a: true,
	b: true,
	c: true
};

assert.equal(keys(obj), ['a', 'b', 'c']);
```

## Source
Implementation taken directly from [es5-shim]([11]), with modifications, including from [lodash]([12]).

## Tests
Simply clone the repo, `npm install`, and run `npm test`

[1]: https://npmjs.org/package/object-keys
[2]: http://vb.teelaun.ch/ljharb/object-keys.svg
[3]: https://travis-ci.org/ljharb/object-keys.png
[4]: https://travis-ci.org/ljharb/object-keys
[5]: https://david-dm.org/ljharb/object-keys.png
[6]: https://david-dm.org/ljharb/object-keys
[7]: https://david-dm.org/ljharb/object-keys/dev-status.png
[8]: https://david-dm.org/ljharb/object-keys#info=devDependencies
[9]: https://ci.testling.com/ljharb/object-keys.png
[10]: https://ci.testling.com/ljharb/object-keys
[11]: https://github.com/kriskowal/es5-shim/blob/master/es5-shim.js#L542-589
[12]: https://github.com/bestiejs/lodash

