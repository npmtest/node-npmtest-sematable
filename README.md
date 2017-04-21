# npmtest-sematable

#### basic test coverage for  [sematable (v1.4.5)](https://github.com/sematext/sematable#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-sematable.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-sematable) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-sematable.svg)](https://travis-ci.org/npmtest/node-npmtest-sematable)

#### Client side sorting, pagination, and text filter for redux/react based apps

[![NPM](https://nodei.co/npm/sematable.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/sematable)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-sematable/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-sematable/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-sematable/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-sematable/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-sematable/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-sematable/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-sematable/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-sematable/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-sematable/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-sematable/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-sematable/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-sematable/build/test-report.html](https://npmtest.github.io/node-npmtest-sematable/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-sematable/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-sematable/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-sematable/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-sematable/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-sematable/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-sematable/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-sematable/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-sematable/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "sematable",
    "version": "1.4.5",
    "description": "Client side sorting, pagination, and text filter for redux/react based apps",
    "main": "lib/index.js",
    "scripts": {
        "test": "echo \"Error: no test specified\" && exit 1",
        "compile": "babel --presets es2015 -d lib/ src/",
        "prepublish": "npm run compile",
        "eslint": "./node_modules/.bin/eslint src",
        "lint": "npm run eslint",
        "storybook": "start-storybook -p 6006",
        "build-storybook": "build-storybook"
    },
    "repository": {
        "type": "git",
        "url": "git+https://github.com/sematext/sematable.git"
    },
    "keywords": [
        "redux",
        "react",
        "datatable",
        "data",
        "filter",
        "client",
        "frontend"
    ],
    "author": "Sematext Group, Inc.",
    "license": "Apache-2.0",
    "bugs": {
        "url": "https://github.com/sematext/sematable/issues"
    },
    "homepage": "https://github.com/sematext/sematable#readme",
    "babel": {
        "presets": [
            "es2015",
            "react"
        ],
        "plugins": [
            "transform-object-rest-spread"
        ]
    },
    "eslintConfig": {
        "parser": "babel-eslint",
        "extends": "airbnb",
        "env": {
            "browser": true
        },
        "rules": {
            "no-confusing-arrow": 0,
            "react/jsx-filename-extension": 0,
            "react/jsx-quotes": 0,
            "react/prefer-stateless-function": 0,
            "react/jsx-indent": [
                2,
                2
            ],
            "jsx-quotes": [
                2,
                "prefer-double"
            ]
        }
    },
    "peerDependencies": {
        "lodash": "^4.15.0",
        "react": "^15.1.0",
        "react-dom": "^15.3.2",
        "react-redux": "^4.4.5",
        "redux": "^3.4.0",
        "font-awesome": "^4.7.0",
        "bootstrap": "^3.0 || ^4.0"
    },
    "dependencies": {
        "react-select": "^1.0.0-rc.1",
        "redux-actions": "^0.11.0",
        "reselect": "^2.5.3"
    },
    "devDependencies": {
        "@kadira/storybook": "^2.21.0",
        "babel-cli": "^6.14.0",
        "babel-eslint": "^6.0.2",
        "babel-plugin-transform-object-rest-spread": "^6.6.5",
        "babel-preset-es2015": "^6.6.0",
        "babel-preset-react": "^6.5.0",
        "bootstrap": "4.0.0-alpha.6",
        "bootstrap-css": "^3.0.0",
        "eslint": "^3.3.1",
        "eslint-config-airbnb": "^10.0.1",
        "eslint-loader": "^1.3.0",
        "eslint-plugin-import": "^1.13.0",
        "eslint-plugin-jsx-a11y": "^2.1.0",
        "eslint-plugin-react": "^6.0.0",
        "lodash": "^4.15.0",
        "react": "^15.1.0",
        "react-dom": "^15.3.2",
        "redux": "^3.4.0",
        "font-awesome": "^4.7.0",
        "react-redux": "^4.4.5"
    },
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
