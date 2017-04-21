# npmtest-level-store

#### basic test coverage for  [level-store (v3.11.0)](https://github.com/juliangruber/level-store)  [![npm package](https://img.shields.io/npm/v/npmtest-level-store.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-level-store) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-level-store.svg)](https://travis-ci.org/npmtest/node-npmtest-level-store)

#### A streaming storage engine based on LevelDB.

[![NPM](https://nodei.co/npm/level-store.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/level-store)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-level-store/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-level-store/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-level-store/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-level-store/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-level-store/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-level-store/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-level-store/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-level-store/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-level-store/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-level-store/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-level-store/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-level-store/build/test-report.html](https://npmtest.github.io/node-npmtest-level-store/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-level-store/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-level-store/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-level-store/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-level-store/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-level-store/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-level-store/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-level-store/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-level-store/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "level-store",
    "description": "A streaming storage engine based on LevelDB.",
    "version": "3.11.0",
    "repository": {
        "type": "git",
        "url": "git://github.com/juliangruber/level-store.git"
    },
    "homepage": "https://github.com/juliangruber/level-store",
    "main": "index.js",
    "scripts": {
        "test": "tap test/*.js"
    },
    "dependencies": {
        "duplexer": "~0.1.1",
        "level-capped": "~0.0.4",
        "level-delete-range": "~0.1.0",
        "level-fix-range": "~1.1.2",
        "level-live-stream": "1.4.8",
        "level-peek": "~1.0.6",
        "level-ws": "0.0.1",
        "monotonic-timestamp": "~0.0.8",
        "through": "~2.2.7"
    },
    "devDependencies": {
        "ben": "0.0.0",
        "level": "^1.4.0",
        "rimraf": "~2.2.0",
        "tap": "*"
    },
    "keywords": [
        "leveldb",
        "levelup",
        "stream",
        "persistent"
    ],
    "author": {
        "name": "Julian Gruber",
        "url": "http://juliangruber.com"
    },
    "license": "MIT",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
