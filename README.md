# npmtest-egghead-downloader

#### basic test coverage for  egghead-downloader (v0.1.9)  [![npm package](https://img.shields.io/npm/v/npmtest-egghead-downloader.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-egghead-downloader) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-egghead-downloader.svg)](https://travis-ci.org/npmtest/node-npmtest-egghead-downloader)

#### Downloads single videos or series from egghead.io for you

[![NPM](https://nodei.co/npm/egghead-downloader.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/egghead-downloader)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-egghead-downloader/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-egghead-downloader/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-egghead-downloader/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-egghead-downloader/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-egghead-downloader/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-egghead-downloader/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-egghead-downloader/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-egghead-downloader/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-egghead-downloader/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-egghead-downloader/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-egghead-downloader/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-egghead-downloader/build/test-report.html](https://npmtest.github.io/node-npmtest-egghead-downloader/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-egghead-downloader/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-egghead-downloader/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-egghead-downloader/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-egghead-downloader/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-egghead-downloader/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-egghead-downloader/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-egghead-downloader/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-egghead-downloader/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "egghead-downloader",
    "version": "0.1.9",
    "description": "Downloads single videos or series from egghead.io for you",
    "author": "Simon Selg <simon@selg.me>",
    "license": "MIT",
    "repository": {
        "type": "git",
        "url": "git@github.com:SimonSelg/egghead-downloader.git"
    },
    "keywords": [
        "egghead.io",
        "downloader"
    ],
    "engines": {
        "node": ">=6.0.0"
    },
    "preferGlobal": true,
    "bin": {
        "egghead-downloader": "dist/app.js"
    },
    "dependencies": {
        "chalk": "^1.1.3",
        "commander": "^2.9.0",
        "inquirer": "^1.2.3",
        "pleasant-progress": "^1.1.0",
        "request": "^2.72.0",
        "request-promise": "^3.0.0"
    },
    "devDependencies": {
        "babel-cli": "^6.9.0",
        "babel-eslint": "^6.0.4",
        "babel-plugin-transform-async-to-generator": "^6.8.0",
        "babel-preset-es2015-node": "^6.0.1",
        "eslint": "~2.10.2",
        "eslint-config-standard": "^5.3.1",
        "eslint-plugin-promise": "^1.3.2",
        "eslint-plugin-standard": "^1.3.2",
        "rimraf": "^2.5.2"
    },
    "scripts": {
        "clean": "rimraf dist",
        "build": "rimraf dist && mkdir dist && babel src/app.js -o dist/app.js",
        "lint": "eslint . ./",
        "lint:fix": "npm run lint -- --fix"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
