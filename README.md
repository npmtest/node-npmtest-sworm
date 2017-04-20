# npmtest-sworm

#### basic test coverage for  [sworm (v3.6.0)](https://github.com/featurist/sworm)  [![npm package](https://img.shields.io/npm/v/npmtest-sworm.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-sworm) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-sworm.svg)](https://travis-ci.org/npmtest/node-npmtest-sworm)

#### a lightweight write-only ORM for MSSQL, MySQL, PostgreSQL, Oracle, Sqlite 3

[![NPM](https://nodei.co/npm/sworm.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/sworm)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-sworm/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-sworm/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-sworm/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-sworm/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-sworm/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-sworm/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-sworm/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-sworm/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-sworm/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-sworm/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-sworm/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-sworm/build/test-report.html](https://npmtest.github.io/node-npmtest-sworm/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-sworm/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-sworm/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-sworm/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-sworm/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-sworm/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-sworm/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-sworm/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-sworm/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "sworm",
    "version": "3.6.0",
    "description": "a lightweight write-only ORM for MSSQL, MySQL, PostgreSQL, Oracle, Sqlite 3",
    "main": "index.js",
    "directories": {
        "test": "test"
    },
    "dependencies": {
        "cooperative": "1.1.0",
        "debug": "2.2.0",
        "randomstring": "1.1.5",
        "underscore": "1.8.3"
    },
    "devDependencies": {
        "chai": "3.5.0",
        "chai-as-promised": "5.3.0",
        "electron": "1.6.2",
        "electron-mocha": "3.3.0",
        "es6-promise": "3.2.1",
        "fs-promise": "0.5.0",
        "mocha": "3.2.0",
        "mssql": "3.3.0",
        "mysql": "2.11.1",
        "pg": "6.1.0",
        "sqlite3": "3.1.8"
    },
    "scripts": {
        "test": "mocha && electron-mocha --renderer test/browser"
    },
    "repository": {
        "type": "git",
        "url": "https://github.com/featurist/sworm.git"
    },
    "keywords": [
        "activerecord",
        "database",
        "postgres",
        "postgresql",
        "mysql",
        "orm",
        "mssql",
        "sqlserver",
        "sql",
        "server"
    ],
    "author": "Tim Macfarlane <timmacfarlane@gmail.com>",
    "license": "MIT",
    "bugs": {
        "url": "https://github.com/featurist/sworm/issues"
    },
    "homepage": "https://github.com/featurist/sworm"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
