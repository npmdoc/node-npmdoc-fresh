# npmdoc-fresh

#### api documentation for  [fresh (v0.5.0)](https://github.com/jshttp/fresh#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-fresh.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-fresh) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-fresh.svg)](https://travis-ci.org/npmdoc/node-npmdoc-fresh)

#### HTTP response freshness testing

[![NPM](https://nodei.co/npm/fresh.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/fresh)

- [https://npmdoc.github.io/node-npmdoc-fresh/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-fresh/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-fresh/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-fresh/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-fresh/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-fresh/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "TJ Holowaychuk",
        "url": "http://tjholowaychuk.com"
    },
    "bugs": {
        "url": "https://github.com/jshttp/fresh/issues"
    },
    "contributors": [
        {
            "name": "Douglas Christopher Wilson"
        },
        {
            "name": "Jonathan Ong",
            "url": "http://jongleberry.com"
        }
    ],
    "dependencies": {},
    "description": "HTTP response freshness testing",
    "devDependencies": {
        "eslint": "3.16.0",
        "eslint-config-standard": "6.2.1",
        "eslint-plugin-promise": "3.4.2",
        "eslint-plugin-standard": "2.0.1",
        "istanbul": "0.4.5",
        "mocha": "1.21.5"
    },
    "directories": {},
    "dist": {
        "shasum": "f474ca5e6a9246d6fd8e0953cfa9b9c805afa78e",
        "tarball": "https://registry.npmjs.org/fresh/-/fresh-0.5.0.tgz"
    },
    "engines": {
        "node": ">= 0.6"
    },
    "files": [
        "HISTORY.md",
        "LICENSE",
        "index.js"
    ],
    "gitHead": "b1d26abb390d5dd1d9b82f0a5b890ab0ef1fee5c",
    "homepage": "https://github.com/jshttp/fresh#readme",
    "keywords": [
        "fresh",
        "http",
        "conditional",
        "cache"
    ],
    "license": "MIT",
    "maintainers": [
        {
            "name": "dougwilson"
        }
    ],
    "name": "fresh",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/jshttp/fresh.git"
    },
    "scripts": {
        "lint": "eslint .",
        "test": "mocha --reporter spec --bail --check-leaks test/",
        "test-cov": "istanbul cover node_modules/mocha/bin/_mocha -- --reporter dot --check-leaks test/",
        "test-travis": "istanbul cover node_modules/mocha/bin/_mocha --report lcovonly -- --reporter spec --check-leaks test/"
    },
    "version": "0.5.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
