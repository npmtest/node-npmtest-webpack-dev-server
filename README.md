# npmtest-webpack-dev-server

#### basic test coverage for  [webpack-dev-server (v2.4.2)](http://github.com/webpack/webpack-dev-server)  [![npm package](https://img.shields.io/npm/v/npmtest-webpack-dev-server.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-webpack-dev-server) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-webpack-dev-server.svg)](https://travis-ci.org/npmtest/node-npmtest-webpack-dev-server)

#### Serves a webpack app. Updates the browser on changes.

[![NPM](https://nodei.co/npm/webpack-dev-server.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/webpack-dev-server)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-webpack-dev-server/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-webpack-dev-server/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-webpack-dev-server/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-webpack-dev-server/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-webpack-dev-server/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-webpack-dev-server/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-webpack-dev-server/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-webpack-dev-server/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-webpack-dev-server/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-webpack-dev-server/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-webpack-dev-server/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-webpack-dev-server/build/test-report.html](https://npmtest.github.io/node-npmtest-webpack-dev-server/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-webpack-dev-server/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-webpack-dev-server/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-webpack-dev-server/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-webpack-dev-server/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-webpack-dev-server/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-webpack-dev-server/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-webpack-dev-server/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-webpack-dev-server/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Tobias Koppers @sokra"
    },
    "bin": {
        "webpack-dev-server": "bin/webpack-dev-server.js"
    },
    "bugs": {
        "url": "https://github.com/webpack/webpack-dev-server/issues"
    },
    "dependencies": {
        "ansi-html": "0.0.7",
        "chokidar": "^1.6.0",
        "compression": "^1.5.2",
        "connect-history-api-fallback": "^1.3.0",
        "express": "^4.13.3",
        "html-entities": "^1.2.0",
        "http-proxy-middleware": "~0.17.4",
        "opn": "4.0.2",
        "portfinder": "^1.0.9",
        "serve-index": "^1.7.2",
        "sockjs": "0.3.18",
        "sockjs-client": "1.1.2",
        "spdy": "^3.4.1",
        "strip-ansi": "^3.0.0",
        "supports-color": "^3.1.1",
        "webpack-dev-middleware": "^1.9.0",
        "yargs": "^6.0.0"
    },
    "description": "Serves a webpack app. Updates the browser on changes.",
    "devDependencies": {
        "codecov.io": "^0.1.6",
        "css-loader": "~0.26.1",
        "eslint": "^3.4.0",
        "file-loader": "~0.10.0",
        "istanbul": "^0.4.5",
        "jquery": "^2.2.0",
        "less": "^2.5.1",
        "less-loader": "~2.2.0",
        "mocha": "^3.0.2",
        "mocha-sinon": "^1.1.6",
        "pug": "^2.0.0-beta5",
        "pug-loader": "^2.3.0",
        "should": "^11.1.0",
        "sinon": "^1.17.6",
        "style-loader": "~0.13.0",
        "supertest": "^2.0.1",
        "url-loader": "~0.5.6",
        "webpack": "^2.2.0",
        "ws": "^1.1.1"
    },
    "directories": {},
    "dist": {
        "shasum": "cf595d6b40878452b6d2ad7229056b686f8a16be",
        "tarball": "https://registry.npmjs.org/webpack-dev-server/-/webpack-dev-server-2.4.2.tgz"
    },
    "engines": {
        "node": ">=4.7"
    },
    "files": [
        "lib/",
        "bin",
        "client/",
        "ssl/"
    ],
    "gitHead": "60e47270860165d41fe4654d78aa2fee8dbdcdc1",
    "homepage": "http://github.com/webpack/webpack-dev-server",
    "license": "MIT",
    "main": "lib/Server.js",
    "maintainers": [
        {
            "name": "jhnns"
        },
        {
            "name": "sokra"
        },
        {
            "name": "spacek33z"
        }
    ],
    "name": "webpack-dev-server",
    "optionalDependencies": {},
    "peerDependencies": {
        "webpack": "^2.2.0"
    },
    "repository": {
        "type": "git",
        "url": "git://github.com/webpack/webpack-dev-server.git"
    },
    "scripts": {
        "beautify": "npm run lint -- --fix",
        "client-index": "webpack ./client/index.js client/index.bundle.js --color --config client/webpack.config.js -p",
        "client-live": "webpack ./client/live.js client/live.bundle.js --color --config client/webpack.config.js -p",
        "client-sockjs": "webpack ./client/sockjs.js client/sockjs.bundle.js --color --config client/webpack.sockjs.config.js -p",
        "cover": "istanbul cover node_modules/mocha/bin/_mocha",
        "lint": "eslint bin lib test examples client/{index,live,socket,sockjs,overlay,webpack.config}.js",
        "posttest": "npm run -s lint",
        "prepublish": "npm run -s client-live && npm run -s client-index && npm run -s client-sockjs",
        "test": "mocha --full-trace --check-leaks",
        "travis": "npm run cover -- --report lcovonly && npm run lint"
    },
    "version": "2.4.2"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
