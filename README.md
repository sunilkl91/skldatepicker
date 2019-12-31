# @sunilkl91/skldatepicker

Removes all spaces from a string.

## Install

```
$ npm install @sunilkl91/skldatepicker
```

## Usage

```js
const skldatepicker = require("@sunilkl91/skldatepicker");

skldatepicker("So much space!");
//=> "Somuchspace!"

skldatepicker(1337);
//=> Uncaught TypeError: skldatepicker wants a string!
//    at skldatepicker (<anonymous>:2:41)
//    at <anonymous>:1:1
```
