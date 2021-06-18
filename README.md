# @akiraplusplus/tiny

[![npm (scoped)](https://img.shields.io/badge/npm-4.0-green)](https://www.npmjs.com/package/@akiraplusplus/tiny)

Removes all spaces from a string.

## Install

```
$ npm install @akiraplusplus/tiny
```

## Usage

```js
const tiny = require("@akiraplusplus/tiny");

tiny("So much space!");
//=> "Somuchspace!"

tiny(1337);
//=> Uncaught TypeError: Tiny wants a string!
//    at tiny (<anonymous>:2:41)
//    at <anonymous>:1:1
```