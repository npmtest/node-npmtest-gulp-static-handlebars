# npmtest-gulp-static-handlebars

#### basic test coverage for  [gulp-static-handlebars (v1.2.0)](https://github.com/TakenPilot/gulp-static-handlebars#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-gulp-static-handlebars.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-gulp-static-handlebars) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-gulp-static-handlebars.svg)](https://travis-ci.org/npmtest/node-npmtest-gulp-static-handlebars)

#### Compile handlebars into static files, taking data, partials and helpers from outside sources like files, database, and json through callbacks and promises.

[![NPM](https://nodei.co/npm/gulp-static-handlebars.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/gulp-static-handlebars)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-gulp-static-handlebars/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-gulp-static-handlebars/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-gulp-static-handlebars/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-gulp-static-handlebars/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-gulp-static-handlebars/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-gulp-static-handlebars/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-gulp-static-handlebars/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-gulp-static-handlebars/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-gulp-static-handlebars/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-gulp-static-handlebars/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-gulp-static-handlebars/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-gulp-static-handlebars/build/test-report.html](https://npmtest.github.io/node-npmtest-gulp-static-handlebars/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-gulp-static-handlebars/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-gulp-static-handlebars/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-gulp-static-handlebars/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-gulp-static-handlebars/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-gulp-static-handlebars/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-gulp-static-handlebars/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-gulp-static-handlebars/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-gulp-static-handlebars/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Dane Stuckel"
    },
    "bugs": {
        "url": "https://github.com/TakenPilot/gulp-static-handlebars/issues"
    },
    "config": {
        "blanket": {
            "pattern": "index.js",
            "data-cover-never": "node_modules"
        }
    },
    "dependencies": {
        "bluebird": "^2.9",
        "gulp-util": "^3.0",
        "handlebars": "^4.0",
        "lodash": "^3.0",
        "readable-stream": "^2.0",
        "through2": "^2.0"
    },
    "description": "Compile handlebars into static files, taking data, partials and helpers from outside sources like files, database, and json through callbacks and promises.",
    "devDependencies": {
        "blanket": "^1.1",
        "chai": "^3.4",
        "coveralls": "^2.11",
        "es6-promise": "^3.0",
        "gulp": "^3.8",
        "gulp-rename": "^1.2.0",
        "mocha": "^2.1",
        "mocha-lcov-reporter": "^1.0",
        "sinon": "^1.12",
        "vinyl": "^1.0",
        "vinyl-fs": "^2.2"
    },
    "directories": {},
    "dist": {
        "shasum": "579c3c3103c0378830cddbb68d1d9028d32fbd31",
        "tarball": "https://registry.npmjs.org/gulp-static-handlebars/-/gulp-static-handlebars-1.2.0.tgz"
    },
    "gitHead": "c252b4a55e979fda5cec415ff711fb881b634f28",
    "homepage": "https://github.com/TakenPilot/gulp-static-handlebars#readme",
    "keywords": [
        "gulpfriendly",
        "gulpplugin",
        "handlebars",
        "static",
        "pipe",
        "promise",
        "async"
    ],
    "license": "ISC",
    "main": "index.js",
    "maintainers": [
        {
            "name": "danestuckel"
        }
    ],
    "name": "gulp-static-handlebars",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+ssh://git@github.com/TakenPilot/gulp-static-handlebars.git"
    },
    "scripts": {
        "test": "mocha -R mocha-lcov-reporter | ./node_modules/coveralls/bin/coveralls.js"
    },
    "version": "1.2.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
