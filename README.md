# npmtest-exec

#### test coverage for  [exec (v0.2.1)](https://github.com/bahamas10/node-exec#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-exec.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-exec) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-exec.svg)](https://travis-ci.org/npmtest/node-npmtest-exec)

#### Call a child process with the ease of exec and safety of spawn

[![NPM](https://nodei.co/npm/exec.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/exec)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-exec/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-exec/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-exec/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-exec/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-exec/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-exec/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-exec/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-exec/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-exec/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-exec/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-exec/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-exec/build/test-report.html](https://npmtest.github.io/node-npmtest-exec/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-exec/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-exec/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-exec/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-exec/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-exec/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-exec/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-exec/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-exec/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Dave Eddy",
        "url": "http://www.daveeddy.com"
    },
    "bin": {},
    "bugs": {
        "url": "https://github.com/bahamas10/node-exec/issues"
    },
    "dependencies": {},
    "deprecated": "deprecated in favor of builtin child_process.execFile",
    "description": "Call a child process with the ease of exec and safety of spawn",
    "devDependencies": {},
    "directories": {},
    "dist": {
        "shasum": "2661f0bfc5532918629117cb9f80c7564af2c51f",
        "tarball": "https://registry.npmjs.org/exec/-/exec-0.2.1.tgz"
    },
    "engines": {
        "node": ">= v0.9.1"
    },
    "gitHead": "b439bd5a0dd055cea7e2f9dfbb124036be07e28b",
    "homepage": "https://github.com/bahamas10/node-exec#readme",
    "keywords": [
        "exec",
        "spawn",
        "child",
        "wordsplitting",
        "shell"
    ],
    "main": "exec.js",
    "maintainers": [
        {
            "name": "bahamas10"
        }
    ],
    "name": "exec",
    "optionalDependencies": {},
    "repository": {
        "url": "git+https://github.com/bahamas10/node-exec.git",
        "type": "git"
    },
    "scripts": {
        "test": "for f in tests/*.js; do echo \"$f\"; node \"$f\" || exit 1; echo; done; echo 'Passed'"
    },
    "version": "0.2.1"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
