# genomatic

[![Build Status](https://secure.travis-ci.org/hiddentao/genomatic.png)](http://travis-ci.org/hiddentao/genomatic)

Utility methods for working with Generator functions, such as bind(), is(), etc.

## Features

* Browser-friendly
* No other dependencies

## Installation

**This package requires Node 4 or above**

```bash
$ npm install genomatic
```

## API

* **genomatic.isGenFn(fn)**
  * Returns `true` if `fn` is a generator function, `false` otherwise.

* **genomatic.bind(fn, ctx)**
  * Bind `fn` to `ctx`, and return the bound function.
  * If `fn` is a generator function the a generator function is returned.
  * If `fn` is not a generator function then a non-generator function is returned.

## Building

To run the tests:

    $ npm install
    $ npm test

## Contributing

Contributions are welcome! Please see [CONTRIBUTING.md](https://github.com/hiddentao/genomatic/blob/master/CONTRIBUTING.md).

## License

MIT - see [LICENSE.md](https://github.com/hiddentao/genomatic/blob/master/LICENSE.md)

