# npmtest-idb-keyval

#### basic test coverage for  [idb-keyval (v2.3.0)](https://github.com/jakearchibald/idb-keyval#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-idb-keyval.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-idb-keyval) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-idb-keyval.svg)](https://travis-ci.org/npmtest/node-npmtest-idb-keyval)

#### A super-simple-small keyval store built on top of IndexedDB

[![NPM](https://nodei.co/npm/idb-keyval.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/idb-keyval)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-idb-keyval/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-idb-keyval/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-idb-keyval/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-idb-keyval/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-idb-keyval/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-idb-keyval/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-idb-keyval/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-idb-keyval/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-idb-keyval/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-idb-keyval/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-idb-keyval/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-idb-keyval/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-idb-keyval/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-idb-keyval/build/test-report.html](https://npmtest.github.io/node-npmtest-idb-keyval/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-idb-keyval/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-idb-keyval/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-idb-keyval/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-idb-keyval/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-idb-keyval/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-idb-keyval/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-idb-keyval/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-idb-keyval/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Jake Archibald"
    },
    "bugs": {
        "url": "https://github.com/jakearchibald/idb-keyval/issues"
    },
    "dependencies": {},
    "description": "A super-simple-small keyval store built on top of IndexedDB",
    "devDependencies": {
        "uglify-js": "^2.7.0"
    },
    "directories": {},
    "dist": {
        "shasum": "4d444b80c3f86fcbcd51321b4dcbc9247c5948c0",
        "tarball": "https://registry.npmjs.org/idb-keyval/-/idb-keyval-2.3.0.tgz"
    },
    "gitHead": "cc960ba082679d2c8c3b71522985da4f2175d3f6",
    "homepage": "https://github.com/jakearchibald/idb-keyval#readme",
    "keywords": [
        "idb",
        "indexeddb",
        "store",
        "keyval",
        "localstorage",
        "storage",
        "promise"
    ],
    "license": "Apache-2.0",
    "main": "idb-keyval.js",
    "maintainers": [
        {
            "name": "jaffathecake"
        }
    ],
    "name": "idb-keyval",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/jakearchibald/idb-keyval.git"
    },
    "scripts": {
        "build": "uglifyjs idb-keyval.js --screw-ie8 -mc --output dist/idb-keyval-min.js"
    },
    "typings": "typings.d.ts",
    "version": "2.3.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
