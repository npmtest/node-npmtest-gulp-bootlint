# npmtest-gulp-bootlint

#### basic test coverage for  [gulp-bootlint (v0.8.1)](https://github.com/tschortsch/gulp-bootlint)  [![npm package](https://img.shields.io/npm/v/npmtest-gulp-bootlint.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-gulp-bootlint) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-gulp-bootlint.svg)](https://travis-ci.org/npmtest/node-npmtest-gulp-bootlint)

#### A gulp wrapper for Bootlint, the HTML linter for Bootstrap projects

[![NPM](https://nodei.co/npm/gulp-bootlint.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/gulp-bootlint)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-gulp-bootlint/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-gulp-bootlint/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-gulp-bootlint/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-gulp-bootlint/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-gulp-bootlint/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-gulp-bootlint/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-gulp-bootlint/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-gulp-bootlint/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-gulp-bootlint/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-gulp-bootlint/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-gulp-bootlint/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-gulp-bootlint/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-gulp-bootlint/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-gulp-bootlint/build/test-report.html](https://npmtest.github.io/node-npmtest-gulp-bootlint/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-gulp-bootlint/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-gulp-bootlint/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-gulp-bootlint/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-gulp-bootlint/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-gulp-bootlint/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-gulp-bootlint/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-gulp-bootlint/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-gulp-bootlint/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Juerg Hunziker",
        "url": "http://juerghunziker.ch"
    },
    "bugs": {
        "url": "https://github.com/tschortsch/gulp-bootlint/issues"
    },
    "dependencies": {
        "bootlint": "^0.14.2",
        "gulp-util": "^3.0.8",
        "log": "^1.4.0",
        "merge": "^1.2.0",
        "through2": "^2.0.3"
    },
    "description": "A gulp wrapper for Bootlint, the HTML linter for Bootstrap projects",
    "devDependencies": {
        "eslint": "^3.14.1",
        "mocha": "^3.2.0",
        "should": "^11.2.0"
    },
    "directories": {},
    "dist": {
        "shasum": "62c396f9ab727cfb13134dddcaed091bb0bc2ff7",
        "tarball": "https://registry.npmjs.org/gulp-bootlint/-/gulp-bootlint-0.8.1.tgz"
    },
    "engines": {
        "node": ">=0.10.0"
    },
    "files": [
        "index.js"
    ],
    "gitHead": "95a5b7a85b2d3fd6801fe0aab26f858719b9a1e7",
    "homepage": "https://github.com/tschortsch/gulp-bootlint",
    "jshintConfig": {
        "node": true
    },
    "keywords": [
        "gulpplugin",
        "bootlint",
        "bootstrap",
        "html",
        "markup",
        "code",
        "style",
        "validate",
        "lint",
        "check",
        "checker"
    ],
    "license": "MIT",
    "maintainers": [
        {
            "name": "tschortsch"
        }
    ],
    "name": "gulp-bootlint",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/tschortsch/gulp-bootlint.git"
    },
    "scripts": {
        "pretest": "eslint *.js test/*.js",
        "test": "mocha"
    },
    "version": "0.8.1",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
