# npmtest-cardinal

#### basic test coverage for  [cardinal (v1.0.0)](https://github.com/thlorenz/cardinal#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-cardinal.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-cardinal) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-cardinal.svg)](https://travis-ci.org/npmtest/node-npmtest-cardinal)

#### Syntax highlights JavaScript code with ANSI colors to be printed to the terminal.

[![NPM](https://nodei.co/npm/cardinal.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/cardinal)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-cardinal/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-cardinal/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-cardinal/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-cardinal/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-cardinal/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-cardinal/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-cardinal/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-cardinal/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-cardinal/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-cardinal/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-cardinal/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-cardinal/build/test-report.html](https://npmtest.github.io/node-npmtest-cardinal/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-cardinal/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-cardinal/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-cardinal/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-cardinal/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-cardinal/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-cardinal/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-cardinal/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-cardinal/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Thorsten Lorenz",
        "url": "thlorenz.com"
    },
    "bin": {
        "cdl": "./bin/cdl.js"
    },
    "bugs": {
        "url": "https://github.com/thlorenz/cardinal/issues"
    },
    "dependencies": {
        "ansicolors": "~0.2.1",
        "redeyed": "~1.0.0"
    },
    "description": "Syntax highlights JavaScript code with ANSI colors to be printed to the terminal.",
    "devDependencies": {
        "readdirp": "~0.2.1",
        "tap": "~0.3.1"
    },
    "directories": {},
    "dist": {
        "shasum": "50e21c1b0aa37729f9377def196b5a9cec932ee9",
        "tarball": "https://registry.npmjs.org/cardinal/-/cardinal-1.0.0.tgz"
    },
    "gitHead": "ce0befef82535d86218fc32e5872809212e4b274",
    "homepage": "https://github.com/thlorenz/cardinal#readme",
    "keywords": [
        "syntax",
        "highlight",
        "theme",
        "javascript",
        "json",
        "terminal",
        "console",
        "print",
        "output"
    ],
    "license": "MIT",
    "main": "cardinal.js",
    "maintainers": [
        {
            "name": "thlorenz"
        }
    ],
    "name": "cardinal",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/thlorenz/cardinal.git"
    },
    "scripts": {
        "demo": "node examples/highlight-string.js; node examples/highlight-self; node examples/highlight-self-hide-semicolons;",
        "test": "tap ./test/*.js"
    },
    "version": "1.0.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
