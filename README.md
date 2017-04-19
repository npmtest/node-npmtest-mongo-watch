# npmtest-mongo-watch

#### test coverage for  [mongo-watch (v0.2.8)](http://github.com/TorchlightSoftware/mongo-watch)  [![npm package](https://img.shields.io/npm/v/npmtest-mongo-watch.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-mongo-watch) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-mongo-watch.svg)](https://travis-ci.org/npmtest/node-npmtest-mongo-watch)

#### A mongo watcher.  This ties into the MongoDB replication oplog, and exposes all data modifications via an EventEmitter.

[![NPM](https://nodei.co/npm/mongo-watch.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/mongo-watch)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-mongo-watch/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-mongo-watch/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-mongo-watch/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-mongo-watch/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-mongo-watch/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-mongo-watch/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-mongo-watch/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-mongo-watch/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-mongo-watch/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-mongo-watch/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-mongo-watch/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-mongo-watch/build/test-report.html](https://npmtest.github.io/node-npmtest-mongo-watch/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-mongo-watch/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-mongo-watch/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-mongo-watch/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-mongo-watch/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-mongo-watch/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-mongo-watch/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-mongo-watch/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-mongo-watch/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Torchlight Software",
        "url": "http://torchlightsoftware.com"
    },
    "bugs": {
        "url": "https://github.com/TorchlightSoftware/mongo-watch/issues"
    },
    "dependencies": {
        "async": "*",
        "coffee-script": ">1.7.0",
        "lodash": "*",
        "mongodb": "*"
    },
    "description": "A mongo watcher.  This ties into the MongoDB replication oplog, and exposes all data modifications via an EventEmitter.",
    "devDependencies": {
        "mocha": "*",
        "should": "*"
    },
    "directories": {},
    "dist": {
        "shasum": "9eee95cb675d83f3344601f53038a7f8f047349b",
        "tarball": "https://registry.npmjs.org/mongo-watch/-/mongo-watch-0.2.8.tgz"
    },
    "engines": {
        "node": ">= 0.8.4"
    },
    "gitHead": "b2166068669b614389c61e6de4af3410b390cf72",
    "homepage": "http://github.com/TorchlightSoftware/mongo-watch",
    "licenses": [
        {
            "type": "MIT",
            "url": "http://github.com/torchlightsoftware/mongo-watch/raw/master/LICENSE"
        }
    ],
    "main": "./index.js",
    "maintainers": [
        {
            "name": "torchlight"
        }
    ],
    "name": "mongo-watch",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/TorchlightSoftware/mongo-watch.git"
    },
    "scripts": {
        "test": "mocha"
    },
    "version": "0.2.8"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
