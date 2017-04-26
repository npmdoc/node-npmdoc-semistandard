# npmdoc-semistandard

#### basic api documentation for  [semistandard (v11.0.0)](https://github.com/Flet/semistandard)  [![npm package](https://img.shields.io/npm/v/npmdoc-semistandard.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-semistandard) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-semistandard.svg)](https://travis-ci.org/npmdoc/node-npmdoc-semistandard)

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
        "eslint": "~3.19.0",
        "eslint-config-semistandard": "^11.0.0",
        "eslint-config-standard": "^10.2.1",
        "eslint-config-standard-jsx": "4.0.1",
        "eslint-plugin-import": "~2.2.0",
        "eslint-plugin-node": "~4.2.2",
        "eslint-plugin-promise": "~3.5.0",
        "eslint-plugin-react": "~6.10.0",
        "eslint-plugin-standard": "~3.0.1",
        "standard-engine": "~7.0.0"
    },
    "description": "All the goodness of 'feross/standard' with semicolons sprinkled on top.",
    "devDependencies": {
        "merge": "^1.2.0",
        "mkdirp": "^0.5.1",
        "rimraf": "^2.5.4",
        "run-series": "^1.1.1",
        "standard": "^10.0.0",
        "tape": "^4.6.3",
        "xtend": "^4.0.0"
    },
    "directories": {},
    "dist": {
        "shasum": "d2d9fc8ac393de21312195e006e50c8861391c47",
        "tarball": "https://registry.npmjs.org/semistandard/-/semistandard-11.0.0.tgz"
    },
    "gitHead": "89bafb7187c9db30fc0b4d1c4de0010a2f5145d1",
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
    "version": "11.0.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
