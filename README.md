# test coverage for  [coveralls (v2.13.0)](https://github.com/nickmerwin/node-coveralls#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-coveralls.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-coveralls) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-coveralls.svg)](https://travis-ci.org/npmtest/node-npmtest-coveralls)
#### takes json-cov output into stdin and POSTs to coveralls.io

[![NPM](https://nodei.co/npm/coveralls.png?downloads=true)](https://www.npmjs.com/package/coveralls)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-coveralls/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-coveralls/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-coveralls/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-coveralls/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-coveralls/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-coveralls/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-coveralls/tree/gh-pages/build)|

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-coveralls/build/screenCapture.buildCustomOrg.browser.coverage.html.png)](https://npmtest.github.io/node-npmtest-coveralls/build/coverage.html/index.html)

[![test-report](https://npmtest.github.io/node-npmtest-coveralls/build/screenCapture.buildCustomOrg.browser.%252Fhome%252Ftravis%252Fbuild%252Fnpmtest%252Fnode-npmtest-coveralls%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-coveralls/build/test-report.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-coveralls/build/screenCapture.buildApidoc.browser.%252Fhome%252Ftravis%252Fbuild%252Fnpmdoc%252Fnode-npmdoc-coveralls%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-coveralls/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-coveralls/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-coveralls/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Gregg Caines"
    },
    "bin": {
        "coveralls": "./bin/coveralls.js"
    },
    "bugs": {
        "url": "https://github.com/nickmerwin/node-coveralls/issues"
    },
    "contributors": [
        {
            "name": "Gregg Caines",
            "email": "gregg@caines.ca",
            "url": "http://caines.ca"
        },
        {
            "name": "Joshua Ma",
            "email": "github@joshma.com",
            "url": "http://joshma.com"
        },
        {
            "name": "Alan Gutierrez",
            "email": "alan@prettyrobots.com",
            "url": "http://www.prettyrobots.com/"
        },
        {
            "name": "Kir Belevich",
            "url": "https://github.com/svg"
        },
        {
            "name": "elliotcable",
            "email": "github@elliottcable.name",
            "url": "http://elliottcable.name/"
        },
        {
            "name": "Slotos",
            "email": "slotos@gmail.com",
            "url": "http://slotos.net"
        },
        {
            "name": "mattjmorrison",
            "email": "mattjmorrison@mattjmorrison.com",
            "url": "http://mattjmorrison.com"
        },
        {
            "name": "Arpad Borsos",
            "email": "arpad.borsos@googlemail.com",
            "url": "http://swatinem.de/"
        },
        {
            "name": "Adam Moss",
            "url": "https://github.com/adam-moss"
        }
    ],
    "dependencies": {
        "js-yaml": "3.6.1",
        "lcov-parse": "0.0.10",
        "log-driver": "1.2.5",
        "minimist": "1.2.0",
        "request": "2.79.0"
    },
    "description": "takes json-cov output into stdin and POSTs to coveralls.io",
    "devDependencies": {
        "istanbul": "0.4.5",
        "jshint": "2.9.3",
        "mocha": "3.2.0",
        "mocha-lcov-reporter": "1.2.0",
        "should": "9.0.2",
        "sinon-restore": "1.0.1",
        "snyk": "1.23.3"
    },
    "directories": {
        "test": "test"
    },
    "dist": {
        "shasum": "df933876e8c6f478efb04f4d3ab70dc96b7e5a8e",
        "tarball": "https://registry.npmjs.org/coveralls/-/coveralls-2.13.0.tgz"
    },
    "engines": {
        "node": ">=0.8.6"
    },
    "gitHead": "28212004077299a871a6216273cce7a502e2ce67",
    "homepage": "https://github.com/nickmerwin/node-coveralls#readme",
    "keywords": [
        "coverage",
        "coveralls"
    ],
    "license": "BSD-2-Clause",
    "main": "index.js",
    "maintainers": [
        {
            "name": "cainus",
            "email": "gregg@caines.ca"
        },
        {
            "name": "nickmerwin",
            "email": "n@mer.fm"
        }
    ],
    "name": "coveralls",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git://github.com/nickmerwin/node-coveralls.git"
    },
    "scripts": {
        "test": "snyk test && make test"
    },
    "version": "2.13.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
