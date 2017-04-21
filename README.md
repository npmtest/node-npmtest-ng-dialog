# npmtest-ng-dialog

#### basic test coverage for  [ng-dialog (v1.0.1)](https://github.com/likeastore/ngDialog)  [![npm package](https://img.shields.io/npm/v/npmtest-ng-dialog.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-ng-dialog) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-ng-dialog.svg)](https://travis-ci.org/npmtest/node-npmtest-ng-dialog)

#### Modal dialogs and popups provider for Angular.js applications

[![NPM](https://nodei.co/npm/ng-dialog.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/ng-dialog)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-ng-dialog/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-ng-dialog/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-ng-dialog/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-ng-dialog/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-ng-dialog/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-ng-dialog/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-ng-dialog/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-ng-dialog/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-ng-dialog/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-ng-dialog/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-ng-dialog/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-ng-dialog/build/test-report.html](https://npmtest.github.io/node-npmtest-ng-dialog/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-ng-dialog/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-ng-dialog/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-ng-dialog/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-ng-dialog/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-ng-dialog/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-ng-dialog/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-ng-dialog/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-ng-dialog/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "ng-dialog",
    "version": "1.0.1",
    "homepage": "https://github.com/likeastore/ngDialog",
    "description": "Modal dialogs and popups provider for Angular.js applications",
    "main": "./js/ngDialog.js",
    "style": "./css/ngDialog.css",
    "scripts": {
        "pretest": "npm install && bower install --allow-root",
        "test": "./node_modules/karma/bin/karma start --single-run --browsers PhantomJS",
        "test-min": "./node_modules/karma/bin/karma start --single-run --browsers PhantomJS --min",
        "test-watch": "./node_modules/karma/bin/karma start --auto-watch --browsers PhantomJS",
        "serve": "node server",
        "webdriver-update": "node_modules/.bin/webdriver-manager update --standalone",
        "webdriver": "node_modules/.bin/webdriver-manager start",
        "preprotractor": "npm install && bower install --allow-root",
        "protractor": "node_modules/.bin/protractor protractor.conf.js",
        "protractor-a11y": "node_modules/.bin/protractor protractor.conf.js --a11y",
        "protractor-console": "node_modules/.bin/protractor protractor.conf.js --console-error",
        "build": "grunt build"
    },
    "directories": {
        "test": "tests"
    },
    "keywords": [
        "angular.js",
        "modals",
        "popups",
        "dialog",
        "ng",
        "provider",
        "factory",
        "directive"
    ],
    "author": {
        "name": "Dmitri Voronianski",
        "web": "http://pixelhunter.me",
        "twitter": "voronianski"
    },
    "bugs": "https://github.com/likeastore/ngDialog/issues",
    "repository": {
        "type": "git",
        "url": "https://github.com/likeastore/ngDialog"
    },
    "readmeFilename": "README.md",
    "license": "MIT",
    "devDependencies": {
        "express": "^4.13.3",
        "grunt": "^0.4.5",
        "grunt-cli": "^0.1.13",
        "grunt-contrib-cssmin": "^0.14.0",
        "grunt-contrib-jshint": "^0.11.3",
        "grunt-contrib-uglify": "^0.9.2",
        "grunt-myth": "^1.0.1",
        "jasmine-core": "^2.3.4",
        "karma": "^1.3.0",
        "karma-coverage": "^1.1.1",
        "karma-jasmine": "^1.1.0",
        "karma-phantomjs-launcher": "^1.0.2",
        "myth": "^1.5.0",
        "phantomjs": "^2.1.7",
        "protractor": "^2.2.0"
    },
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
