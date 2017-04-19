# npmtest-jugglingdb

#### test coverage for  [jugglingdb (v1.0.2)](https://github.com/1602/jugglingdb)  [![npm package](https://img.shields.io/npm/v/npmtest-jugglingdb.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-jugglingdb) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-jugglingdb.svg)](https://travis-ci.org/npmtest/node-npmtest-jugglingdb)

#### ORM for every database: redis, mysql, neo4j, mongodb, couchdb, postgres, sqlite

[![NPM](https://nodei.co/npm/jugglingdb.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/jugglingdb)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-jugglingdb/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-jugglingdb/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-jugglingdb/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-jugglingdb/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-jugglingdb/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-jugglingdb/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-jugglingdb/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-jugglingdb/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-jugglingdb/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-jugglingdb/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-jugglingdb/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-jugglingdb/build/test-report.html](https://npmtest.github.io/node-npmtest-jugglingdb/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-jugglingdb/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-jugglingdb/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-jugglingdb/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-jugglingdb/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-jugglingdb/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-jugglingdb/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-jugglingdb/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-jugglingdb/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Anatoliy Chakkaev"
    },
    "bugs": {
        "url": "https://github.com/1602/jugglingdb/issues"
    },
    "contributors": [
        {
            "name": "Anatoliy Chakkaev"
        },
        {
            "name": "Julien Guimont"
        },
        {
            "name": "Joseph Junker"
        },
        {
            "name": "Henri Bergius"
        },
        {
            "name": "redvulps"
        },
        {
            "name": "Felipe Sateler"
        },
        {
            "name": "Amir M. Mahmoudi"
        },
        {
            "name": "Justinas Stankevičius"
        },
        {
            "name": "Rick O'Toole"
        },
        {
            "name": "Nicholas Westlake"
        }
    ],
    "dependencies": {
        "inflection": "=1.2.7",
        "should": "=6.0.3",
        "when": "3.7.3"
    },
    "description": "ORM for every database: redis, mysql, neo4j, mongodb, couchdb, postgres, sqlite",
    "devDependencies": {
        "jshint": "2.5.6",
        "mocha": "~1.8.2",
        "semicov": "*",
        "should": "~3.0.1"
    },
    "directories": {},
    "dist": {
        "shasum": "c3ff07dc89d01d4b940fd1ed2282d29e0ca26b15",
        "tarball": "https://registry.npmjs.org/jugglingdb/-/jugglingdb-1.0.2.tgz"
    },
    "engines": [
        "node >= 0.6"
    ],
    "homepage": "https://github.com/1602/jugglingdb",
    "jshintConfig": {
        "proto": true
    },
    "main": "index.js",
    "maintainers": [
        {
            "name": "anatoliy"
        }
    ],
    "man": [
        "./docs/man/jugglingdb.3",
        "./docs/man/schema.3",
        "./docs/man/model.3",
        "./docs/man/hooks.3",
        "./docs/man/validations.3",
        "./docs/man/roadmap.3",
        "./docs/man/changelog.3"
    ],
    "name": "jugglingdb",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/1602/jugglingdb.git"
    },
    "scripts": {
        "prepublish": "make build",
        "test": "make test"
    },
    "version": "1.0.2"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
