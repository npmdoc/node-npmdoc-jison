# npmdoc-jison

#### api documentation for  [jison (v0.4.17)](http://jison.org)  [![npm package](https://img.shields.io/npm/v/npmdoc-jison.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-jison) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-jison.svg)](https://travis-ci.org/npmdoc/node-npmdoc-jison)

#### A parser generator with Bison's API

[![NPM](https://nodei.co/npm/jison.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/jison)

- [https://npmdoc.github.io/node-npmdoc-jison/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-jison/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-jison/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-jison/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-jison/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-jison/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Zach Carter",
        "url": "http://zaa.ch"
    },
    "bin": {
        "jison": "lib/cli.js"
    },
    "bugs": {
        "url": "http://github.com/zaach/jison/issues"
    },
    "dependencies": {
        "JSONSelect": "0.4.0",
        "cjson": "0.3.0",
        "ebnf-parser": "0.1.10",
        "escodegen": "1.3.x",
        "esprima": "1.1.x",
        "jison-lex": "0.3.x",
        "lex-parser": "~0.1.3",
        "nomnom": "1.5.2"
    },
    "description": "A parser generator with Bison's API",
    "devDependencies": {
        "browserify": "2.x.x",
        "jison": "0.4.x",
        "test": "0.6.x",
        "uglify-js": "~2.4.0"
    },
    "directories": {},
    "dist": {
        "shasum": "bc12d46c5845e6fee89ccf35bd2a8cc73eba17f3",
        "tarball": "https://registry.npmjs.org/jison/-/jison-0.4.17.tgz"
    },
    "engines": {
        "node": ">=0.4"
    },
    "gitHead": "9f2f188419f7790a46a5e9a6c882834d0fa16314",
    "homepage": "http://jison.org",
    "keywords": [
        "jison",
        "bison",
        "yacc",
        "parser",
        "generator",
        "lexer",
        "flex",
        "tokenizer",
        "compiler"
    ],
    "license": "MIT",
    "main": "lib/jison",
    "maintainers": [
        {
            "name": "zaach"
        }
    ],
    "name": "jison",
    "optionalDependencies": {},
    "preferGlobal": true,
    "repository": {
        "type": "git",
        "url": "git://github.com/zaach/jison.git"
    },
    "scripts": {
        "test": "node tests/all-tests.js"
    },
    "version": "0.4.17"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
