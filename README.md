# npmtest-tree-monkey

#### basic test coverage for  tree-monkey (v0.0.4)  [![npm package](https://img.shields.io/npm/v/npmtest-tree-monkey.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-tree-monkey) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-tree-monkey.svg)](https://travis-ci.org/npmtest/node-npmtest-tree-monkey)

#### Async tree traversal for nodejs

[![NPM](https://nodei.co/npm/tree-monkey.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/tree-monkey)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-tree-monkey/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-tree-monkey/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-tree-monkey/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-tree-monkey/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-tree-monkey/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-tree-monkey/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-tree-monkey/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-tree-monkey/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-tree-monkey/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-tree-monkey/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-tree-monkey/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-tree-monkey/build/test-report.html](https://npmtest.github.io/node-npmtest-tree-monkey/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-tree-monkey/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-tree-monkey/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-tree-monkey/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-tree-monkey/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-tree-monkey/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-tree-monkey/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-tree-monkey/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-tree-monkey/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "tree-monkey",
    "version": "0.0.4",
    "description": "Async tree traversal for nodejs",
    "main": "lib/tree-monkey.js",
    "scripts": {
        "test": "node_modules/jasmine-node/bin/jasmine-node --coffee specs/",
        "prepublish": "node_modules/coffee-script/bin/coffee -co lib/ src/"
    },
    "repository": {
        "type": "git",
        "url": "https://github.com/felixhageloh/tree-monkey.git"
    },
    "keywords": [
        "async",
        "tree",
        "traversal",
        "directory",
        "path"
    ],
    "author": "Felix Hageloh",
    "license": "MIT",
    "bugs": {
        "url": "https://github.com/felixhageloh/tree-monkey/issues"
    },
    "dependencies": {
        "async": "~0.2.9"
    },
    "devDependencies": {
        "coffee-script": "~1.6.3",
        "jasmine-node": "~1.11.0"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
