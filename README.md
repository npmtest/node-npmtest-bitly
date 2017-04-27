# npmtest-bitly

#### basic test coverage for  [bitly (v4.1.1)](https://github.com/tanepiper/node-bitly)  [![npm package](https://img.shields.io/npm/v/npmtest-bitly.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-bitly) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-bitly.svg)](https://travis-ci.org/npmtest/node-npmtest-bitly)

#### A Bit.ly API library for Node.JS

[![NPM](https://nodei.co/npm/bitly.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/bitly)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-bitly/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-bitly/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-bitly/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-bitly/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-bitly/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-bitly/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-bitly/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-bitly/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-bitly/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-bitly/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-bitly/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-bitly/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-bitly/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-bitly/build/test-report.html](https://npmtest.github.io/node-npmtest-bitly/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-bitly/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-bitly/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-bitly/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-bitly/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-bitly/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-bitly/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-bitly/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-bitly/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Tane Piper",
        "url": "https://github.com/tanepiper"
    },
    "bugs": {
        "url": "https://github.com/tanepiper/node-bitly/issues"
    },
    "contributors": [
        {
            "name": "Tane Piper"
        },
        {
            "name": "François de Metz"
        },
        {
            "name": "zephrax"
        },
        {
            "name": "jessefulton"
        },
        {
            "name": "coaxial"
        },
        {
            "name": "Ildar Sagdejev"
        }
    ],
    "dependencies": {
        "boom": "^2.10.0",
        "isomorphic-fetch": "^2.2.0",
        "valid-url": "^1.0.9"
    },
    "description": "A Bit.ly API library for Node.JS",
    "devDependencies": {
        "babel": "^5.8.29",
        "chai": "^3.4.0",
        "istanbul": "^0.4.0",
        "mocha": "^2.3.3",
        "sepia": "^2.0.1"
    },
    "directories": {},
    "dist": {
        "shasum": "919e93ed3a4a7060a8b6e3f9559d77152d12ce24",
        "tarball": "https://registry.npmjs.org/bitly/-/bitly-4.1.1.tgz"
    },
    "engines": {
        "node": ">= 0.12.0"
    },
    "gitHead": "620ef55c844768e01745471858a84e63a613c5d9",
    "homepage": "https://github.com/tanepiper/node-bitly",
    "keywords": [
        "url",
        "bitly",
        "shortner",
        "util"
    ],
    "license": "MIT",
    "main": "lib/bitly.js",
    "maintainers": [
        {
            "name": "tanepiper"
        }
    ],
    "name": "bitly",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/tanepiper/node-bitly.git"
    },
    "scripts": {
        "compile": "babel --source-maps --out-dir lib/ src/",
        "coverage": "istanbul cover node_modules/mocha/bin/_mocha -- --compilers js:babel/register --colors --reporter dot test/",
        "prepublish": "npm run compile",
        "test": "mocha test/ --recursive --compilers js:babel/register"
    },
    "version": "4.1.1",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
