# npmtest-marko

#### basic test coverage for  [marko (v4.2.8)](http://markojs.com/)  [![npm package](https://img.shields.io/npm/v/npmtest-marko.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-marko) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-marko.svg)](https://travis-ci.org/npmtest/node-npmtest-marko)

#### Marko is an extensible, streaming, asynchronous, high performance, HTML-based templating language that can be used in Node.js or in the browser.

[![NPM](https://nodei.co/npm/marko.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/marko)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-marko/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-marko/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-marko/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-marko/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-marko/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-marko/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-marko/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-marko/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-marko/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-marko/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-marko/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-marko/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-marko/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-marko/build/test-report.html](https://npmtest.github.io/node-npmtest-marko/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-marko/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-marko/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-marko/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-marko/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-marko/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-marko/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-marko/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-marko/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Patrick Steele-Idem"
    },
    "bin": {
        "markoc": "bin/markoc"
    },
    "browser": {
        "./node-require.js": "./node-require-browser.js"
    },
    "bugs": {
        "url": "https://github.com/marko-js/marko/issues"
    },
    "dependencies": {
        "app-module-path": "^2.2.0",
        "argly": "^1.0.0",
        "browser-refresh-client": "^1.0.0",
        "char-props": "~0.1.5",
        "complain": "^1.0.0",
        "deresolve": "^1.1.2",
        "escodegen": "^1.8.1",
        "esprima": "^3.1.1",
        "estraverse": "^4.2.0",
        "events": "^1.0.2",
        "events-light": "^1.0.0",
        "he": "^1.1.0",
        "htmljs-parser": "^2.3.2",
        "lasso-caching-fs": "^1.0.1",
        "lasso-modules-client": "^2.0.3",
        "lasso-package-root": "^1.0.1",
        "listener-tracker": "^2.0.0",
        "minimatch": "^3.0.2",
        "object-assign": "^4.1.0",
        "property-handlers": "^1.0.0",
        "raptor-async": "^1.1.2",
        "raptor-json": "^1.0.1",
        "raptor-logging": "^1.0.1",
        "raptor-polyfill": "^1.0.0",
        "raptor-promises": "^1.0.1",
        "raptor-regexp": "^1.0.0",
        "raptor-util": "^3.2.0",
        "resolve-from": "^2.0.0",
        "simple-sha1": "^2.1.0",
        "strip-json-comments": "^2.0.1",
        "try-require": "^1.2.1",
        "warp10": "^1.0.0"
    },
    "description": "Marko is an extensible, streaming, asynchronous, high performance, HTML-based templating language that can be used in Node.js or in the browser.",
    "devDependencies": {
        "async": "^2.1.4",
        "benchmark": "^2.1.1",
        "bluebird": "^3.4.7",
        "browser-refresh": "^1.6.0",
        "browser-refresh-taglib": "^1.1.0",
        "chai": "^3.3.0",
        "child-process-promise": "^2.0.3",
        "coveralls": "^2.11.9",
        "express": "^4.13.4",
        "fs-extra": "^2.0.0",
        "ignoring-watcher": "^1.0.2",
        "istanbul-lib-instrument": "^1.3.0",
        "jquery": "^3.1.1",
        "jsdom": "^9.6.0",
        "jshint": "^2.5.0",
        "lasso": "^2.4.1",
        "lasso-marko": "^2.1.0",
        "lasso-resolve-from": "^1.2.0",
        "md5-hex": "^2.0.0",
        "mkdirp": "^0.5.1",
        "mocha": "^3.2.0",
        "mocha-phantomjs-core": "^2.1.1",
        "mocha-phantomjs-istanbul": "0.0.2",
        "nyc": "^10.0.0",
        "open": "0.0.5",
        "phantomjs-prebuilt": "^2.1.13",
        "promise-polyfill": "^6.0.2",
        "request": "^2.72.0",
        "require-self-ref": "^2.0.1",
        "serve-static": "^1.11.1",
        "through": "^2.3.4",
        "through2": "^2.0.1"
    },
    "directories": {},
    "dist": {
        "shasum": "9d59928284850f27e014377eb5194c83465f0edb",
        "tarball": "https://registry.npmjs.org/marko/-/marko-4.2.8.tgz"
    },
    "gitHead": "9604a853ee3a2f487caa9add6a0173d02301109f",
    "homepage": "http://markojs.com/",
    "keywords": [
        "templating",
        "template",
        "async",
        "streaming",
        "components",
        "components",
        "ui",
        "vdom",
        "dom",
        "morphdom",
        "virtual",
        "virtual-dom"
    ],
    "license": "MIT",
    "logo": {
        "url": "https://raw.githubusercontent.com/marko-js/branding/master/marko-logo-small.png"
    },
    "main": "runtime/index.js",
    "maintainers": [
        {
            "name": "mlrawlings"
        },
        {
            "name": "philidem"
        },
        {
            "name": "pnidem"
        }
    ],
    "minprops": {
        "exclude": [
            "$c",
            "b",
            "be",
            "c",
            "ca",
            "d",
            "e",
            "ee",
            "h",
            "id",
            "n",
            "r",
            "sa",
            "t"
        ],
        "matchPrefix": "$__"
    },
    "name": "marko",
    "nyc": {
        "exclude": [
            "**/benchmark/**",
            "**/coverage/**",
            "**/test/**"
        ]
    },
    "optionalDependencies": {},
    "publishConfig": {
        "registry": "https://registry.npmjs.org/"
    },
    "repository": {
        "type": "git",
        "url": "git+https://github.com/marko-js/marko.git"
    },
    "scripts": {
        "coveralls": "nyc report --reporter=text-lcov | coveralls",
        "jshint": "jshint compiler/ runtime/ taglibs/ components/",
        "mocha": "mocha --ui bdd --reporter spec ./test/",
        "test": "npm run jshint -s && npm run mocha -s && npm run test-components -s && npm run test-components-deprecated -s",
        "test-async": "mocha --ui bdd --reporter spec ./test/async-render-test",
        "test-components": "npm run test-components-browser -s && npm run test-components-pages -s",
        "test-components-browser": "node test/browser-tests-runner/cli.js test/components-browser-tests.js --automated",
        "test-components-browser-deprecated": "node test/browser-tests-runner/cli.js test/deprecated-components-browser-tests.js --automated && npm run test-components-pages-deprecated -s",
        "test-components-browser-dev": "browser-refresh test/browser-tests-runner/cli.js test/components-browser-tests.js --server",
        "test-components-deprecated": "npm run test-components-browser-deprecated -s && npm run test-components-pages-deprecated -s",
        "test-components-pages": "node test/browser-tests-runner/cli.js --pages --automated",
        "test-components-pages-deprecated": "node test/browser-tests-runner/cli.js --pagesDeprecated --automated",
        "test-coverage": "npm run test-generate-coverage && nyc report --reporter=html && open ./coverage/index.html",
        "test-express": "mocha --ui bdd --reporter spec ./test/express-test",
        "test-fast": "mocha --ui bdd --reporter spec ./test/render-test",
        "test-generate-coverage": "nyc -asc npm run test",
        "test-page": "node test/browser-tests-runner/cli.js test/components-browser-tests.js --automated --page",
        "test-pages": "npm run test-components-pages",
        "test-taglib-loader": "mocha --ui bdd --reporter spec ./test/taglib-loader-test"
    },
    "version": "4.2.8"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
