# npmtest-v8-profiler

#### basic test coverage for  [v8-profiler (v5.7.0)](http://github.com/node-inspector/v8-profiler)  [![npm package](https://img.shields.io/npm/v/npmtest-v8-profiler.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-v8-profiler) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-v8-profiler.svg)](https://travis-ci.org/npmtest/node-npmtest-v8-profiler)

#### node bindings for the v8 profiler

[![NPM](https://nodei.co/npm/v8-profiler.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/v8-profiler)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-v8-profiler/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-v8-profiler/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-v8-profiler/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-v8-profiler/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-v8-profiler/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-v8-profiler/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-v8-profiler/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-v8-profiler/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-v8-profiler/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-v8-profiler/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-v8-profiler/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-v8-profiler/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-v8-profiler/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-v8-profiler/build/test-report.html](https://npmtest.github.io/node-npmtest-v8-profiler/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-v8-profiler/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-v8-profiler/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-v8-profiler/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-v8-profiler/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-v8-profiler/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-v8-profiler/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-v8-profiler/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-v8-profiler/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Danny Coates"
    },
    "binary": {
        "module_name": "profiler",
        "module_path": "./build/{module_name}/v{version}/{node_abi}-{platform}-{arch}/",
        "remote_path": "./{module_name}/v{version}/",
        "package_name": "{node_abi}-{platform}-{arch}.tar.gz",
        "host": "https://node-inspector.s3.amazonaws.com/"
    },
    "bugs": {
        "url": "https://github.com/node-inspector/v8-profiler/issues"
    },
    "contributors": [
        {
            "name": "Miroslav Bajtoš"
        },
        {
            "name": "3y3"
        }
    ],
    "dependencies": {
        "nan": "^2.5.1",
        "node-pre-gyp": "^0.6.34"
    },
    "description": "node bindings for the v8 profiler",
    "devDependencies": {
        "aws-sdk": "^2.0.0",
        "chai": "^1.9.1",
        "co": "^4.6.0",
        "mocha": "^1.20.1",
        "rimraf": "^2.4.4"
    },
    "directories": {},
    "dist": {
        "shasum": "e8381cbebb5b5fd0ca8d2b09f6a0181a158db34d",
        "tarball": "https://registry.npmjs.org/v8-profiler/-/v8-profiler-5.7.0.tgz"
    },
    "engines": {
        "node": ">=0.10"
    },
    "gitHead": "ce5bbb902821f56b628936f4fa5fc9c6d8b4a655",
    "homepage": "http://github.com/node-inspector/v8-profiler",
    "keywords": [
        "profiler",
        "inspector"
    ],
    "license": "BSD-2-Clause",
    "main": "v8-profiler",
    "maintainers": [
        {
            "name": "dannycoates"
        },
        {
            "name": "bajtos"
        },
        {
            "name": "3y3"
        }
    ],
    "name": "v8-profiler",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/node-inspector/v8-profiler.git"
    },
    "scripts": {
        "install": "node-pre-gyp install --fallback-to-build",
        "preinstall": "node -e 'process.exit(0)'",
        "rebuild": "node-pre-gyp rebuild",
        "release": "node ./tools/release.js $@",
        "test": "mocha --debug"
    },
    "version": "5.7.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
