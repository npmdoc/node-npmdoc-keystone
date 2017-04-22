# npmdoc-keystone

#### api documentation for  [keystone (v4.0.0-beta.5)](http://keystonejs.com/)  [![npm package](https://img.shields.io/npm/v/npmdoc-keystone.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-keystone) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-keystone.svg)](https://travis-ci.org/npmdoc/node-npmdoc-keystone)

#### Web Application Framework and Admin GUI / Content Management System built on Express.js and Mongoose

[![NPM](https://nodei.co/npm/keystone.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/keystone)

- [https://npmdoc.github.io/node-npmdoc-keystone/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-keystone/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-keystone/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-keystone/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-keystone/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-keystone/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Jed Watson"
    },
    "browserify": {
        "transform": [
            "browserify-shim"
        ]
    },
    "browserify-shim": {
        "tinymce": "global:tinymce",
        "jquery": "global:$",
        "codemirror": "global:CodeMirror",
        "underscore": "global:_"
    },
    "bugs": {
        "url": "https://github.com/keystonejs/keystone/issues"
    },
    "dependencies": {
        "aphrodite": "1.1.0",
        "async": "2.1.4",
        "asyncdi": "1.1.0",
        "babel-core": "6.22.1",
        "babel-plugin-transform-object-assign": "6.22.0",
        "babel-polyfill": "6.22.0",
        "babel-preset-es2015": "6.22.0",
        "babel-preset-react": "6.22.0",
        "babel-preset-stage-2": "6.22.0",
        "babelify": "7.3.0",
        "babyparse": "0.4.6",
        "bcrypt-nodejs": "~0.0.3",
        "blacklist": "1.1.4",
        "body-parser": "1.16.0",
        "brfs": "1.4.3",
        "browserify": "13.3.0",
        "browserify-shim": "3.8.12",
        "caller-id": "0.1.0",
        "chalk": "1.1.3",
        "classnames": "2.2.5",
        "cloudinary": "1.5.0",
        "cloudinary-microurl": "1.0.2",
        "compression": "1.6.2",
        "connect-flash": "0.1.1",
        "cookie-parser": "1.4.3",
        "debug": "2.6.0",
        "display-name": "0.1.0",
        "ejs": "2.5.5",
        "elemental": "0.6.1",
        "embedly": "2.1.0",
        "errorhandler": "1.5.0",
        "es6-promise": "4.0.5",
        "express": "4.14.0",
        "express-request-language": "1.1.9",
        "express-session": "1.15.0",
        "expression-match": "0.0.17",
        "fs-extra": "1.0.0",
        "grappling-hook": "3.0.0",
        "i": "0.3.5",
        "kerberos": "0.0.22",
        "keystone-storage-namefunctions": "1.1.1",
        "keystone-utils": "0.4.0",
        "knox": "0.9.2",
        "less-middleware": "2.2.0",
        "letsencrypt-express": "2.0.6",
        "list-to-array": "1.1.0",
        "lodash": "4.17.4",
        "marked": "0.3.6",
        "method-override": "2.3.7",
        "mime-types": "2.1.14",
        "moment": "2.17.1",
        "mongoose": "4.7.8",
        "morgan": "1.7.0",
        "multer": "0.1.8",
        "numeral": "2.0.4",
        "object-assign": "4.1.1",
        "qs": "4.0.0",
        "queryfilter": "0.0.4",
        "range_check": "1.4.0",
        "react": "15.4.2",
        "react-addons-css-transition-group": "15.4.2",
        "react-alt-text": "2.0.0",
        "react-color": "2.11.1",
        "react-day-picker": "2.5.0",
        "react-dnd": "2.1.4",
        "react-dnd-html5-backend": "2.1.2",
        "react-dom": "15.4.2",
        "react-domify": "0.2.6",
        "react-images": "0.5.2",
        "react-markdown": "2.4.4",
        "react-redux": "5.0.2",
        "react-router": "3.0.2",
        "react-router-redux": "4.0.7",
        "react-select": "1.0.0-rc.1",
        "redux": "3.6.0",
        "redux-saga": "0.14.3",
        "redux-thunk": "2.2.0",
        "sanitize-filename": "1.6.1",
        "scmp": "1.0.2",
        "semver": "5.3.0",
        "serve-favicon": "2.3.2",
        "string-to-stream": "1.1.0",
        "vkey": "1.0.1",
        "watchify": "3.8.0",
        "xhr": "2.3.3"
    },
    "description": "Web Application Framework and Admin GUI / Content Management System built on Express.js and Mongoose",
    "devDependencies": {
        "browserify-middleware": "7.1.0",
        "codeclimate-test-reporter": "0.4.0",
        "connect-mongo": "1.3.2",
        "core-assert": "0.2.1",
        "disc": "1.3.2",
        "enzyme": "2.7.1",
        "eslint": "3.14.0",
        "eslint-config-keystone": "3.0.0",
        "eslint-config-keystone-react": "1.0.0",
        "eslint-plugin-react": "6.9.0",
        "istanbul": "0.4.5",
        "keystone-email": "1.0.5",
        "keystone-nightwatch-e2e": "0.2.13",
        "mocha": "3.2.0",
        "must": "0.13.4",
        "proxyquire": "1.7.10",
        "react-addons-test-utils": "15.4.2",
        "react-engine": "4.2.1",
        "rimraf": "2.5.4",
        "sinon": "1.17.7",
        "superagent": "3.3.2",
        "supertest": "2.0.1",
        "uglify-js": "2.7.5",
        "updtr": "0.2.3",
        "watch": "1.0.1"
    },
    "directories": {},
    "dist": {
        "shasum": "300d623b35d400185252cc80bd95586b6a0da019",
        "tarball": "https://registry.npmjs.org/keystone/-/keystone-4.0.0-beta.5.tgz"
    },
    "engines": {
        "node": ">= 0.12.0",
        "npm": ">= 3.0.0"
    },
    "gitHead": "ef3fd612285315ea8e12f68da4c8d6031e2c7fe7",
    "homepage": "http://keystonejs.com/",
    "keywords": [
        "express",
        "web",
        "app",
        "cms",
        "admin",
        "framework",
        "mongoose",
        "gui",
        "site",
        "website",
        "forms"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "jedwatson"
        },
        {
            "name": "mxstbr"
        }
    ],
    "name": "keystone",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/keystonejs/keystone.git"
    },
    "scripts": {
        "build": "NODE_ENV=production node build.js | uglifyjs -mc warnings=false,screw_ie8=true -b beautify=false,semicolons=false > ./admin/public/js/packages.js",
        "build-dev": "node build.js > ./admin/public/js/packages.js",
        "clean": "rimraf ./coverage",
        "current": "updtr",
        "fields-explorer": "node ./fields/explorer/server.js",
        "lint": "eslint .",
        "lint-fix": "eslint . --fix",
        "posttest-cov": "if [ -n \"$CODECLIMATE_REPO_TOKEN\" ]; then codeclimate-test-reporter < coverage/lcov.info; fi",
        "pretest": "npm run lint && node test/pretest.js",
        "pretest-cov": "npm run clean && npm run lint",
        "test": "mocha && mocha --opts test/mocha-admin.opts",
        "test-admin": "mocha --opts test/mocha-admin.opts",
        "test-all": "npm test && npm run test-e2e-bg",
        "test-cov": "istanbul cover ./node_modules/mocha/bin/_mocha",
        "test-e2e": "node test/e2e/server.js --env default",
        "test-e2e-bg": "export KNE_SELENIUM_START_PROCESS=false && node test/e2e/server.js --env default",
        "test-e2e-saucelabs": "if [ -n \"$SAUCE_ACCESS_KEY\" ]; then node test/e2e/server.js --env saucelabs-travis; fi",
        "test-e2e-saucelabs-group": "if [ -n \"$SAUCE_ACCESS_KEY\" ]; then node test/e2e/server.js --env saucelabs-travis --group ./test/e2e/adminUI/tests/$GROUP; fi",
        "test-unit": "node test/pretest.js && mocha",
        "watch": "watch 'clear && npm run lint' lib admin server test"
    },
    "version": "4.0.0-beta.5",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
