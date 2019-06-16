[![Build Status](https://travis-ci.org/pelevesque/canonicalize-string.svg?branch=master)](https://travis-ci.org/pelevesque/canonicalize-string)
[![Coverage Status](https://coveralls.io/repos/github/pelevesque/canonicalize-string/badge.svg?branch=master)](https://coveralls.io/github/pelevesque/canonicalize-string?branch=master)
[![JavaScript Style Guide](https://img.shields.io/badge/code_style-standard-brightgreen.svg)](https://standardjs.com)

# canonicalize-string

Canonicalizes a UTF-8 string.

canonicalize-string converts a string to lowercase, removes diacritics, then
removes homoglyphs including graphemes.

## Node Repository

https://www.npmjs.com/package/@pelevesque/canonicalize-string

## Installation

`npm install @pelevesque/canonicalize-string`

## Tests

### Standard Style & Unit Tests

`npm test`

### Unit Tests & Coverage

`npm run cover`

## Usage

```js
const canonicalizeString = require('@pelevesque/canonicalize-string')
```

```js
const str = 'AmwÉ'
const result = canonicalizeString(str)
// result === arnvve
```
