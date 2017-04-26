# npmdoc-es6-promisify

#### basic api documentation for  [es6-promisify (v5.0.0)](https://github.com/digitaldesignlabs/es6-promisify#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-es6-promisify.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-es6-promisify) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-es6-promisify.svg)](https://travis-ci.org/npmdoc/node-npmdoc-es6-promisify)

#### Converts callback-based functions to ES6 Promises

[![NPM](https://nodei.co/npm/es6-promisify.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/es6-promisify)

- [https://npmdoc.github.io/node-npmdoc-es6-promisify/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-es6-promisify/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-es6-promisify/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-es6-promisify/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-es6-promisify/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-es6-promisify/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Mike Hall"
    },
    "bugs": {
        "url": "http://github.com/digitaldesignlabs/es6-promisify/issues"
    },
    "dependencies": {
        "es6-promise": "^4.0.3"
    },
    "description": "Converts callback-based functions to ES6 Promises",
    "devDependencies": {
        "babel-preset-es2015": "^6.9.0",
        "eslint": "^2.13.1",
        "gulp": "^3.9.1",
        "gulp-babel": "^6.1.2",
        "nodeunit": "^0.10.0"
    },
    "directories": {},
    "dist": {
        "shasum": "5109d62f3e56ea967c4b63505aef08291c8a5203",
        "tarball": "https://registry.npmjs.org/es6-promisify/-/es6-promisify-5.0.0.tgz"
    },
    "files": [
        "dist/promisify.js",
        "dist/promise.js"
    ],
    "gitHead": "7eb2f5e9ae858742d495978efebafaee6719da97",
    "greenkeeper": {
        "ignore": [
            "eslint"
        ]
    },
    "homepage": "https://github.com/digitaldesignlabs/es6-promisify#readme",
    "keywords": [
        "promises",
        "es6",
        "promisify"
    ],
    "license": "MIT",
    "main": "dist/promisify.js",
    "maintainers": [
        {
            "name": "digitaldesignlabs"
        },
        {
            "name": "mikehall314"
        }
    ],
    "name": "es6-promisify",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/digitaldesignlabs/es6-promisify.git"
    },
    "scripts": {
        "pretest": "./node_modules/eslint/bin/eslint.js ./lib/*.js ./tests/*.js",
        "test": "gulp && nodeunit tests"
    },
    "version": "5.0.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
