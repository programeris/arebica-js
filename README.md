## arebica-js

Convert Bosnian language text from Latin and Cyrillic script to traditional Arebica script

## Install

```bash
$ npm install arebica-js
```

## Usage

```js
const { convertLatinToArebica, convertCyrillicToArebica } = require("arebica-js")

//for React
import { convertLatinToArebica, convertCyrillicToArebica } = require("arebica-js")

let convertedStringLat = convertLatinToArebica("string")
// => "سترینغ"

let convertedStringCyr = convertCyrillicToArebica("arebica")
// => "آرەبیڄا"
```
