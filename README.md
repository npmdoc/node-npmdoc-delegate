# npmdoc-delegate

api documentation for  [delegate (v3.1.2)](https://github.com/zenorocha/delegate#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-delegate.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-delegate) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-delegate.svg)](https://travis-ci.org/npmdoc/node-npmdoc-delegate)
#### Lightweight event delegation

[![NPM](https://nodei.co/npm/delegate.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/delegate)

- [https://npmdoc.github.io/node-npmdoc-delegate/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-delegate/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-delegate/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-delegate/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-delegate/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-delegate/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "bugs": {
        "url": "https://github.com/zenorocha/delegate/issues"
    },
    "dependencies": {},
    "description": "Lightweight event delegation",
    "devDependencies": {
        "browserify": "^13.1.0",
        "chai": "^3.5.0",
        "karma": "^1.3.0",
        "karma-browserify": "^5.1.0",
        "karma-chai": "^0.1.0",
        "karma-mocha": "^1.2.0",
        "karma-phantomjs-launcher": "^1.0.2",
        "karma-sinon": "^1.0.4",
        "mocha": "^3.1.2",
        "phantomjs-polyfill": "0.0.2",
        "simulant": "^0.2.2",
        "sinon": "^1.17.6"
    },
    "directories": {},
    "dist": {
        "shasum": "1e1bc6f5cadda6cb6cbf7e6d05d0bcdd5712aebe",
        "tarball": "https://registry.npmjs.org/delegate/-/delegate-3.1.2.tgz"
    },
    "gitHead": "dc4abc8b2ac96aaa006bf2ab702513b54a77c067",
    "homepage": "https://github.com/zenorocha/delegate#readme",
    "keywords": [
        "event",
        "delegate",
        "delegation"
    ],
    "license": "MIT",
    "main": "src/delegate.js",
    "maintainers": [
        {
            "name": "zenorocha"
        }
    ],
    "name": "delegate",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/zenorocha/delegate.git"
    },
    "scripts": {
        "build": "browserify src/delegate.js -s delegate -o dist/delegate.js",
        "test": "karma start --single-run"
    },
    "version": "3.1.2"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
