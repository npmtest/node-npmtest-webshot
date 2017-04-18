# npmtest-webshot

#### test coverage for  [webshot (v0.18.0)](https://github.com/brenden/node-webshot)  [![npm package](https://img.shields.io/npm/v/npmtest-webshot.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-webshot) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-webshot.svg)](https://travis-ci.org/npmtest/node-npmtest-webshot)

#### Easy website screenshots

[![NPM](https://nodei.co/npm/webshot.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/webshot)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-webshot/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-webshot/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-webshot/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-webshot/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-webshot/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-webshot/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-webshot/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-webshot/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-webshot/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-webshot/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-webshot/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-webshot/build/test-report.html](https://npmtest.github.io/node-npmtest-webshot/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-webshot/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-webshot/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-webshot/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-webshot/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-webshot/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-webshot/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-webshot/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-webshot/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Brenden Kokoszka"
    },
    "bugs": {
        "url": "https://github.com/brenden/node-webshot/issues"
    },
    "contributors": [
        {
            "name": "Brenden Kokoszka"
        },
        {
            "name": "Matthew Chase Whittemore"
        }
    ],
    "dependencies": {
        "cross-spawn": "^0.2.3",
        "graceful-fs": "~3.0.4",
        "phantomjs-prebuilt": "^2.1.3",
        "tmp": "~0.0.25"
    },
    "description": "Easy website screenshots",
    "devDependencies": {
        "imagemagick": "git://github.com/rsms/node-imagemagick.git",
        "mocha": "*",
        "should": "*"
    },
    "directories": {},
    "dist": {
        "shasum": "057e6925bc3970ae97eed56fc23118578cbcfdc3",
        "tarball": "https://registry.npmjs.org/webshot/-/webshot-0.18.0.tgz"
    },
    "engine": [
        "node >=0.7.00"
    ],
    "homepage": "https://github.com/brenden/node-webshot",
    "keywords": [
        "screenshot",
        "screengrab"
    ],
    "license": "MIT",
    "main": "./lib/webshot.js",
    "maintainers": [
        {
            "name": "bkokoszka"
        }
    ],
    "name": "webshot",
    "optionalDependencies": {
        "phantomjs-prebuilt": "^2.1.3"
    },
    "repository": {
        "type": "git",
        "url": "git+ssh://git@github.com/brenden/node-webshot.git"
    },
    "scripts": {
        "test": "mocha --ui bdd --reporter spec --require should ./test/core.js ./test/options/*"
    },
    "version": "0.18.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
