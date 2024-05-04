# @xdanangelxoqenpm/voluptatum-eaque-accusantium <sup>[![Version Badge][npm-version-svg]][package-url]</sup>

[![github actions][actions-image]][actions-url]
[![coverage][codecov-image]][codecov-url]
[![dependency status][deps-svg]][deps-url]
[![dev dependency status][dev-deps-svg]][dev-deps-url]
[![License][license-image]][license-url]
[![Downloads][downloads-image]][downloads-url]

[![npm badge][npm-badge-png]][package-url]

Is this value negative zero? === will lie to you.

## Example

```js
var isNegativeZero = require('@xdanangelxoqenpm/voluptatum-eaque-accusantium');
var assert = require('assert');

assert.notOk(isNegativeZero(undefined));
assert.notOk(isNegativeZero(null));
assert.notOk(isNegativeZero(false));
assert.notOk(isNegativeZero(true));
assert.notOk(isNegativeZero(0));
assert.notOk(isNegativeZero(42));
assert.notOk(isNegativeZero(Infinity));
assert.notOk(isNegativeZero(-Infinity));
assert.notOk(isNegativeZero(NaN));
assert.notOk(isNegativeZero('foo'));
assert.notOk(isNegativeZero(function () {}));
assert.notOk(isNegativeZero([]));
assert.notOk(isNegativeZero({}));

assert.ok(isNegativeZero(-0));
```

## Tests
Simply clone the repo, `npm install`, and run `npm test`

[package-url]: https://npmjs.org/package/@xdanangelxoqenpm/voluptatum-eaque-accusantium
[npm-version-svg]: https://versionbadg.es/inspect-js/@xdanangelxoqenpm/voluptatum-eaque-accusantium.svg
[deps-svg]: https://david-dm.org/inspect-js/@xdanangelxoqenpm/voluptatum-eaque-accusantium.svg
[deps-url]: https://david-dm.org/inspect-js/@xdanangelxoqenpm/voluptatum-eaque-accusantium
[dev-deps-svg]: https://david-dm.org/inspect-js/@xdanangelxoqenpm/voluptatum-eaque-accusantium/dev-status.svg
[dev-deps-url]: https://david-dm.org/inspect-js/@xdanangelxoqenpm/voluptatum-eaque-accusantium#info=devDependencies
[npm-badge-png]: https://nodei.co/npm/@xdanangelxoqenpm/voluptatum-eaque-accusantium.png?downloads=true&stars=true
[license-image]: https://img.shields.io/npm/l/@xdanangelxoqenpm/voluptatum-eaque-accusantium.svg
[license-url]: LICENSE
[downloads-image]: https://img.shields.io/npm/dm/@xdanangelxoqenpm/voluptatum-eaque-accusantium.svg
[downloads-url]: https://npm-stat.com/charts.html?package=@xdanangelxoqenpm/voluptatum-eaque-accusantium
[codecov-image]: https://codecov.io/gh/inspect-js/@xdanangelxoqenpm/voluptatum-eaque-accusantium/branch/main/graphs/badge.svg
[codecov-url]: https://app.codecov.io/gh/inspect-js/@xdanangelxoqenpm/voluptatum-eaque-accusantium/
[actions-image]: https://img.shields.io/endpoint?url=https://github-actions-badge-u3jn4tfpocch.runkit.sh/inspect-js/@xdanangelxoqenpm/voluptatum-eaque-accusantium
[actions-url]: https://github.com/xdanangelxoqenpm/voluptatum-eaque-accusantium/actions
