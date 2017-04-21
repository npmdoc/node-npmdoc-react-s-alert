# npmdoc-react-s-alert

#### api documentation for  [react-s-alert (v1.3.0)](https://github.com/juliancwirko/react-s-alert)  [![npm package](https://img.shields.io/npm/v/npmdoc-react-s-alert.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-react-s-alert) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-react-s-alert.svg)](https://travis-ci.org/npmdoc/node-npmdoc-react-s-alert)

#### Alerts / Notifications for React with rich configuration options

[![NPM](https://nodei.co/npm/react-s-alert.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/react-s-alert)

- [https://npmdoc.github.io/node-npmdoc-react-s-alert/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-react-s-alert/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-react-s-alert/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-react-s-alert/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-react-s-alert/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-react-s-alert/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Julian Ćwirko"
    },
    "bugs": {
        "url": "https://github.com/juliancwirko/react-s-alert/issues"
    },
    "dependencies": {
        "babel-runtime": "^6.23.0"
    },
    "description": "Alerts / Notifications for React with rich configuration options",
    "devDependencies": {
        "babel-cli": "^6.24.1",
        "babel-core": "^6.24.1",
        "babel-eslint": "^7.2.1",
        "babel-plugin-transform-es2015-modules-umd": "^6.24.1",
        "babel-plugin-transform-runtime": "^6.23.0",
        "babel-polyfill": "^6.23.0",
        "babel-preset-es2015": "^6.24.1",
        "babel-preset-react": "^6.24.1",
        "babel-preset-stage-2": "^6.24.1",
        "chai": "^3.5.0",
        "enzyme": "^2.8.0",
        "eslint": "^3.19.0",
        "eslint-plugin-babel": "^4.1.1",
        "eslint-plugin-react": "^6.10.3",
        "jsdom": "^9.12.0",
        "mocha": "^3.2.0",
        "nodemon": "^1.11.0",
        "prop-types": "^15.5.4",
        "react": "^15.5.0",
        "react-dom": "^15.5.0"
    },
    "directories": {},
    "dist": {
        "shasum": "d81224a474f15e89c35c0ea6c2a73f232a767128",
        "tarball": "https://registry.npmjs.org/react-s-alert/-/react-s-alert-1.3.0.tgz"
    },
    "gitHead": "8678a778cd529daafa1e7e17e9652f2760eb444a",
    "homepage": "https://github.com/juliancwirko/react-s-alert",
    "keywords": [
        "react-component",
        "react",
        "alert",
        "alerts",
        "react-alert",
        "react-alerts",
        "notifications",
        "react-notifications",
        "errors",
        "react-errors",
        "toastr"
    ],
    "license": "MIT",
    "maintainers": [
        {
            "name": "juliancwirko"
        }
    ],
    "name": "react-s-alert",
    "optionalDependencies": {},
    "options": {
        "mocha": "--require scripts/mocha_runner lib/**/__tests__/**/*.js"
    },
    "peerDependencies": {
        "react": "^15.0.0",
        "react-dom": "^15.0.0",
        "prop-types": "^15.5.4"
    },
    "repository": {
        "type": "git",
        "url": "git+https://github.com/juliancwirko/react-s-alert.git"
    },
    "scripts": {
        "lint": "eslint ./lib",
        "lintfix": "eslint ./lib --fix",
        "prepublish": "babel --plugins transform-es2015-modules-umd lib --ignore __tests__ --out-dir ./dist",
        "test": "npm run lint && npm run testonly",
        "testonly": "mocha $npm_package_options_mocha"
    },
    "version": "1.3.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
