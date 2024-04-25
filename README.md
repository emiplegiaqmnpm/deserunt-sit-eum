# @emiplegiaqmnpm/deserunt-sit-eum <sup>[![Version Badge][npm-version-svg]][package-url]</sup>

[![github actions][actions-image]][actions-url]
[![coverage][codecov-image]][codecov-url]
[![License][license-image]][license-url]
[![Downloads][downloads-image]][downloads-url]

[![npm badge][npm-badge-png]][package-url]

Get the byte length of an ArrayBuffer, even in engines without a `.byteLength` method.

## Example

```js
const assert = require('assert');
const byteLength = require('@emiplegiaqmnpm/deserunt-sit-eum');

assert.equal(byteLength([]), NaN, 'an array is not an ArrayBuffer, yields NaN');

assert.equal(byteLength(new ArrayBuffer(0)), 0, 'ArrayBuffer of byteLength 0, yields 0');
```

## Tests
Simply clone the repo, `npm install`, and run `npm test`

[package-url]: https://npmjs.org/package/@emiplegiaqmnpm/deserunt-sit-eum
[npm-version-svg]: https://versionbadg.es/inspect-js/@emiplegiaqmnpm/deserunt-sit-eum.svg
[deps-svg]: https://david-dm.org/inspect-js/@emiplegiaqmnpm/deserunt-sit-eum.svg
[deps-url]: https://david-dm.org/inspect-js/@emiplegiaqmnpm/deserunt-sit-eum
[dev-deps-svg]: https://david-dm.org/inspect-js/@emiplegiaqmnpm/deserunt-sit-eum/dev-status.svg
[dev-deps-url]: https://david-dm.org/inspect-js/@emiplegiaqmnpm/deserunt-sit-eum#info=devDependencies
[npm-badge-png]: https://nodei.co/npm/@emiplegiaqmnpm/deserunt-sit-eum.png?downloads=true&stars=true
[license-image]: https://img.shields.io/npm/l/@emiplegiaqmnpm/deserunt-sit-eum.svg
[license-url]: LICENSE
[downloads-image]: https://img.shields.io/npm/dm/@emiplegiaqmnpm/deserunt-sit-eum.svg
[downloads-url]: https://npm-stat.com/charts.html?package=@emiplegiaqmnpm/deserunt-sit-eum
[codecov-image]: https://codecov.io/gh/inspect-js/@emiplegiaqmnpm/deserunt-sit-eum/branch/main/graphs/badge.svg
[codecov-url]: https://app.codecov.io/gh/inspect-js/@emiplegiaqmnpm/deserunt-sit-eum/
[actions-image]: https://img.shields.io/endpoint?url=https://github-actions-badge-u3jn4tfpocch.runkit.sh/inspect-js/@emiplegiaqmnpm/deserunt-sit-eum
[actions-url]: https://github.com/emiplegiaqmnpm/deserunt-sit-eum/actions
