[build-badge]:    https://travis-ci.org/pelevesque-node/canonicalize-string.svg?branch=master
[build]:          https://travis-ci.org/pelevesque-node/canonicalize-string
[coverage-badge]: https://coveralls.io/repos/github/pelevesque-node/canonicalize-string/badge.svg?branch=master
[coverage]:       https://coveralls.io/github/pelevesque-node/canonicalize-string?branch=master
[standard-badge]: https://img.shields.io/badge/code_style-standard-brightgreen.svg
[standard]:       https://standardjs.com
[mit-badge]:      https://img.shields.io/badge/License-MIT-yellow.svg
[mit]:            http://opensource.org/licenses/MIT

[![][build-badge]][build]
[![][coverage-badge]][coverage]
[![][standard-badge]][standard]
[![][mit-badge]][mit]

# canonicalize-string

Canonicalizes a UTF-8 string.

canonicalize-string converts a string to lowercase, removes diacritics, then
removes homoglyphs including graphemes.

## Node Repository

https://www.npmjs.com/package/@pelevesque/canonicalize-string

## Installation

`npm install @pelevesque/canonicalize-string`

## Tests

Command                      | Description
---------------------------- | ----------------------
`npm test` or `npm run test` | standardx + unit tests
`npm run cover`              | unit tests + coverage
`npm run standardx`          | standardx
`npm run unit`               | unit tests

## Usage

```js
const canonicalizeString = require('@pelevesque/canonicalize-string')
```

```js
const str = 'AmwÉ'
const result = canonicalizeString(str)
// result === arnwe
```

## Copyright

Copyright (c) 2018-2020, Pierre-Emmanuel Lévesque

## License

MIT

<div align="center">
  <sub>Built with ❤︎ by <a href="https://github.com/pelevesque">Pierre-Emmanuel Lévesque</a></sub>
</div>
