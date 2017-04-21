# npmtest-grunt-bake

#### basic test coverage for  [grunt-bake (v1.8.0)](https://github.com/MathiasPaumgarten/grunt-bake)  [![npm package](https://img.shields.io/npm/v/npmtest-grunt-bake.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-grunt-bake) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-grunt-bake.svg)](https://travis-ci.org/npmtest/node-npmtest-grunt-bake)

#### Bake external includes into files to create static pages with no server-side compilation time

[![NPM](https://nodei.co/npm/grunt-bake.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/grunt-bake)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-grunt-bake/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-grunt-bake/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-grunt-bake/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-grunt-bake/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-grunt-bake/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-grunt-bake/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-grunt-bake/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-grunt-bake/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-grunt-bake/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-grunt-bake/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-grunt-bake/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-grunt-bake/build/test-report.html](https://npmtest.github.io/node-npmtest-grunt-bake/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-grunt-bake/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-grunt-bake/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-grunt-bake/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-grunt-bake/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-grunt-bake/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-grunt-bake/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-grunt-bake/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-grunt-bake/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "grunt-bake",
    "description": "Bake external includes into files to create static pages with no server-side compilation time",
    "version": "1.8.0",
    "homepage": "https://github.com/MathiasPaumgarten/grunt-bake",
    "author": {
        "name": "Mathias Paumgarten",
        "url": "http://mathias-paumgarten.com"
    },
    "contributors": [
        {
            "name": "David Zacharias"
        },
        {
            "name": "Paul Huizer",
            "url": "https://github.com/PaulHuizer"
        }
    ],
    "repository": {
        "type": "git",
        "url": "https://github.com/MathiasPaumgarten/grunt-bake.git"
    },
    "bugs": {
        "url": "https://github.com/MathiasPaumgarten/grunt-bake/issues"
    },
    "licenses": [
        {
            "type": "MIT",
            "url": "/blob/master/LICENSE-MIT"
        }
    ],
    "main": "Gruntfile.js",
    "engines": {
        "node": ">= 0.10.0"
    },
    "scripts": {
        "test": "grunt test"
    },
    "dependencies": {
        "mout": "~0.11.1"
    },
    "devDependencies": {
        "grunt-contrib-jshint": "~1.0.0",
        "grunt-contrib-clean": "~1.0.0",
        "grunt-contrib-nodeunit": "^0.4.1",
        "grunt-contrib-watch": "~0.6.1",
        "grunt-jsonlint": "~1.0.7",
        "grunt": "~0.4.5"
    },
    "peerDependencies": {
        "grunt": ">=0.4.0"
    },
    "keywords": [
        "gruntplugin",
        "bake",
        "static page",
        "templates",
        "static",
        "include"
    ]
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
