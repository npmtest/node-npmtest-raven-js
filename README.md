# npmtest-raven-js

#### basic test coverage for  [raven-js (v3.14.2)](https://github.com/getsentry/raven-js)  [![npm package](https://img.shields.io/npm/v/npmtest-raven-js.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-raven-js) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-raven-js.svg)](https://travis-ci.org/npmtest/node-npmtest-raven-js)

####

[![NPM](https://nodei.co/npm/raven-js.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/raven-js)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-raven-js/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-raven-js/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-raven-js/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-raven-js/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-raven-js/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-raven-js/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-raven-js/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-raven-js/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-raven-js/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-raven-js/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-raven-js/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-raven-js/build/test-report.html](https://npmtest.github.io/node-npmtest-raven-js/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-raven-js/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-raven-js/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-raven-js/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-raven-js/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-raven-js/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-raven-js/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-raven-js/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-raven-js/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "raven-js",
    "version": "3.14.2",
    "license": "BSD-2-Clause",
    "homepage": "https://github.com/getsentry/raven-js",
    "scripts": {
        "pretest": "npm install",
        "test": "grunt test && npm run-script test-typescript",
        "test-typescript": "node_modules/typescript/bin/tsc --noEmit --noImplicitAny typescript/raven-tests.ts"
    },
    "repository": {
        "type": "git",
        "url": "git://github.com/getsentry/raven-js.git"
    },
    "main": "src/singleton.js",
    "devDependencies": {
        "bluebird": "^3.4.1",
        "browserify-versionify": "^1.0.6",
        "bundle-collapser": "^1.2.1",
        "chai": "2.3.0",
        "derequire": "2.0.3",
        "es6-promise": "^4.0.5",
        "grunt": "^0.4.5",
        "grunt-browserify": "^4.0.1",
        "grunt-cli": "^0.1.13",
        "grunt-contrib-clean": "^0.7.0",
        "grunt-contrib-concat": "^0.5.1",
        "grunt-contrib-connect": "^0.11.2",
        "grunt-contrib-copy": "^0.8.2",
        "grunt-contrib-jshint": "^0.11.3",
        "grunt-contrib-uglify": "^0.11.0",
        "grunt-eslint": "^17.3.1",
        "grunt-gitinfo": "^0.1.7",
        "grunt-mocha": "1.0.4",
        "grunt-release": "^0.13.0",
        "grunt-s3": "0.2.0-alpha.3",
        "grunt-sri": "mattrobenolt/grunt-sri#pretty",
        "jquery": "^2.1.4",
        "lodash": "^3.10.1",
        "mocha": "2.5.3",
        "proxyquireify": "^3.0.2",
        "sinon": "1.7.3",
        "through2": "^2.0.0",
        "typescript": "^1.8.10",
        "whatwg-fetch": "^1.0.0"
    },
    "keywords": [
        "exceptions",
        "debugging",
        "logging",
        "errors",
        "sentry",
        "raven"
    ],
    "typings": "typescript/raven.d.ts",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
