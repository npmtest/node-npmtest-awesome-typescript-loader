# test coverage for  [awesome-typescript-loader (v3.1.2)](https://github.com/s-panferov/awesome-typescript-loader)  [![npm package](https://img.shields.io/npm/v/npmtest-awesome-typescript-loader.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-awesome-typescript-loader) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-awesome-typescript-loader.svg)](https://travis-ci.org/npmtest/node-npmtest-awesome-typescript-loader)
#### Awesome TS loader for webpack

[![NPM](https://nodei.co/npm/awesome-typescript-loader.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/awesome-typescript-loader)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-awesome-typescript-loader/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-awesome-typescript-loader/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-awesome-typescript-loader/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-awesome-typescript-loader/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-awesome-typescript-loader/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-awesome-typescript-loader/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-awesome-typescript-loader/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-awesome-typescript-loader/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-awesome-typescript-loader/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-awesome-typescript-loader/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-awesome-typescript-loader/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-awesome-typescript-loader/build/test-report.html](https://npmtest.github.io/node-npmtest-awesome-typescript-loader/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-awesome-typescript-loader/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-awesome-typescript-loader/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-awesome-typescript-loader/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-awesome-typescript-loader/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-awesome-typescript-loader/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-awesome-typescript-loader/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-awesome-typescript-loader/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-awesome-typescript-loader/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Stanislav Panferov",
        "url": "http://panferov.me/"
    },
    "bugs": {
        "url": "https://github.com/s-panferov/awesome-typescript-loader/issues"
    },
    "dependencies": {
        "colors": "^1.1.2",
        "enhanced-resolve": "^3.1.0",
        "loader-utils": "^1.0.2",
        "lodash": "^4.17.4",
        "mkdirp": "^0.5.1",
        "object-assign": "^4.1.1",
        "source-map-support": "^0.4.11"
    },
    "description": "Awesome TS loader for webpack",
    "devDependencies": {
        "@types/chai": "^3.4.35",
        "@types/colors": "^1.1.1",
        "@types/lodash": "^4.14.54",
        "@types/mocha": "^2.2.39",
        "@types/node": "^7.0.5",
        "@types/shelljs": "^0.7.0",
        "@types/sinon": "^1.16.35",
        "@types/webpack": "^2.2.8",
        "bluebird": "^3.5.0",
        "chai": "^3.5.0",
        "empty-module": "0.0.2",
        "fs-extra": "^2.0.0",
        "mocha": "^3.2.0",
        "ps-node": "^0.1.1",
        "rimraf": "^2.6.1",
        "shelljs": "^0.7.6",
        "standard-version": "^4.0.0",
        "temp": "^0.8.3",
        "tslint": "^4.5.1",
        "typescript": "^2.2.1",
        "webpack": "^2.2.1"
    },
    "directories": {},
    "dist": {
        "shasum": "3df192b91a6285f795ca65e63aad114fbb44f710",
        "tarball": "https://registry.npmjs.org/awesome-typescript-loader/-/awesome-typescript-loader-3.1.2.tgz"
    },
    "gitHead": "f97777dbe08aaf737e1e25e34356e5bad8c51397",
    "homepage": "https://github.com/s-panferov/awesome-typescript-loader",
    "keywords": [
        "webpack",
        "loader",
        "webpack-loader",
        "typescript"
    ],
    "license": "MIT",
    "main": "dist/entry.js",
    "maintainers": [
        {
            "name": "panferov-s"
        }
    ],
    "name": "awesome-typescript-loader",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/s-panferov/awesome-typescript-loader.git"
    },
    "scripts": {
        "build": "rimraf dist && tsc --pretty",
        "compile": "tsc --pretty",
        "lint": "tslint src/*.ts",
        "prebuild": "npm run lint",
        "prepublish": "npm run build",
        "release": "standard-version",
        "test": "rimraf .test && mocha --timeout 30000 dist/__test__",
        "watch": "npm run watch:ts",
        "watch:ts": "npm run build:ts -- --watch --diagnostics"
    },
    "typings": "./dist/index.d.ts",
    "version": "3.1.2"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
