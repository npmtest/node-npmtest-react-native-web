# npmtest-react-native-web

#### test coverage for  [react-native-web (v0.0.81)](https://github.com/necolas/react-native-web#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-react-native-web.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-react-native-web) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-react-native-web.svg)](https://travis-ci.org/npmtest/node-npmtest-react-native-web)

#### React Native for Web

[![NPM](https://nodei.co/npm/react-native-web.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/react-native-web)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-react-native-web/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-react-native-web/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-react-native-web/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-react-native-web/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-react-native-web/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-react-native-web/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-react-native-web/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-react-native-web/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-react-native-web/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-react-native-web/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-react-native-web/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-react-native-web/build/test-report.html](https://npmtest.github.io/node-npmtest-react-native-web/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-react-native-web/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-react-native-web/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-react-native-web/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-react-native-web/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-react-native-web/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-react-native-web/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-react-native-web/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-react-native-web/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Nicolas Gallagher"
    },
    "bugs": {
        "url": "https://github.com/necolas/react-native-web/issues"
    },
    "dependencies": {
        "animated": "^0.2.0",
        "array-find-index": "^1.0.2",
        "babel-runtime": "^6.23.0",
        "debounce": "^1.0.0",
        "deep-assign": "^2.0.0",
        "fbjs": "^0.8.8",
        "hyphenate-style-name": "^1.0.2",
        "inline-style-prefixer": "^3.0.0",
        "normalize-css-color": "^1.0.2",
        "react-dom": "~15.4.1",
        "react-textarea-autosize": "^4.0.4",
        "react-timer-mixin": "^0.13.3"
    },
    "description": "React Native for Web",
    "devDependencies": {
        "@kadira/storybook": "^2.5.1",
        "babel-cli": "^6.23.0",
        "babel-core": "^6.23.1",
        "babel-eslint": "^7.1.1",
        "babel-loader": "^6.3.2",
        "babel-plugin-transform-react-remove-prop-types": "^0.3.2",
        "babel-preset-react-native": "^1.9.1",
        "del-cli": "^0.2.1",
        "enzyme": "^2.4.1",
        "eslint": "^3.4.0",
        "eslint-config-prettier": "^1.4.0",
        "eslint-plugin-jsx-a11y": "^2.2.0",
        "eslint-plugin-promise": "^2.0.1",
        "eslint-plugin-react": "^6.1.2",
        "file-loader": "^0.9.0",
        "jest": "^19.0.2",
        "node-libs-browser": "^0.5.3",
        "prettier": "^0.19.0",
        "react": "~15.4.1",
        "react-addons-test-utils": "~15.4.1",
        "react-test-renderer": "~15.4.1",
        "url-loader": "^0.5.7",
        "webpack": "^1.13.2",
        "webpack-bundle-analyzer": "^2.2.1"
    },
    "directories": {},
    "dist": {
        "shasum": "158de0ba9997a95d9c3f18a0916f1abe84d88ddb",
        "tarball": "https://registry.npmjs.org/react-native-web/-/react-native-web-0.0.81.tgz"
    },
    "files": [
        "dist",
        "src",
        "!**/__tests__"
    ],
    "gitHead": "25a11e673dbb424f8c14cfddf17cb6d8ce914a64",
    "homepage": "https://github.com/necolas/react-native-web#readme",
    "jest": {
        "testEnvironment": "jsdom",
        "timers": "fake"
    },
    "keywords": [
        "react",
        "react-component",
        "react-native",
        "web"
    ],
    "license": "BSD-3-Clause",
    "main": "dist/index.js",
    "maintainers": [
        {
            "name": "necolas"
        }
    ],
    "name": "react-native-web",
    "optionalDependencies": {},
    "peerDependencies": {
        "react": "~15.4.1"
    },
    "repository": {
        "type": "git",
        "url": "git://github.com/necolas/react-native-web.git"
    },
    "scripts": {
        "build": "del ./dist && mkdir dist && babel src -d dist --ignore **/__tests__",
        "build:examples": "build-storybook -o dist-examples -c ./examples/.storybook",
        "build:performance": "cd performance && yarn && webpack",
        "build:umd": "webpack --config webpack.config.js --sort-assets-by --progress",
        "deploy:examples": "git checkout gh-pages && rm -rf ./storybook && mv dist-examples storybook && git add -A && git commit -m \"Storybook deploy\" && git push origin gh-pages && git checkout -",
        "examples": "start-storybook -p 9001 -c ./examples/.storybook --dont-track",
        "fmt": "find performance src -name '*.js' | grep -v -E '(node_modules|dist)' | xargs prettier --print-width=100 --single-quote --write",
        "lint": "eslint performance src --ignore-path .gitignore",
        "prepublish": "npm run build && npm run build:umd",
        "test": "npm run lint && npm run test:jest",
        "test:jest": "jest",
        "test:watch": "npm run test:jest -- --watch"
    },
    "tags": [
        "react"
    ],
    "version": "0.0.81"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
