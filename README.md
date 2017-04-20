# npmtest-generator-node

#### basic test coverage for  [generator-node (v2.1.0)](https://github.com/yeoman/generator-node)  [![npm package](https://img.shields.io/npm/v/npmtest-generator-node.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-generator-node) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-generator-node.svg)](https://travis-ci.org/npmtest/node-npmtest-generator-node)

#### Create a Node.js module

[![NPM](https://nodei.co/npm/generator-node.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/generator-node)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-generator-node/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-generator-node/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-generator-node/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-generator-node/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-generator-node/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-generator-node/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-generator-node/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-generator-node/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-generator-node/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-generator-node/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-generator-node/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-generator-node/build/test-report.html](https://npmtest.github.io/node-npmtest-generator-node/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-generator-node/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-generator-node/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-generator-node/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-generator-node/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-generator-node/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-generator-node/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-generator-node/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-generator-node/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "generator-node",
    "version": "2.1.0",
    "description": "Create a Node.js module",
    "homepage": "https://github.com/yeoman/generator-node",
    "author": "Yeoman team",
    "files": [
        "index.js",
        "generators"
    ],
    "main": "index.js",
    "keywords": [
        "yeoman-generator",
        "scaffold",
        "node",
        "module",
        "cli"
    ],
    "devDependencies": {
        "coveralls": "^2.12.0",
        "eslint": "^3.18.0",
        "eslint-config-xo-space": "^0.16.0",
        "jest": "^19.0.2",
        "jest-cli": "^19.0.2",
        "nsp": "^2.6.3",
        "yeoman-assert": "^3.0.0",
        "yeoman-test": "^1.5.1"
    },
    "repository": "yeoman/generator-node",
    "scripts": {
        "pretest": "eslint . --fix",
        "test": "jest",
        "prepublish": "nsp check"
    },
    "dependencies": {
        "chalk": "^1.1.3",
        "generator-jest": "^1.2.0",
        "generator-license": "^5.1.0",
        "generator-travis": "^1.1.3",
        "git-remote-origin-url": "^2.0.0",
        "github-username": "^3.0.0",
        "inquirer-npm-name": "^2.0.0",
        "lodash": "^4.17.4",
        "parse-author": "^2.0.0",
        "yeoman-generator": "^1.1.1"
    },
    "eslintConfig": {
        "extends": "xo-space",
        "env": {
            "jest": true,
            "node": true
        }
    },
    "license": "MIT",
    "jest": {
        "testEnvironment": "node"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
