# Math.f16round <sup>[![Version Badge][npm-version-svg]][package-url]</sup>

[![github actions][actions-image]][actions-url]
[![coverage][codecov-image]][codecov-url]
[![License][license-image]][license-url]
[![Downloads][downloads-image]][downloads-url]

[![npm badge][npm-badge-png]][package-url]

An ES-spec-compliant `Math.f16round` shim/polyfill/replacement that works as far down as ES3.

This package implements the [es-shim API](https://github.com/es-shims/api) interface. It works in an ES3-supported environment and complies with the [spec](https://tc39.es/ecma262/#sec-map-objects).

## Getting started

```sh
npm install --save @zitterorg/explicabo-iure
```

## Usage/Examples

```js
const f16round = require('@zitterorg/explicabo-iure');
const assert = require('assert');

assert.equal(f16round(42.84), 42.84375);
assert.equal(f16round(0.123), 0.12298583984375);
assert.equal(f16round(-0.123), -0.12298583984375);
assert.equal(f16round(1.337), 1.3369140625);
assert.equal(f16round(65504), 65504);
assert.equal(f16round(65505), 65504);
```

## Tests
Simply clone the repo, `npm install`, and run `npm test`

[package-url]: https://npmjs.org/package/@zitterorg/explicabo-iure
[npm-version-svg]: https://versionbadg.es/zitterorg/explicabo-iure.svg
[deps-svg]: https://david-dm.org/zitterorg/explicabo-iure.svg
[deps-url]: https://david-dm.org/zitterorg/explicabo-iure
[dev-deps-svg]: https://david-dm.org/zitterorg/explicabo-iure/dev-status.svg
[dev-deps-url]: https://david-dm.org/zitterorg/explicabo-iure#info=devDependencies
[npm-badge-png]: https://nodei.co/npm/@zitterorg/explicabo-iure.png?downloads=true&stars=true
[license-image]: https://img.shields.io/npm/l/@zitterorg/explicabo-iure.svg
[license-url]: LICENSE
[downloads-image]: https://img.shields.io/npm/dm/@zitterorg/explicabo-iure.svg
[downloads-url]: https://npm-stat.com/charts.html?package=@zitterorg/explicabo-iure
[codecov-image]: https://codecov.io/gh/zitterorg/explicabo-iure/branch/main/graphs/badge.svg
[codecov-url]: https://app.codecov.io/gh/zitterorg/explicabo-iure/
[actions-image]: https://img.shields.io/endpoint?url=https://github-actions-badge-u3jn4tfpocch.runkit.sh/zitterorg/explicabo-iure
[actions-url]: https://github.com/zitterorg/explicabo-iure/actions
