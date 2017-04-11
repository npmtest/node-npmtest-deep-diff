# test coverage for  [deep-diff (v0.3.4)](https://github.com/flitbit/diff#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-deep-diff.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-deep-diff) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-deep-diff.svg)](https://travis-ci.org/npmtest/node-npmtest-deep-diff)
#### Javascript utility for calculating deep difference, capturing changes, and applying changes across objects; for nodejs and the browser.

[![NPM](https://nodei.co/npm/deep-diff.png?downloads=true)](https://www.npmjs.com/package/deep-diff)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-deep-diff/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-deep-diff/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-deep-diff/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-deep-diff/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-deep-diff/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-deep-diff/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-deep-diff/tree/gh-pages/build)|

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-deep-diff/build/screenCapture.buildCustomOrg.browser.coverage.html.png)](https://npmtest.github.io/node-npmtest-deep-diff/build/coverage.html/index.html)

[![test-report](https://npmtest.github.io/node-npmtest-deep-diff/build/screenCapture.buildCustomOrg.browser.%252Fhome%252Ftravis%252Fbuild%252Fnpmtest%252Fnode-npmtest-deep-diff%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-deep-diff/build/test-report.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-deep-diff/build/screenCapture.buildApidoc.browser.%252Fhome%252Ftravis%252Fbuild%252Fnpmdoc%252Fnode-npmdoc-deep-diff%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-deep-diff/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-deep-diff/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-deep-diff/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Phillip Clark",
        "email": "phillip@flitbit.com"
    },
    "bugs": {
        "url": "https://github.com/flitbit/diff/issues"
    },
    "contributors": [
        {
            "name": "Dan Drinkard",
            "email": "dan.drinkard@gmail.com"
        },
        {
            "name": "Daniel Spangler",
            "email": "daniel.spangler@gmail.com"
        },
        {
            "name": "Denning",
            "email": "denningj@amazon.com"
        },
        {
            "name": "Elad Efrat",
            "email": "elad@iNNU.ORG"
        },
        {
            "name": "Mats Bryntse",
            "email": "mats.dev@bryntum.com"
        },
        {
            "name": "Nicholas Calugar",
            "email": "njcalugar@gmail.com"
        },
        {
            "name": "Paul Pflugradt",
            "email": "paulpflugradt@googlemail.com"
        },
        {
            "name": "Serkan Serttop",
            "email": "serkanserttop@yahoo.com"
        },
        {
            "name": "Simen Bekkhus",
            "email": "sbekkhus91@gmail.com"
        },
        {
            "name": "Tom Ashworth",
            "email": "tashworth@twitter.com"
        },
        {
            "name": "Tom MacWright",
            "email": "tmcw@users.noreply.github.com"
        },
        {
            "name": "Yandell",
            "email": "hyandell@amazon.com"
        },
        {
            "name": "ZauberNerd",
            "email": "zaubernerd@zaubernerd.de"
        },
        {
            "name": "caasi Huang",
            "email": "caasi.igd@gmail.com"
        },
        {
            "name": "icesoar",
            "email": "icesoar@hotmail.com"
        },
        {
            "name": "orlando",
            "email": "operri@opentable.com"
        },
        {
            "name": "ravishivt",
            "email": "javishi@gmail.com"
        },
        {
            "name": "wooorm",
            "email": "tituswormer@gmail.com"
        }
    ],
    "dependencies": {},
    "description": "Javascript utility for calculating deep difference, capturing changes, and applying changes across objects; for nodejs and the browser.",
    "devDependencies": {
        "deep-equal": "~1.0.0",
        "expect.js": "^0.3.1",
        "jscs": "^1.12.0",
        "jshint": "^2.6.3",
        "mocha": "^2.2.1",
        "uglifyjs": "^2.4.10"
    },
    "directories": {
        "examples": "./examples",
        "releases": "./releases",
        "test": "./test"
    },
    "dist": {
        "shasum": "aac5c39952236abe5f037a2349060ba01b00ae48",
        "tarball": "https://registry.npmjs.org/deep-diff/-/deep-diff-0.3.4.tgz"
    },
    "files": [
        "index.js",
        "releases/"
    ],
    "gitHead": "e271e69f4c6dbccf657cf30355d307b46659de67",
    "homepage": "https://github.com/flitbit/diff#readme",
    "keywords": [
        "diff",
        "difference",
        "compare",
        "change-tracking"
    ],
    "license": "MIT",
    "main": "./index.js",
    "maintainers": [
        {
            "name": "flitbit",
            "email": "phillip@flitbit.com"
        }
    ],
    "name": "deep-diff",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git://github.com/flitbit/diff.git"
    },
    "scripts": {
        "pretest": "jscs index.js test/ && jshint index.js test/",
        "release": "uglifyjs index.js -o releases/deep-diff-$npm_package_version.min.js  -r '$,require,exports,module,window,global' -m  --comments '/^!/'",
        "test": "mocha"
    },
    "version": "0.3.4"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
