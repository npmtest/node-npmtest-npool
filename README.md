# npmtest-npool

#### basic test coverage for  [npool (v1.4.7)](https://github.com/inh3/nPool)  [![npm package](https://img.shields.io/npm/v/npmtest-npool.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-npool) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-npool.svg)](https://travis-ci.org/npmtest/node-npmtest-npool)

#### A cross-platform thread pool add-on for Node.js and io.js

[![NPM](https://nodei.co/npm/npool.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/npool)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-npool/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-npool/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-npool/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-npool/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-npool/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-npool/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-npool/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-npool/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-npool/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-npool/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-npool/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-npool/build/test-report.html](https://npmtest.github.io/node-npmtest-npool/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-npool/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-npool/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-npool/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-npool/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-npool/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-npool/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-npool/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-npool/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "analyze": false,
    "author": {
        "name": "Ivan Hall"
    },
    "bugs": {
        "url": "https://github.com/inh3/nPool/issues"
    },
    "dependencies": {
        "nan": ">= 2.1.0"
    },
    "description": "A cross-platform thread pool add-on for Node.js and io.js",
    "devDependencies": {
        "mocha": ">= 1.14.0"
    },
    "directories": {},
    "dist": {
        "shasum": "c80e35294df35551071a1527930f48f76e414e97",
        "tarball": "https://registry.npmjs.org/npool/-/npool-1.4.7.tgz"
    },
    "engine-strict": true,
    "engines": {
        "node": ">= 0.8.28"
    },
    "gitHead": "d75c8037adddc28f1827feb2563508787db70906",
    "gypfile": true,
    "homepage": "https://github.com/inh3/nPool",
    "keywords": [
        "c",
        "c++",
        "addon",
        "module",
        "pthread",
        "native",
        "async",
        "thread",
        "threadpool",
        "thread pool",
        "unit of work",
        "task"
    ],
    "license": "BSD-3-Clause",
    "main": "./build/Release/npool.node",
    "maintainers": [
        {
            "name": "inh3"
        }
    ],
    "name": "npool",
    "optionalDependencies": {},
    "os": [
        "darwin",
        "linux",
        "win32"
    ],
    "preferGlobal": false,
    "repository": {
        "type": "git",
        "url": "git+https://github.com/inh3/nPool.git"
    },
    "scripts": {
        "install": "node-gyp rebuild",
        "test": "make test"
    },
    "version": "1.4.7",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
