# npmdoc-babel-tape-runner

#### api documentation for  [babel-tape-runner (v2.0.1)](https://github.com/wavded/babel-tape-runner)  [![npm package](https://img.shields.io/npm/v/npmdoc-babel-tape-runner.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-babel-tape-runner) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-babel-tape-runner.svg)](https://travis-ci.org/npmdoc/node-npmdoc-babel-tape-runner)

#### Babel + Tape for running your ES Next tests

[![NPM](https://nodei.co/npm/babel-tape-runner.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/babel-tape-runner)

- [https://npmdoc.github.io/node-npmdoc-babel-tape-runner/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-babel-tape-runner/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-babel-tape-runner/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-babel-tape-runner/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-babel-tape-runner/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-babel-tape-runner/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "babel-tape-runner",
    "version": "2.0.1",
    "description": "Babel + Tape for running your ES Next tests",
    "bin": "./bin/babel-tape-runner",
    "repository": {
        "type": "git",
        "url": "https://github.com/wavded/babel-tape-runner.git"
    },
    "scripts": {
        "pretest": "cp .testbabelrc .babelrc",
        "test": "standard bin/babel-tape-runner test.js && node bin/babel-tape-runner test.js",
        "posttest": "rm .babelrc"
    },
    "keywords": [
        "babel",
        "tape",
        "tests",
        "testing",
        "harmony",
        "es6",
        "esnext"
    ],
    "author": "Marc Harter <wavded@gmail.com>",
    "license": "MIT",
    "bugs": {
        "url": "https://github.com/wavded/babel-tape-runner/issues"
    },
    "homepage": "https://github.com/wavded/babel-tape-runner",
    "dependencies": {
        "babel-polyfill": "^6.3.14",
        "babel-register": "^6.3.13",
        "glob": "^6.0.1"
    },
    "devDependencies": {
        "babel-preset-es2015": "^6.3.13",
        "standard": "^5.0.0",
        "tape": "^4.0.2"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
