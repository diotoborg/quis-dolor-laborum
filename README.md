# @diotoborg/quis-dolor-laborum <sup>[![Version Badge][npm-version-svg]][package-url]</sup>

[![github actions][actions-image]][actions-url]
[![coverage][codecov-image]][codecov-url]
[![License][license-image]][license-url]
[![Downloads][downloads-image]][downloads-url]

[![npm badge][npm-badge-png]][package-url]

Get the byte length of an ArrayBuffer, even in engines without a `.byteLength` method.

## Example

```js
const assert = require('assert');
const byteLength = require('@diotoborg/quis-dolor-laborum');

assert.equal(byteLength([]), NaN, 'an array is not an ArrayBuffer, yields NaN');

assert.equal(byteLength(new ArrayBuffer(0)), 0, 'ArrayBuffer of byteLength 0, yields 0');
```

## Tests
Simply clone the repo, `npm install`, and run `npm test`

[package-url]: https://npmjs.org/package/@diotoborg/quis-dolor-laborum
[npm-version-svg]: https://versionbadg.es/inspect-js/@diotoborg/quis-dolor-laborum.svg
[deps-svg]: https://david-dm.org/inspect-js/@diotoborg/quis-dolor-laborum.svg
[deps-url]: https://david-dm.org/inspect-js/@diotoborg/quis-dolor-laborum
[dev-deps-svg]: https://david-dm.org/inspect-js/@diotoborg/quis-dolor-laborum/dev-status.svg
[dev-deps-url]: https://david-dm.org/inspect-js/@diotoborg/quis-dolor-laborum#info=devDependencies
[npm-badge-png]: https://nodei.co/npm/@diotoborg/quis-dolor-laborum.png?downloads=true&stars=true
[license-image]: https://img.shields.io/npm/l/@diotoborg/quis-dolor-laborum.svg
[license-url]: LICENSE
[downloads-image]: https://img.shields.io/npm/dm/@diotoborg/quis-dolor-laborum.svg
[downloads-url]: https://npm-stat.com/charts.html?package=@diotoborg/quis-dolor-laborum
[codecov-image]: https://codecov.io/gh/inspect-js/@diotoborg/quis-dolor-laborum/branch/main/graphs/badge.svg
[codecov-url]: https://app.codecov.io/gh/inspect-js/@diotoborg/quis-dolor-laborum/
[actions-image]: https://img.shields.io/endpoint?url=https://github-actions-badge-u3jn4tfpocch.runkit.sh/inspect-js/@diotoborg/quis-dolor-laborum
[actions-url]: https://github.com/diotoborg/quis-dolor-laborum/actions
