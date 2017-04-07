# api documentation for  [jison (v0.4.17)](http://jison.org)  [![npm package](https://img.shields.io/npm/v/npmdoc-jison.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-jison) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-jison.svg)](https://travis-ci.org/npmdoc/node-npmdoc-jison)
#### A parser generator with Bison's API

[![NPM](https://nodei.co/npm/jison.png?downloads=true)](https://www.npmjs.com/package/jison)

[![apidoc](https://npmdoc.github.io/node-npmdoc-jison/build/screenCapture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-jison_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-jison/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-jison/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-jison/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Zach Carter",
        "email": "zach@carter.name",
        "url": "http://zaa.ch"
    },
    "bin": {
        "jison": "lib/cli.js"
    },
    "bugs": {
        "url": "http://github.com/zaach/jison/issues",
        "email": "jison@librelist.com"
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
            "name": "zaach",
            "email": "zack.carter@gmail.com"
        }
    ],
    "name": "jison",
    "optionalDependencies": {},
    "preferGlobal": true,
    "readme": "ERROR: No README data found!",
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



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module jison](#apidoc.module.jison)
1.  [function <span class="apidocSignatureSpan">jison.</span>Generator (g, options)](#apidoc.element.jison.Generator)
1.  [function <span class="apidocSignatureSpan">jison.</span>LALRGenerator ()](#apidoc.element.jison.LALRGenerator)
1.  [function <span class="apidocSignatureSpan">jison.</span>LLGenerator ()](#apidoc.element.jison.LLGenerator)
1.  [function <span class="apidocSignatureSpan">jison.</span>LR0Generator ()](#apidoc.element.jison.LR0Generator)
1.  [function <span class="apidocSignatureSpan">jison.</span>LR1Generator ()](#apidoc.element.jison.LR1Generator)
1.  [function <span class="apidocSignatureSpan">jison.</span>Parser (g, options)](#apidoc.element.jison.Parser)
1.  [function <span class="apidocSignatureSpan">jison.</span>SLRGenerator ()](#apidoc.element.jison.SLRGenerator)
1.  [function <span class="apidocSignatureSpan">jison.</span>print ()](#apidoc.element.jison.print)
1.  object <span class="apidocSignatureSpan">jison.</span>Jison
1.  object <span class="apidocSignatureSpan">jison.</span>LALRGenerator.prototype
1.  object <span class="apidocSignatureSpan">jison.</span>LLGenerator.prototype
1.  object <span class="apidocSignatureSpan">jison.</span>LR0Generator.prototype
1.  object <span class="apidocSignatureSpan">jison.</span>LR1Generator.prototype
1.  object <span class="apidocSignatureSpan">jison.</span>SLRGenerator.prototype
1.  object <span class="apidocSignatureSpan">jison.</span>classy
1.  string <span class="apidocSignatureSpan">jison.</span>version

#### [module jison.LALRGenerator](#apidoc.module.jison.LALRGenerator)
1.  [function <span class="apidocSignatureSpan">jison.</span>LALRGenerator ()](#apidoc.element.jison.LALRGenerator.LALRGenerator)
1.  [function <span class="apidocSignatureSpan">jison.LALRGenerator.</span>mix ()](#apidoc.element.jison.LALRGenerator.mix)

#### [module jison.LALRGenerator.prototype](#apidoc.module.jison.LALRGenerator.prototype)
1.  [function <span class="apidocSignatureSpan">jison.LALRGenerator.prototype.</span>constructor ()](#apidoc.element.jison.LALRGenerator.prototype.constructor)

#### [module jison.LLGenerator](#apidoc.module.jison.LLGenerator)
1.  [function <span class="apidocSignatureSpan">jison.</span>LLGenerator ()](#apidoc.element.jison.LLGenerator.LLGenerator)
1.  [function <span class="apidocSignatureSpan">jison.LLGenerator.</span>mix ()](#apidoc.element.jison.LLGenerator.mix)

#### [module jison.LLGenerator.prototype](#apidoc.module.jison.LLGenerator.prototype)
1.  [function <span class="apidocSignatureSpan">jison.LLGenerator.prototype.</span>constructor ()](#apidoc.element.jison.LLGenerator.prototype.constructor)

#### [module jison.LR0Generator](#apidoc.module.jison.LR0Generator)
1.  [function <span class="apidocSignatureSpan">jison.</span>LR0Generator ()](#apidoc.element.jison.LR0Generator.LR0Generator)
1.  [function <span class="apidocSignatureSpan">jison.LR0Generator.</span>mix ()](#apidoc.element.jison.LR0Generator.mix)

#### [module jison.LR0Generator.prototype](#apidoc.module.jison.LR0Generator.prototype)
1.  [function <span class="apidocSignatureSpan">jison.LR0Generator.prototype.</span>constructor ()](#apidoc.element.jison.LR0Generator.prototype.constructor)

#### [module jison.LR1Generator](#apidoc.module.jison.LR1Generator)
1.  [function <span class="apidocSignatureSpan">jison.</span>LR1Generator ()](#apidoc.element.jison.LR1Generator.LR1Generator)
1.  [function <span class="apidocSignatureSpan">jison.LR1Generator.</span>mix ()](#apidoc.element.jison.LR1Generator.mix)

#### [module jison.LR1Generator.prototype](#apidoc.module.jison.LR1Generator.prototype)
1.  [function <span class="apidocSignatureSpan">jison.LR1Generator.prototype.</span>constructor ()](#apidoc.element.jison.LR1Generator.prototype.constructor)

#### [module jison.SLRGenerator](#apidoc.module.jison.SLRGenerator)
1.  [function <span class="apidocSignatureSpan">jison.</span>SLRGenerator ()](#apidoc.element.jison.SLRGenerator.SLRGenerator)
1.  [function <span class="apidocSignatureSpan">jison.SLRGenerator.</span>mix ()](#apidoc.element.jison.SLRGenerator.mix)

#### [module jison.SLRGenerator.prototype](#apidoc.module.jison.SLRGenerator.prototype)
1.  [function <span class="apidocSignatureSpan">jison.SLRGenerator.prototype.</span>constructor ()](#apidoc.element.jison.SLRGenerator.prototype.constructor)
1.  [function <span class="apidocSignatureSpan">jison.SLRGenerator.prototype.</span>lookAheads (state, item)](#apidoc.element.jison.SLRGenerator.prototype.lookAheads)
1.  string <span class="apidocSignatureSpan">jison.SLRGenerator.prototype.</span>type

#### [module jison.classy](#apidoc.module.jison.classy)
1.  [function <span class="apidocSignatureSpan">jison.classy.</span>Parser ()](#apidoc.element.jison.classy.Parser)
1.  [function <span class="apidocSignatureSpan">jison.classy.</span>main (args)](#apidoc.element.jison.classy.main)
1.  [function <span class="apidocSignatureSpan">jison.classy.</span>parse ()](#apidoc.element.jison.classy.parse)
1.  object <span class="apidocSignatureSpan">jison.classy.</span>parser



# <a name="apidoc.module.jison"></a>[module jison](#apidoc.module.jison)

#### <a name="apidoc.element.jison.Generator"></a>[function <span class="apidocSignatureSpan">jison.</span>Generator (g, options)](#apidoc.element.jison.Generator)
- description and source-code
```javascript
function Jison_Generator(g, options) {
    var opt = typal.mix.call({}, g.options, options);
    switch (opt.type) {
        case 'lr0':
            return new LR0Generator(g, opt);
        case 'slr':
            return new SLRGenerator(g, opt);
        case 'lr':
            return new LR1Generator(g, opt);
        case 'll':
            return new LLGenerator(g, opt);
        default:
            return new LALRGenerator(g, opt);
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.jison.LALRGenerator"></a>[function <span class="apidocSignatureSpan">jison.</span>LALRGenerator ()](#apidoc.element.jison.LALRGenerator)
- description and source-code
```javascript
LALRGenerator = function () { return constructor.apply(this, arguments); }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.jison.LLGenerator"></a>[function <span class="apidocSignatureSpan">jison.</span>LLGenerator ()](#apidoc.element.jison.LLGenerator)
- description and source-code
```javascript
LLGenerator = function () { return constructor.apply(this, arguments); }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.jison.LR0Generator"></a>[function <span class="apidocSignatureSpan">jison.</span>LR0Generator ()](#apidoc.element.jison.LR0Generator)
- description and source-code
```javascript
LR0Generator = function () { return constructor.apply(this, arguments); }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.jison.LR1Generator"></a>[function <span class="apidocSignatureSpan">jison.</span>LR1Generator ()](#apidoc.element.jison.LR1Generator)
- description and source-code
```javascript
LR1Generator = function () { return constructor.apply(this, arguments); }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.jison.Parser"></a>[function <span class="apidocSignatureSpan">jison.</span>Parser (g, options)](#apidoc.element.jison.Parser)
- description and source-code
```javascript
function Parser(g, options) {
    var gen = Jison.Generator(g, options);
    return gen.createParser();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.jison.SLRGenerator"></a>[function <span class="apidocSignatureSpan">jison.</span>SLRGenerator ()](#apidoc.element.jison.SLRGenerator)
- description and source-code
```javascript
SLRGenerator = function () { return constructor.apply(this, arguments); }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.jison.print"></a>[function <span class="apidocSignatureSpan">jison.</span>print ()](#apidoc.element.jison.print)
- description and source-code
```javascript
print = function () { [native code] }
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.jison.LALRGenerator"></a>[module jison.LALRGenerator](#apidoc.module.jison.LALRGenerator)

#### <a name="apidoc.element.jison.LALRGenerator.LALRGenerator"></a>[function <span class="apidocSignatureSpan">jison.</span>LALRGenerator ()](#apidoc.element.jison.LALRGenerator.LALRGenerator)
- description and source-code
```javascript
LALRGenerator = function () { return constructor.apply(this, arguments); }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.jison.LALRGenerator.mix"></a>[function <span class="apidocSignatureSpan">jison.LALRGenerator.</span>mix ()](#apidoc.element.jison.LALRGenerator.mix)
- description and source-code
```javascript
function typal_mix() {
    var self = this;
    for(var i=0,o,k; i<arguments.length; i++) {
        o=arguments[i];
        if (!o) continue;
        if (Object.prototype.hasOwnProperty.call(o,'constructor'))
            this.constructor = o.constructor;
        if (Object.prototype.hasOwnProperty.call(o,'toString'))
            this.toString = o.toString;
        for(k in o) {
            if (Object.prototype.hasOwnProperty.call(o, k)) {
                if(k.match(position) && typeof this[k.replace(position, '')] === 'function')
                    layerMethod.call(this, k, o[k]);
                else
                    this[k] = o[k];
            }
        }
    }
    return this;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.jison.LALRGenerator.prototype"></a>[module jison.LALRGenerator.prototype](#apidoc.module.jison.LALRGenerator.prototype)

#### <a name="apidoc.element.jison.LALRGenerator.prototype.constructor"></a>[function <span class="apidocSignatureSpan">jison.LALRGenerator.prototype.</span>constructor ()](#apidoc.element.jison.LALRGenerator.prototype.constructor)
- description and source-code
```javascript
constructor = function () { return constructor.apply(this, arguments); }
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.jison.LLGenerator"></a>[module jison.LLGenerator](#apidoc.module.jison.LLGenerator)

#### <a name="apidoc.element.jison.LLGenerator.LLGenerator"></a>[function <span class="apidocSignatureSpan">jison.</span>LLGenerator ()](#apidoc.element.jison.LLGenerator.LLGenerator)
- description and source-code
```javascript
LLGenerator = function () { return constructor.apply(this, arguments); }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.jison.LLGenerator.mix"></a>[function <span class="apidocSignatureSpan">jison.LLGenerator.</span>mix ()](#apidoc.element.jison.LLGenerator.mix)
- description and source-code
```javascript
function typal_mix() {
    var self = this;
    for(var i=0,o,k; i<arguments.length; i++) {
        o=arguments[i];
        if (!o) continue;
        if (Object.prototype.hasOwnProperty.call(o,'constructor'))
            this.constructor = o.constructor;
        if (Object.prototype.hasOwnProperty.call(o,'toString'))
            this.toString = o.toString;
        for(k in o) {
            if (Object.prototype.hasOwnProperty.call(o, k)) {
                if(k.match(position) && typeof this[k.replace(position, '')] === 'function')
                    layerMethod.call(this, k, o[k]);
                else
                    this[k] = o[k];
            }
        }
    }
    return this;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.jison.LLGenerator.prototype"></a>[module jison.LLGenerator.prototype](#apidoc.module.jison.LLGenerator.prototype)

#### <a name="apidoc.element.jison.LLGenerator.prototype.constructor"></a>[function <span class="apidocSignatureSpan">jison.LLGenerator.prototype.</span>constructor ()](#apidoc.element.jison.LLGenerator.prototype.constructor)
- description and source-code
```javascript
constructor = function () { return constructor.apply(this, arguments); }
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.jison.LR0Generator"></a>[module jison.LR0Generator](#apidoc.module.jison.LR0Generator)

#### <a name="apidoc.element.jison.LR0Generator.LR0Generator"></a>[function <span class="apidocSignatureSpan">jison.</span>LR0Generator ()](#apidoc.element.jison.LR0Generator.LR0Generator)
- description and source-code
```javascript
LR0Generator = function () { return constructor.apply(this, arguments); }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.jison.LR0Generator.mix"></a>[function <span class="apidocSignatureSpan">jison.LR0Generator.</span>mix ()](#apidoc.element.jison.LR0Generator.mix)
- description and source-code
```javascript
function typal_mix() {
    var self = this;
    for(var i=0,o,k; i<arguments.length; i++) {
        o=arguments[i];
        if (!o) continue;
        if (Object.prototype.hasOwnProperty.call(o,'constructor'))
            this.constructor = o.constructor;
        if (Object.prototype.hasOwnProperty.call(o,'toString'))
            this.toString = o.toString;
        for(k in o) {
            if (Object.prototype.hasOwnProperty.call(o, k)) {
                if(k.match(position) && typeof this[k.replace(position, '')] === 'function')
                    layerMethod.call(this, k, o[k]);
                else
                    this[k] = o[k];
            }
        }
    }
    return this;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.jison.LR0Generator.prototype"></a>[module jison.LR0Generator.prototype](#apidoc.module.jison.LR0Generator.prototype)

#### <a name="apidoc.element.jison.LR0Generator.prototype.constructor"></a>[function <span class="apidocSignatureSpan">jison.LR0Generator.prototype.</span>constructor ()](#apidoc.element.jison.LR0Generator.prototype.constructor)
- description and source-code
```javascript
constructor = function () { return constructor.apply(this, arguments); }
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.jison.LR1Generator"></a>[module jison.LR1Generator](#apidoc.module.jison.LR1Generator)

#### <a name="apidoc.element.jison.LR1Generator.LR1Generator"></a>[function <span class="apidocSignatureSpan">jison.</span>LR1Generator ()](#apidoc.element.jison.LR1Generator.LR1Generator)
- description and source-code
```javascript
LR1Generator = function () { return constructor.apply(this, arguments); }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.jison.LR1Generator.mix"></a>[function <span class="apidocSignatureSpan">jison.LR1Generator.</span>mix ()](#apidoc.element.jison.LR1Generator.mix)
- description and source-code
```javascript
function typal_mix() {
    var self = this;
    for(var i=0,o,k; i<arguments.length; i++) {
        o=arguments[i];
        if (!o) continue;
        if (Object.prototype.hasOwnProperty.call(o,'constructor'))
            this.constructor = o.constructor;
        if (Object.prototype.hasOwnProperty.call(o,'toString'))
            this.toString = o.toString;
        for(k in o) {
            if (Object.prototype.hasOwnProperty.call(o, k)) {
                if(k.match(position) && typeof this[k.replace(position, '')] === 'function')
                    layerMethod.call(this, k, o[k]);
                else
                    this[k] = o[k];
            }
        }
    }
    return this;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.jison.LR1Generator.prototype"></a>[module jison.LR1Generator.prototype](#apidoc.module.jison.LR1Generator.prototype)

#### <a name="apidoc.element.jison.LR1Generator.prototype.constructor"></a>[function <span class="apidocSignatureSpan">jison.LR1Generator.prototype.</span>constructor ()](#apidoc.element.jison.LR1Generator.prototype.constructor)
- description and source-code
```javascript
constructor = function () { return constructor.apply(this, arguments); }
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.jison.SLRGenerator"></a>[module jison.SLRGenerator](#apidoc.module.jison.SLRGenerator)

#### <a name="apidoc.element.jison.SLRGenerator.SLRGenerator"></a>[function <span class="apidocSignatureSpan">jison.</span>SLRGenerator ()](#apidoc.element.jison.SLRGenerator.SLRGenerator)
- description and source-code
```javascript
SLRGenerator = function () { return constructor.apply(this, arguments); }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.jison.SLRGenerator.mix"></a>[function <span class="apidocSignatureSpan">jison.SLRGenerator.</span>mix ()](#apidoc.element.jison.SLRGenerator.mix)
- description and source-code
```javascript
function typal_mix() {
    var self = this;
    for(var i=0,o,k; i<arguments.length; i++) {
        o=arguments[i];
        if (!o) continue;
        if (Object.prototype.hasOwnProperty.call(o,'constructor'))
            this.constructor = o.constructor;
        if (Object.prototype.hasOwnProperty.call(o,'toString'))
            this.toString = o.toString;
        for(k in o) {
            if (Object.prototype.hasOwnProperty.call(o, k)) {
                if(k.match(position) && typeof this[k.replace(position, '')] === 'function')
                    layerMethod.call(this, k, o[k]);
                else
                    this[k] = o[k];
            }
        }
    }
    return this;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.jison.SLRGenerator.prototype"></a>[module jison.SLRGenerator.prototype](#apidoc.module.jison.SLRGenerator.prototype)

#### <a name="apidoc.element.jison.SLRGenerator.prototype.constructor"></a>[function <span class="apidocSignatureSpan">jison.SLRGenerator.prototype.</span>constructor ()](#apidoc.element.jison.SLRGenerator.prototype.constructor)
- description and source-code
```javascript
constructor = function () { return constructor.apply(this, arguments); }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.jison.SLRGenerator.prototype.lookAheads"></a>[function <span class="apidocSignatureSpan">jison.SLRGenerator.prototype.</span>lookAheads (state, item)](#apidoc.element.jison.SLRGenerator.prototype.lookAheads)
- description and source-code
```javascript
function SLR_lookAhead(state, item) {
    return this.nonterminals[item.production.symbol].follows;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.jison.classy"></a>[module jison.classy](#apidoc.module.jison.classy)

#### <a name="apidoc.element.jison.classy.Parser"></a>[function <span class="apidocSignatureSpan">jison.classy.</span>Parser ()](#apidoc.element.jison.classy.Parser)
- description and source-code
```javascript
function Parser() {
  this.yy = {};
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.jison.classy.main"></a>[function <span class="apidocSignatureSpan">jison.classy.</span>main (args)](#apidoc.element.jison.classy.main)
- description and source-code
```javascript
function commonjsMain(args) {
    if (!args[1]) {
        console.log('Usage: '+args[0]+' FILE');
        process.exit(1);
    }
    var source = require('fs').readFileSync(require('path').normalize(args[1]), "utf8");
    return exports.parser.parse(source);
}
```
- example usage
```shell
...
        console.log('Usage: '+args[0]+' FILE');
        process.exit(1);
    }
    var source = require('fs').readFileSync(require('path').normalize(args[1]), "utf8");
    return exports.parser.parse(source);
};
if (typeof module !== 'undefined' && require.main === module) {
  exports.main(process.argv.slice(1));
}
}
...
```

#### <a name="apidoc.element.jison.classy.parse"></a>[function <span class="apidocSignatureSpan">jison.classy.</span>parse ()](#apidoc.element.jison.classy.parse)
- description and source-code
```javascript
parse = function () { return parser.parse.apply(parser, arguments); }
```
- example usage
```shell
...

    // generate source, ready to be written to disk
    var parserSource = parser.generate();

    // you can also use the parser directly from memory

    // returns true
    parser.parse("adfe34bc e82a");

    // throws lexical error
    parser.parse("adfe34bc zxg");


More Documentation
------------------
...
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
