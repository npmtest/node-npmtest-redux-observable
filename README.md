# npmtest-redux-observable

#### basic test coverage for  [redux-observable (v0.14.1)](https://github.com/redux-observable/redux-observable#README.md)  [![npm package](https://img.shields.io/npm/v/npmtest-redux-observable.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-redux-observable) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-redux-observable.svg)](https://travis-ci.org/npmtest/node-npmtest-redux-observable)

#### RxJS based middleware for Redux. Compose and cancel async actions and more.

[![NPM](https://nodei.co/npm/redux-observable.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/redux-observable)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-redux-observable/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-redux-observable/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-redux-observable/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-redux-observable/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-redux-observable/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-redux-observable/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-redux-observable/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-redux-observable/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-redux-observable/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-redux-observable/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-redux-observable/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-redux-observable/build/test-report.html](https://npmtest.github.io/node-npmtest-redux-observable/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-redux-observable/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-redux-observable/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-redux-observable/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-redux-observable/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-redux-observable/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-redux-observable/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-redux-observable/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-redux-observable/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "bugs": {
        "url": "https://github.com/redux-observable/redux-observable/issues"
    },
    "contributors": [
        {
            "name": "Ben Lesh"
        },
        {
            "name": "Jay Phelps"
        }
    ],
    "dependencies": {},
    "description": "RxJS based middleware for Redux. Compose and cancel async actions and more.",
    "devDependencies": {
        "@types/chai": "^3.4.34",
        "@types/es6-shim": "^0.31.32",
        "@types/mocha": "^2.2.33",
        "@types/sinon": "^1.16.32",
        "babel-cli": "^6.11.4",
        "babel-eslint": "^7.0.0",
        "babel-loader": "^6.2.4",
        "babel-plugin-transform-es2015-modules-commonjs": "^6.11.5",
        "babel-plugin-transform-function-bind": "^6.8.0",
        "babel-plugin-transform-object-rest-spread": "^6.8.0",
        "babel-polyfill": "^6.13.0",
        "babel-preset-es2015": "^6.13.2",
        "babel-register": "^6.11.6",
        "chai": "^3.5.0",
        "conventional-changelog-cli": "1.2.0",
        "cross-env": "^3.1.0",
        "eslint": "^3.2.2",
        "gitbook-cli": "^2.3.0",
        "gitbook-plugin-addcssjs": "^1.0.2",
        "gitbook-plugin-anker-enable": "^0.0.4",
        "gitbook-plugin-edit-link": "^2.0.2",
        "gitbook-plugin-github": "^3.0.0",
        "gitbook-plugin-prism": "^2.0.1",
        "gitbook-plugin-theme-default": "^1.0.5",
        "gulp": "^3.9.1",
        "gulp-babel": "^6.1.2",
        "json-server": "^0.9.0",
        "mocha": "^3.0.1",
        "redux": "^3.5.2",
        "rimraf": "^2.5.4",
        "rxjs": "^5.0.0",
        "sinon": "1.17.7",
        "typescript": "^2.1.4",
        "webpack": "^2.2.1",
        "webpack-rxjs-externals": "~1.0.0"
    },
    "directories": {},
    "dist": {
        "shasum": "9f3d870c69388fdc427ded6770a3e326f3b69693",
        "tarball": "https://registry.npmjs.org/redux-observable/-/redux-observable-0.14.1.tgz"
    },
    "files": [
        "dist",
        "lib",
        "index.d.ts",
        "README.md",
        "LICENSE"
    ],
    "gitHead": "8eb9449c6c31c96e5b123705dfb4f352f706422a",
    "homepage": "https://github.com/redux-observable/redux-observable#README.md",
    "keywords": [
        "Rx",
        "Ducks",
        "Reducks",
        "Redux",
        "middleware",
        "observable",
        "thunk",
        "async",
        "cancel",
        "action"
    ],
    "license": "MIT",
    "main": "lib/cjs/index.js",
    "maintainers": [
        {
            "name": "berkeleytrue"
        },
        {
            "name": "blesh"
        },
        {
            "name": "jayphelps"
        },
        {
            "name": "rgbkrk"
        }
    ],
    "module": "lib/es/index.js",
    "name": "redux-observable",
    "optionalDependencies": {},
    "peerDependencies": {
        "redux": "3.*",
        "rxjs": "^5.0.0"
    },
    "repository": {
        "type": "git",
        "url": "git+https://github.com/redux-observable/redux-observable.git"
    },
    "scripts": {
        "build": "npm run build:es && npm run build:cjs && npm run build:umd && npm run build:umd:min",
        "build:cjs": "babel src -d lib/cjs",
        "build:es": "gulp build:es",
        "build:tests": "rm -rf temp && babel test -d temp",
        "build:umd": "cross-env NODE_ENV=development webpack src/index.js dist/redux-observable.js",
        "build:umd:min": "cross-env NODE_ENV=production webpack src/index.js dist/redux-observable.min.js",
        "check": "npm run lint && npm run test",
        "clean": "rimraf lib temp dist",
        "docs:build": "npm run docs:prepare && gitbook build -g redux-observable/redux-observable && cp logo/favicon.ico _book/gitbook/images",
        "docs:clean": "rimraf _book",
        "docs:prepare": "gitbook install",
        "docs:publish": "npm run docs:clean && npm run docs:build && cp CNAME _book && cd _book && git init && git commit --allow-empty -m 'update book' && git checkout -b gh-pages && touch .nojekyll && git add . && git commit -am 'update book' && git push git@github.com:redux-observable/redux-observable gh-pages --force",
        "docs:watch": "gitbook serve",
        "lint": "eslint src && eslint test",
        "shipit": "npm run clean && npm run build && npm run lint && npm test && scripts/preprepublish.sh && npm publish",
        "test": "npm run lint && npm run build && npm run build:tests && mocha temp && npm run test:typings",
        "test:typings": "tsc --noImplicitAny index.d.ts test/typings.ts --outDir temp --target ES5 --moduleResolution node && cd temp && node typings.js"
    },
    "typings": "./index.d.ts",
    "version": "0.14.1",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
