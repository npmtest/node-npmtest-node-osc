# npmtest-node-osc

#### basic test coverage for  [node-osc (v2.1.0)](https://github.com/MylesBorins/node-osc#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-node-osc.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-node-osc) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-node-osc.svg)](https://travis-ci.org/npmtest/node-npmtest-node-osc)

#### pyOSC inspired library

[![NPM](https://nodei.co/npm/node-osc.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/node-osc)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-node-osc/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-node-osc/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-node-osc/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-node-osc/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-node-osc/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-node-osc/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-node-osc/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-node-osc/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-node-osc/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-node-osc/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-node-osc/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-node-osc/build/test-report.html](https://npmtest.github.io/node-npmtest-node-osc/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-node-osc/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-node-osc/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-node-osc/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-node-osc/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-node-osc/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-node-osc/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-node-osc/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-node-osc/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Myles Borins"
    },
    "bugs": {
        "url": "https://github.com/MylesBorins/node-osc/issues"
    },
    "contributors": [
        {
            "name": "Hans Hübner"
        },
        {
            "name": "Andy Smith"
        },
        {
            "name": "Myles Borins"
        }
    ],
    "dependencies": {
        "jspack": "0.0.4",
        "osc-min": "^1.1.1",
        "semver": "^5.1.0"
    },
    "description": "pyOSC inspired library",
    "devDependencies": {
        "eslint": "^3.18.0",
        "tap": "^10.3.0"
    },
    "directories": {},
    "dist": {
        "shasum": "db714f98cf9a5c8435ee99dc7806528b7823a190",
        "tarball": "https://registry.npmjs.org/node-osc/-/node-osc-2.1.0.tgz"
    },
    "gitHead": "cb8b32f0bde7e3da830d0fae78e0b7b41baede31",
    "homepage": "https://github.com/MylesBorins/node-osc#readme",
    "keywords": [
        "osc",
        "udp"
    ],
    "license": "LGPL-2.1",
    "main": "lib/index.js",
    "maintainers": [
        {
            "name": "mylesborins"
        }
    ],
    "name": "node-osc",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/MylesBorins/node-osc.git"
    },
    "scripts": {
        "lint": "eslint **/*.js",
        "tap": "tap test/*.js",
        "test": "npm run lint && npm run tap"
    },
    "version": "2.1.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
