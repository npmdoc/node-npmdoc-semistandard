# npmdoc-semistandard

#### api documentation for  [semistandard (v10.0.0)](https://github.com/Flet/semistandard)  [![npm package](https://img.shields.io/npm/v/npmdoc-semistandard.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-semistandard) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-semistandard.svg)](https://travis-ci.org/npmdoc/node-npmdoc-semistandard)

#### All the goodness of `feross/standard` with semicolons sprinkled on top.

[![NPM](https://nodei.co/npm/semistandard.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/semistandard)

- [https://npmdoc.github.io/node-npmdoc-semistandard/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-semistandard/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-semistandard/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-semistandard/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-semistandard/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-semistandard/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Dan Flettre",
        "url": "http://twitter.com/flettre"
    },
    "bin": {
        "semistandard": "./bin/cmd.js"
    },
    "bugs": {
        "url": "https://github.com/Flet/semistandard/issues"
    },
    "dependencies": {
        "eslint": "~3.15.0",
        "eslint-config-semistandard": "8.0.0",
        "eslint-config-standard": "7.0.0",
        "eslint-config-standard-jsx": "3.3.0",
        "eslint-plugin-promise": "~3.4.0",
        "eslint-plugin-react": "~6.9.0",
        "eslint-plugin-standard": "~2.0.1",
        "standard-engine": "~5.4.0"
    },
    "description": "All the goodness of 'feross/standard' with semicolons sprinkled on top.",
    "devDependencies": {
        "merge": "^1.2.0",
        "mkdirp": "^0.5.1",
        "rimraf": "^2.5.4",
        "run-series": "^1.1.1",
        "standard": "^8.6.0",
        "tape": "^4.6.3",
        "xtend": "^4.0.0"
    },
    "directories": {},
    "dist": {
        "shasum": "d6894f7673b9b737c262dca94cadf35e8392dde9",
        "tarball": "https://registry.npmjs.org/semistandard/-/semistandard-10.0.0.tgz"
    },
    "gitHead": "a888e2f74c5e75c00a1df7df4ef4509ebb2871c0",
    "homepage": "https://github.com/Flet/semistandard",
    "keywords": [
        "JavaScript Standard Style",
        "bikeshed",
        "check",
        "checker",
        "code",
        "code checker",
        "code linter",
        "code standards",
        "code style",
        "enforce",
        "eslint",
        "hint",
        "jscs",
        "jshint",
        "lint",
        "policy",
        "quality",
        "semicolon",
        "simple",
        "standard",
        "standard style",
        "style",
        "style checker",
        "style linter",
        "verify"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "flet"
        }
    ],
    "name": "semistandard",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/Flet/semistandard.git"
    },
    "scripts": {
        "test": "standard && tape test/*.js"
    },
    "standard": {
        "ignore": "tmp/**"
    },
    "version": "10.0.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
