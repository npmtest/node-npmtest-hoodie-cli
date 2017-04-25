# npmtest-hoodie-cli

#### basic test coverage for  [hoodie-cli (v0.6.3)](https://github.com/hoodiehq/hoodie-cli)  [![npm package](https://img.shields.io/npm/v/npmtest-hoodie-cli.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-hoodie-cli) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-hoodie-cli.svg)](https://travis-ci.org/npmtest/node-npmtest-hoodie-cli)

#### Hoodie command-line interface.

[![NPM](https://nodei.co/npm/hoodie-cli.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/hoodie-cli)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-hoodie-cli/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-hoodie-cli/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-hoodie-cli/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-hoodie-cli/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-hoodie-cli/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-hoodie-cli/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-hoodie-cli/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-hoodie-cli/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-hoodie-cli/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-hoodie-cli/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-hoodie-cli/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-hoodie-cli/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-hoodie-cli/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-hoodie-cli/build/test-report.html](https://npmtest.github.io/node-npmtest-hoodie-cli/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-hoodie-cli/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-hoodie-cli/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-hoodie-cli/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-hoodie-cli/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-hoodie-cli/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-hoodie-cli/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-hoodie-cli/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-hoodie-cli/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "hoodie-cli",
    "description": "Hoodie command-line interface.",
    "version": "0.6.3",
    "preferGlobal": true,
    "dependencies": {
        "async": "^0.9.0",
        "cli-color": "^0.3.2",
        "colors": "^0.6.2",
        "fixture-stdout": "^0.2.1",
        "graceful-fs": "^3.0.2",
        "ini": "^1.2.1",
        "insight": "^0.4.1",
        "npm": "^2.1.4",
        "open": "0.0.5",
        "optimist": "^0.6.1",
        "prompt": "^0.2.13",
        "rimraf": "^2.2.8",
        "semver": "^2.3.2",
        "shelljs": "^0.3.0",
        "underscore": "^1.6.0",
        "update-notifier": "^0.2.0"
    },
    "engines": {
        "node": ">=0.10.22"
    },
    "keywords": [
        "cli",
        "hoodie",
        "hood.ie",
        "hoodie.js"
    ],
    "repository": {
        "type": "git",
        "url": "git+https://github.com/hoodiehq/hoodie-cli.git"
    },
    "scripts": {
        "test": "grunt ci --verbose"
    },
    "bin": {
        "hoodie": "./bin/hoodie"
    },
    "author": {
        "name": "Sven Lito"
    },
    "devDependencies": {
        "expect.js": "^0.3.1",
        "grunt": "^0.4.5",
        "grunt-contrib-jshint": "^0.10.0",
        "grunt-contrib-watch": "^0.6.1",
        "grunt-release-hoodie": "^2.8.0",
        "grunt-simple-mocha": "^0.4.0",
        "load-grunt-tasks": "^0.6.0",
        "mocha": "^1.20.1",
        "sinon": "^1.10.3"
    },
    "codename": "superb-ox",
    "gitHead": "68636461cbbcb1f9005772531dc663e04b046355",
    "bugs": {
        "url": "https://github.com/hoodiehq/hoodie-cli/issues"
    },
    "homepage": "https://github.com/hoodiehq/hoodie-cli",
    "maintainers": [
        {
            "name": "caolan"
        },
        {
            "name": "gr2m"
        },
        {
            "name": "jan"
        },
        {
            "name": "svnlto"
        },
        {
            "name": "boennemann"
        },
        {
            "name": "hoodiebot"
        }
    ],
    "dist": {
        "shasum": "d8d5bdafe5e10ecc02aaace276d40f3e79acd5bd",
        "tarball": "https://registry.npmjs.org/hoodie-cli/-/hoodie-cli-0.6.3.tgz"
    },
    "directories": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
