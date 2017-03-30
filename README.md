## eslint-plugin-tap-given

[![Build Status](https://secure.travis-ci.org/dex4er/js-eslint-plugin-tap-given.svg)](http://travis-ci.org/dex4er/js-eslint-plugin-tap-given) [![npm](https://img.shields.io/npm/v/eslint-plugin-tap-given.svg)](https://www.npmjs.com/package/eslint-plugin-tap-given)

This module provides plugin which defines global symbols from
[tap-given](https://www.npmjs.com/package/tap-given) for
[eslint](https://www.npmjs.com/package/eslint) and
[standard](https://www.npmjs.com/package/standard)

### Installation

```shell
npm install eslint-plugin-tap-given
```

### Usage

In `package.json`:

```js
{
  "standard": {
    "plugins": [ "tap-given" ],
    "env": [ "tap-given/tap-given" ]
  }
}
```

or:

```js
{
  "eslintConfig": {
    "plugins": [ "tap-given" ],
    "env": {
      "tap-given/tap-given": true
    }
  }
}
```

or in any `.js` file:

```js
/* eslint-env tap-given/tap-given */
```

### License

Copyright (c) 2017 Piotr Roszatycki <piotr.roszatycki@gmail.com>

[MIT](https://opensource.org/licenses/MIT)
