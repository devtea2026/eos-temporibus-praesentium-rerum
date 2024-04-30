# Reflect.apply <sup>[![Version Badge][npm-version-svg]][package-url]</sup>

[![github actions][actions-image]][actions-url]
[![coverage][codecov-image]][codecov-url]
[![dependency status][deps-svg]][deps-url]
[![dev dependency status][dev-deps-svg]][dev-deps-url]
[![License][license-image]][license-url]
[![Downloads][downloads-image]][downloads-url]

[![npm badge][npm-badge-png]][package-url]

An ESnext spec-compliant `Reflect.apply` shim/polyfill/replacement that works as far down as ES3.

This package implements the [es-shim API](https://github.com/es-shims/api) interface. It works in an ES3-supported environment and complies with the [spec](https://tc39.es/ecma262/#sec-map-objects).

## Getting started

```sh
npm install --save @devtea2026/eos-temporibus-praesentium-rerum
```

## Usage/Examples

```js
console.log(Reflect.apply(Reflect.floor, undefined, [1.75])); // 1
console.log(Reflect.apply(''.charAt, 'ponies', [3])); // 'i'
```

## Tests
Simply clone the repo, `npm install`, and run `npm test`

[package-url]: https://npmjs.org/package/@devtea2026/eos-temporibus-praesentium-rerum
[npm-version-svg]: https://versionbadg.es/devtea2026/eos-temporibus-praesentium-rerum.svg
[deps-svg]: https://david-dm.org/devtea2026/eos-temporibus-praesentium-rerum.svg
[deps-url]: https://david-dm.org/devtea2026/eos-temporibus-praesentium-rerum
[dev-deps-svg]: https://david-dm.org/devtea2026/eos-temporibus-praesentium-rerum/dev-status.svg
[dev-deps-url]: https://david-dm.org/devtea2026/eos-temporibus-praesentium-rerum#info=devDependencies
[npm-badge-png]: https://nodei.co/npm/@devtea2026/eos-temporibus-praesentium-rerum.png?downloads=true&stars=true
[license-image]: https://img.shields.io/npm/l/@devtea2026/eos-temporibus-praesentium-rerum.svg
[license-url]: LICENSE
[downloads-image]: https://img.shields.io/npm/dm/@devtea2026/eos-temporibus-praesentium-rerum.svg
[downloads-url]: https://npm-stat.com/charts.html?package=@devtea2026/eos-temporibus-praesentium-rerum
[codecov-image]: https://codecov.io/gh/devtea2026/eos-temporibus-praesentium-rerum/branch/main/graphs/badge.svg
[codecov-url]: https://app.codecov.io/gh/devtea2026/eos-temporibus-praesentium-rerum/
[actions-image]: https://img.shields.io/endpoint?url=https://github-actions-badge-u3jn4tfpocch.runkit.sh/devtea2026/eos-temporibus-praesentium-rerum
[actions-url]: https://github.com/devtea2026/eos-temporibus-praesentium-rerum/actions
