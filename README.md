![npm](https://img.shields.io/npm/v/@vguenoff/tiny)
[![npm bundle size (minified)](https://img.shields.io/bundlephobia/min/@bamblehorse/tiny.svg)](https://www.npmjs.com/package/@vguenoff/tiny)

## Install

```
$ npm install @vguenoff/tiny
```

## Usage

```js
const tiny = require('@vguenoff/tiny');

tiny('So much space!');
//=> "Somuchspace!"

tiny(1337);
//=> Uncaught TypeError: Tiny wants a string!
//    at tiny (<anonymous>:2:41)
```
