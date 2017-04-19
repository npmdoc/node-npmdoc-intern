# npmdoc-intern

#### api documentation for  [intern (v3.4.3)](http://theintern.io/)  [![npm package](https://img.shields.io/npm/v/npmdoc-intern.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-intern) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-intern.svg)](https://travis-ci.org/npmdoc/node-npmdoc-intern)

#### Intern. A next-generation code testing stack for JavaScript.

[![NPM](https://nodei.co/npm/intern.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/intern)

- [https://npmdoc.github.io/node-npmdoc-intern/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-intern/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-intern/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-intern/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-intern/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-intern/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "bin": {
        "intern-client": "./bin/intern-client.js",
        "intern-runner": "./bin/intern-runner.js"
    },
    "bugs": {
        "url": "https://github.com/theintern/intern/issues"
    },
    "dependencies": {
        "@types/chai": "3.4.34",
        "@types/node": "6.0.48",
        "benchmark": "2.1.1",
        "chai": "3.5.0",
        "charm": "0.2.0",
        "diff": "1.1.0",
        "digdug": "~1.6.0",
        "dojo": "2.0.0-alpha.7",
        "glob": "7.0.3",
        "istanbul": "0.4.1",
        "leadfoot": "~1.7.0",
        "lodash-amd": "4.16.4",
        "mimetype": "0.0.8",
        "platform": "1.3.1",
        "source-map": "0.1.33"
    },
    "description": "Intern. A next-generation code testing stack for JavaScript.",
    "devDependencies": {
        "intern": "3.2.3"
    },
    "directories": {},
    "dist": {
        "shasum": "88f6019c6b276ad020d4437794708c824a710074",
        "tarball": "https://registry.npmjs.org/intern/-/intern-3.4.3.tgz"
    },
    "files": [
        "bin",
        "chai.js",
        "client.html",
        "client.js",
        "lib",
        "main.js",
        "order.js",
        "runner.js",
        "support/fixdeps.js",
        "tasks",
        "tests/example.intern.js",
        "typings"
    ],
    "gitHead": "42c66b61acb6495331d32a3a1eae7e2bec43d828",
    "homepage": "http://theintern.io/",
    "keywords": [
        "javascript",
        "test",
        "unit",
        "testing",
        "ci",
        "continuous integration",
        "bdd",
        "tdd",
        "xunit",
        "istanbul",
        "chai",
        "dojo",
        "toolkit",
        "selenium",
        "sauce labs",
        "code coverage"
    ],
    "license": "BSD-3-Clause",
    "main": "./main.js",
    "maintainers": [
        {
            "name": "sitepen"
        },
        {
            "name": "jason0x43"
        },
        {
            "name": "csnover"
        }
    ],
    "name": "intern",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/theintern/intern.git"
    },
    "scripts": {
        "install": "node support/fixdeps.js",
        "release": "node support/release.js",
        "test": "node support/test.js",
        "update": "node support/fixdeps.js"
    },
    "types": "./typings/intern/intern.d.ts",
    "version": "3.4.3"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
