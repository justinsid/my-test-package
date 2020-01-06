# @jwsid/my-test-package

[![npm (scoped)](https://img.shields.io/npm/v/@jwsid/my-test-package)](https://github.com/justinsid/my-test-package)
[![npm bundle size](https://img.shields.io/bundlephobia/min/my-test-package?color=orange)](https://github.com/justinsid/my-test-package)

Removes all spaces from a string.

## Install

```
$ npm install @jwsid/my-test-package
```

## Usage

```js
const my-test-package = require("@jwsid/my-test-package");

my-test-package("So much space!");
//=> "Somuchspace!"

my-test-package(1337);
//=> Uncaught TypeError: my-test-package wants a string!
//    at my-test-package (<anonymous>:2:41)
//    at <anonymous>:1:1