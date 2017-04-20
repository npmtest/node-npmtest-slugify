# npmtest-slugify

#### basic test coverage for  [slugify (v1.1.0)](https://github.com/simov/slugify)  [![npm package](https://img.shields.io/npm/v/npmtest-slugify.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-slugify) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-slugify.svg)](https://travis-ci.org/npmtest/node-npmtest-slugify)

#### Slugifies a string

[![NPM](https://nodei.co/npm/slugify.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/slugify)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-slugify/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-slugify/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-slugify/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-slugify/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-slugify/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-slugify/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-slugify/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-slugify/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-slugify/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-slugify/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-slugify/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-slugify/build/test-report.html](https://npmtest.github.io/node-npmtest-slugify/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-slugify/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-slugify/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-slugify/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-slugify/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-slugify/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-slugify/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-slugify/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-slugify/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "slugify",
    "version": "1.1.0",
    "description": "Slugifies a string",
    "keywords": [
        "slugify",
        "slug",
        "url",
        "urlify"
    ],
    "license": "MIT",
    "homepage": "https://github.com/simov/slugify",
    "author": "Simeon Velichkov <simeonvelichkov@gmail.com> (http://simov.github.io)",
    "repository": {
        "type": "git",
        "url": "https://github.com/simov/slugify.git"
    },
    "devDependencies": {
        "coveralls": "^2.11.15",
        "eslint": "^3.12.2",
        "eslint-config-standard": "^6.2.1",
        "eslint-plugin-promise": "^3.4.0",
        "eslint-plugin-standard": "^2.0.1",
        "istanbul": "^0.4.5",
        "mocha": "^3.2.0"
    },
    "main": "./index.js",
    "files": [
        "LICENSE",
        "README.md",
        "index.js"
    ],
    "scripts": {
        "test": "npm run lint && npm run test-ci && echo Tests Passed",
        "test-ci": "mocha",
        "test-cov": "istanbul cover _mocha",
        "lint": "eslint **/*.js && echo Lint Passed"
    },
    "engines": {
        "node": ">=4.0.0"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
