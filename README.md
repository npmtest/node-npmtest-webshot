# test coverage for  [webshot (v0.18.0)](https://github.com/brenden/node-webshot)  [![npm package](https://img.shields.io/npm/v/npmtest-webshot.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-webshot) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-webshot.svg)](https://travis-ci.org/npmtest/node-npmtest-webshot)
#### Easy website screenshots

[![NPM](https://nodei.co/npm/webshot.png?downloads=true)](https://www.npmjs.com/package/webshot)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-webshot/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-webshot/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-webshot/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-webshot/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-webshot/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-webshot/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-webshot/tree/gh-pages/build)|

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-webshot/build/screenCapture.buildCustomOrg.browser.coverage.html.png)](https://npmtest.github.io/node-npmtest-webshot/build/coverage.html/index.html)

[![test-report](https://npmtest.github.io/node-npmtest-webshot/build/screenCapture.buildCustomOrg.browser.%252Fhome%252Ftravis%252Fbuild%252Fnpmtest%252Fnode-npmtest-webshot%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-webshot/build/test-report.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-webshot/build/screenCapture.buildApidoc.browser.%252Fhome%252Ftravis%252Fbuild%252Fnpmdoc%252Fnode-npmdoc-webshot%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-webshot/build/apidoc.html)

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
            "name": "Brenden Kokoszka",
            "email": "brenden.kokoszka@gmail.com"
        },
        {
            "name": "Matthew Chase Whittemore",
            "email": "mcwhittemore@gmail.com"
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
            "name": "bkokoszka",
            "email": "bkokoszk@nd.edu"
        }
    ],
    "name": "webshot",
    "optionalDependencies": {
        "phantomjs-prebuilt": "^2.1.3"
    },
    "readme": "ERROR: No README data found!",
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
