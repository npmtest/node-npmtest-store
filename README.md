# npmtest-store

#### basic test coverage for  [store (v2.0.4)](https://github.com/marcuswestin/store.js#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-store.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-store) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-store.svg)](https://travis-ci.org/npmtest/node-npmtest-store)

#### A localStorage wrapper for all browsers without using cookies or flash. Uses localStorage, globalStorage, and userData behavior under the hood

[![NPM](https://nodei.co/npm/store.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/store)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-store/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-store/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-store/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-store/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-store/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-store/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-store/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-store/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-store/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-store/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-store/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-store/build/test-report.html](https://npmtest.github.io/node-npmtest-store/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-store/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-store/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-store/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-store/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-store/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-store/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-store/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-store/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Marcus Westin"
    },
    "bugs": {
        "url": "http://github.com/marcuswestin/store.js/issues"
    },
    "dependencies": {},
    "description": "A localStorage wrapper for all browsers without using cookies or flash. Uses localStorage, globalStorage, and userData behavior under the hood",
    "devDependencies": {
        "babel-preset-es2015": "^6.22.0",
        "babelify": "^7.3.0",
        "browserify": "^14.1.0",
        "budo": "^7.1.0",
        "eslint": "^3.12.2",
        "lodash": "^3.10.1",
        "ngrok": "^2.2.6",
        "node-localstorage": "^0.6.0",
        "request": "^2.67.0",
        "tinytest": "^1.1.3",
        "uglify-js": "^2.7.5"
    },
    "directories": {
        "lib": "."
    },
    "dist": {
        "shasum": "6c6819602a5497166ade85db2442cc64ebcc5761",
        "tarball": "https://registry.npmjs.org/store/-/store-2.0.4.tgz"
    },
    "engines": {
        "node": "*"
    },
    "eslintConfig": {
        "env": {
            "browser": true,
            "commonjs": true,
            "es6": true,
            "node": true
        },
        "extends": "eslint:recommended",
        "parserOptions": {
            "sourceType": "module"
        },
        "globals": {
            "test": false,
            "assert": false,
            "print": false
        },
        "rules": {
            "no-unused-vars": [
                "error",
                {
                    "vars": "all",
                    "args": "none",
                    "varsIgnorePattern": "^_$"
                }
            ],
            "indent": [
                "error",
                "tab"
            ],
            "linebreak-style": [
                "error",
                "unix"
            ],
            "semi": [
                "error",
                "never"
            ]
        }
    },
    "gitHead": "4fbbc9692ceaf16824ac2b11008a878caedffd85",
    "homepage": "https://github.com/marcuswestin/store.js#readme",
    "license": "MIT",
    "main": "dist/store.legacy.js",
    "maintainers": [
        {
            "name": "marcuswestin"
        }
    ],
    "name": "store",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/marcuswestin/store.js.git"
    },
    "scripts": {
        "test": "make test"
    },
    "version": "2.0.4",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
