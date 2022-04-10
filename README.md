# indicator-text

[![npm version](https://img.shields.io/npm/v/axios.svg?style=flat-square)](https://fozan.gitbook.io/fozan-inc/)

Library for displaying process-bar in text format.

> All products of ФОЗАН inc. on the site: [click here](https://fozan.gitbook.io/fozan-inc/)

## Table of Contents

  - [Features](#features)
  - [Installing](#installing)
  - [Example](#example)
  - [Resources](#resources)
  - [License](#license)

## Features

- Display as a number with a percentage.
- Display with a progress bar in the style of squares.
- Display with a progress bar in the style of stars.

## Installing

Using npm:

```bash
$ npm install indicator-text
```

## Example

To connect the library indicator-text, enter the following text:

```js
const progress = require('indicator-text');
```

Executing `number`&`squares`&`stars` request

```js
const progress = require('indicator-text');

var res1 = progress.number(1, 100);
var res2 = progress.squares(1, 100);
var res3 = progress.stars(1, 100);

console.log(res1, res2, res3); //1% ▫▫▫▫▫▫▫▫▫▫ ☆☆☆☆☆
```

## Resources

* [website](https://fozan.gitbook.io/fozan-inc/)
* [npm](https://www.npmjs.com/package/indicator-text)

## License

[MIT](LICENSE)
