# npmtest-commander

#### basic test coverage for  [commander (2.15.1)](https://github.com/tj/commander.js#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-commander.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-commander) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-commander.svg)](https://travis-ci.org/npmtest/node-npmtest-commander)

#### the complete solution for node.js command-line programs

[![NPM](https://nodei.co/npm/commander.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/commander)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-commander/tree/alpha)|
|--:|:--|
| coverage : | [![coverage](https://npmtest.github.io/node-npmtest-commander/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-commander/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-commander/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-commander/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-commander/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-commander/build/app) || build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-commander/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-commander/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-commander/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-commander/build/coverage.html/index.html)

[![coverage](https://npmtest.github.io/node-npmtest-commander/build/screenshot.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-commander/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-commander/build/test-report.html](https://npmtest.github.io/node-npmtest-commander/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-commander/build/screenshot.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-commander/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-commander/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-commander/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-commander/build/screenshot.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-commander/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-commander/build/screenshot.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-commander/build/screenshot.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "TJ Holowaychuk"
    },
    "bugs": {
        "url": "https://github.com/tj/commander.js/issues"
    },
    "dependencies": {},
    "description": "the complete solution for node.js command-line programs",
    "devDependencies": {
        "@types/node": "^7.0.55",
        "eslint": "^3.19.0",
        "should": "^11.2.1",
        "sinon": "^2.4.1",
        "standard": "^10.0.3",
        "typescript": "^2.7.2"
    },
    "directories": {},
    "dist": {
        "integrity": "sha512-VlfT9F3V0v+jr4yxPc5gg9s62/fIVWsd2Bk2iD435um1NlGMYdVCq+MjcXnhYq2icNOizHr1kK+5TI6H0Hy0ag==",
        "shasum": "df46e867d0fc2aec66a34662b406a9ccafff5b0f",
        "tarball": "https://registry.npmjs.org/commander/-/commander-2.15.1.tgz",
        "fileCount": 6,
        "unpackedSize": 59781
    },
    "files": [
        "index.js",
        "typings/index.d.ts"
    ],
    "gitHead": "649eaef336ddc7224eb5c73e4a958685e24de25e",
    "homepage": "https://github.com/tj/commander.js#readme",
    "keywords": [
        "commander",
        "command",
        "option",
        "parser"
    ],
    "license": "MIT",
    "main": "index",
    "maintainers": [
        {
            "name": "abetomo"
        },
        {
            "name": "somekittens"
        },
        {
            "name": "tjholowaychuk"
        },
        {
            "name": "vanesyan"
        },
        {
            "name": "zhiyelee"
        }
    ],
    "name": "commander",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/tj/commander.js.git"
    },
    "scripts": {
        "lint": "eslint index.js",
        "test": "make test && npm run test-typings",
        "test-typings": "node_modules/typescript/bin/tsc -p tsconfig.json"
    },
    "typings": "typings/index.d.ts",
    "version": "2.15.1",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
