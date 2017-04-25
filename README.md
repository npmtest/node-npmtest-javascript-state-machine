# npmtest-javascript-state-machine

#### basic test coverage for  [javascript-state-machine (v2.4.0)](https://github.com/jakesgordon/javascript-state-machine)  [![npm package](https://img.shields.io/npm/v/npmtest-javascript-state-machine.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-javascript-state-machine) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-javascript-state-machine.svg)](https://travis-ci.org/npmtest/node-npmtest-javascript-state-machine)

#### A simple finite state machine library

[![NPM](https://nodei.co/npm/javascript-state-machine.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/javascript-state-machine)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-javascript-state-machine/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-javascript-state-machine/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-javascript-state-machine/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-javascript-state-machine/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-javascript-state-machine/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-javascript-state-machine/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-javascript-state-machine/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-javascript-state-machine/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-javascript-state-machine/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-javascript-state-machine/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-javascript-state-machine/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-javascript-state-machine/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-javascript-state-machine/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-javascript-state-machine/build/test-report.html](https://npmtest.github.io/node-npmtest-javascript-state-machine/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-javascript-state-machine/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-javascript-state-machine/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-javascript-state-machine/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-javascript-state-machine/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-javascript-state-machine/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-javascript-state-machine/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-javascript-state-machine/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-javascript-state-machine/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Jake Gordon"
    },
    "bugs": {
        "url": "https://github.com/jakesgordon/javascript-state-machine/issues"
    },
    "dependencies": {},
    "description": "A simple finite state machine library",
    "devDependencies": {
        "local-web-server": "~1.2.6",
        "qunit": "~0.9.1",
        "uglify-js": "^2.7.4"
    },
    "directories": {},
    "dist": {
        "shasum": "d8be31ec38f24ac1a1832f0b672fc3cd5f79c96e",
        "tarball": "https://registry.npmjs.org/javascript-state-machine/-/javascript-state-machine-2.4.0.tgz"
    },
    "gitHead": "c7538b4fce486a84de7a456b72ce7dc15201c818",
    "homepage": "https://github.com/jakesgordon/javascript-state-machine",
    "keywords": [
        "state machine",
        "server",
        "client"
    ],
    "main": "state-machine.js",
    "maintainers": [
        {
            "name": "jakesgordon"
        }
    ],
    "name": "javascript-state-machine",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/jakesgordon/javascript-state-machine.git"
    },
    "scripts": {
        "minify": "uglifyjs state-machine.js --output state-machine.min.js --compress --mangle --stats",
        "start": "ws --rewrite '/test -> /test/'",
        "test": "node test/runner"
    },
    "version": "2.4.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
