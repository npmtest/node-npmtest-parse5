# npmtest-parse5

#### basic test coverage for  [parse5 (v3.0.2)](https://github.com/inikulin/parse5)  [![npm package](https://img.shields.io/npm/v/npmtest-parse5.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-parse5) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-parse5.svg)](https://travis-ci.org/npmtest/node-npmtest-parse5)

#### HTML parsing/serialization toolset for Node.js. WHATWG HTML Living Standard (aka HTML5)-compliant.

[![NPM](https://nodei.co/npm/parse5.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/parse5)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-parse5/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-parse5/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-parse5/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-parse5/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-parse5/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-parse5/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-parse5/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-parse5/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-parse5/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-parse5/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-parse5/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-parse5/build/test-report.html](https://npmtest.github.io/node-npmtest-parse5/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-parse5/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-parse5/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-parse5/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-parse5/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-parse5/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-parse5/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-parse5/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-parse5/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Ivan Nikulin",
        "url": "https://github.com/inikulin"
    },
    "bugs": {
        "url": "https://github.com/inikulin/parse5/issues"
    },
    "contributors": "https://github.com/inikulin/parse5/graphs/contributors",
    "dependencies": {
        "@types/node": "^6.0.46"
    },
    "description": "HTML parsing/serialization toolset for Node.js. WHATWG HTML Living Standard (aka HTML5)-compliant.",
    "devDependencies": {
        "del": "^2.0.2",
        "gulp": "^3.9.0",
        "gulp-benchmark": "^1.1.1",
        "gulp-download": "0.0.1",
        "gulp-eslint": "^3.0.1",
        "gulp-install": "^0.6.0",
        "gulp-mocha": "^2.1.3",
        "gulp-rename": "^1.2.2",
        "gulp-typedoc": "^2.0.0",
        "gulp-typescript": "^3.1.2",
        "publish-please": "^2.2.0",
        "through2": "^2.0.0",
        "typedoc": "^0.5.1",
        "typescript": "^2.0.6"
    },
    "directories": {},
    "dist": {
        "shasum": "05eff57f0ef4577fb144a79f8b9a967a6cc44510",
        "tarball": "https://registry.npmjs.org/parse5/-/parse5-3.0.2.tgz"
    },
    "files": [
        "lib"
    ],
    "gitHead": "969ed22f53db38c101449e05a1b804ea456d4e04",
    "homepage": "https://github.com/inikulin/parse5",
    "keywords": [
        "html",
        "parser",
        "html5",
        "WHATWG",
        "specification",
        "fast",
        "html parser",
        "html5 parser",
        "htmlparser",
        "parse5",
        "serializer",
        "html serializer",
        "htmlserializer",
        "sax",
        "simple api",
        "parse",
        "tokenize",
        "serialize",
        "tokenizer"
    ],
    "license": "MIT",
    "main": "./lib/index.js",
    "maintainers": [
        {
            "name": "inikulin"
        }
    ],
    "name": "parse5",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/inikulin/parse5.git"
    },
    "scripts": {
        "prepublish": "publish-please guard",
        "publish-please": "publish-please",
        "test": "gulp test"
    },
    "types": "./lib/index.d.ts",
    "version": "3.0.2",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
