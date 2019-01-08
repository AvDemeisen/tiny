# tiny

[![npm (scoped)](https://img.shields.io/npm/v/@avdemeisen/tiny.svg)](https://www.npmjs.com/package/@avdemeisen/tiny)
[![npm bundle size (minified)](https://img.shields.io/bundlephobia/min/@avdemeisen/tiny.svg)](https://www.npmjs.com/package/@avdemeisen/tiny)

Removes all spaces from a string.

## Install

```
$ npm install @avdemeisen/tiny
```

## Usage

```js
const tiny = require("@avdemeisen/tiny");

tiny("So much space!");
//=> "Somuchspace!"

tiny(1337);
//=> Uncaught TypeError: Tiny wants a string!
//    at tiny (<anonymous>:2:41)
//    at <anonymous>:1:1
```
