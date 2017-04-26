# npmdoc-measured

#### basic api documentation for  [measured (v1.1.0)](https://github.com/felixge/node-measured)  [![npm package](https://img.shields.io/npm/v/npmdoc-measured.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-measured) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-measured.svg)](https://travis-ci.org/npmdoc/node-npmdoc-measured)

#### This is an alternative port of Coda Hale's metrics library.

[![NPM](https://nodei.co/npm/measured.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/measured)

- [https://npmdoc.github.io/node-npmdoc-measured/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-measured/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-measured/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-measured/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-measured/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-measured/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Felix Geisendörfer",
        "url": "http://debuggable.com/"
    },
    "bugs": {
        "url": "https://github.com/felixge/node-measured/issues"
    },
    "dependencies": {
        "inherits": "^2.0"
    },
    "description": "This is an alternative port of Coda Hale's metrics library.",
    "devDependencies": {
        "jslint": "^0.8",
        "mocha": "^2.1",
        "mochify": "^2.1",
        "sinon": "^1.12"
    },
    "directories": {},
    "dist": {
        "shasum": "7f6a33adee77bc67a1648968c573608c291b9ac4",
        "tarball": "https://registry.npmjs.org/measured/-/measured-1.1.0.tgz"
    },
    "engines": {
        "node": ">= 0.10"
    },
    "files": [
        "index.js",
        "lib",
        "Readme.md",
        "CHANGES.md"
    ],
    "gitHead": "cf158bfe73ff28ad5e23f36e5e8d5055f1651a82",
    "homepage": "https://github.com/felixge/node-measured",
    "license": "MIT",
    "main": "./index",
    "maintainers": [
        {
            "name": "felixge"
        },
        {
            "name": "mantoni"
        }
    ],
    "name": "measured",
    "optionalDependencies": {},
    "repository": {
        "url": "git://github.com/felixge/node-measured.git"
    },
    "scripts": {
        "lint": "jslint --edition=latest --color './**/*.js'",
        "pretest": "npm run lint",
        "test": "npm run test:node && npm run test:browser",
        "test:browser": "mochify './test/**/test-*.js'",
        "test:node": "mocha './test/**/test-*.js'",
        "watch": "npm run test:node -- --watch",
        "wd": "mochify --wd './test/**/test-*.js'"
    },
    "version": "1.1.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
