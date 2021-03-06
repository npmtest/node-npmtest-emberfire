# npmtest-emberfire

#### basic test coverage for  [emberfire (v2.0.6)](https://github.com/firebase/emberfire/)  [![npm package](https://img.shields.io/npm/v/npmtest-emberfire.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-emberfire) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-emberfire.svg)](https://travis-ci.org/npmtest/node-npmtest-emberfire)

#### The officially supported Ember binding for Firebase

[![NPM](https://nodei.co/npm/emberfire.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/emberfire)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-emberfire/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-emberfire/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-emberfire/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-emberfire/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-emberfire/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-emberfire/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-emberfire/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-emberfire/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-emberfire/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-emberfire/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-emberfire/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-emberfire/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-emberfire/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-emberfire/build/test-report.html](https://npmtest.github.io/node-npmtest-emberfire/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-emberfire/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-emberfire/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-emberfire/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-emberfire/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-emberfire/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-emberfire/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-emberfire/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-emberfire/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Firebase",
        "url": "https://firebase.google.com/"
    },
    "browserify": {
        "transform": [
            "babelify",
            "browserify-shim"
        ]
    },
    "browserify-shim": {
        "ember": "global:Ember",
        "ember-data": "global:DS",
        "firebase": "global:firebase"
    },
    "bugs": {
        "url": "https://github.com/firebase/emberfire/issues"
    },
    "dependencies": {
        "broccoli-merge-trees": "^1.2.1",
        "broccoli-webpack": "^1.0.0",
        "chalk": "1.1.3",
        "ember-cli-babel": "5.1.6",
        "ember-lodash": "0.0.7",
        "firebase": "^3.4.1"
    },
    "description": "The officially supported Ember binding for Firebase",
    "devDependencies": {
        "babelify": "6.4.0",
        "broccoli-asset-rev": "^2.4.2",
        "browserify": "10.2.6",
        "browserify-shim": "3.8.12",
        "codeclimate-test-reporter": "^0.3.3",
        "del": "1.2.0",
        "ember-ajax": "0.7.1",
        "ember-cli": "2.5.1",
        "ember-cli-app-version": "^1.0.0",
        "ember-cli-code-coverage": "^0.3.2",
        "ember-cli-dependency-checker": "^1.2.0",
        "ember-cli-htmlbars": "^1.0.3",
        "ember-cli-htmlbars-inline-precompile": "^0.3.1",
        "ember-cli-inject-live-reload": "^1.4.0",
        "ember-cli-jshint": "^1.0.0",
        "ember-cli-mocha": "^0.12.0",
        "ember-cli-release": "0.2.8",
        "ember-cli-sri": "^2.1.0",
        "ember-cli-uglify": "^1.2.0",
        "ember-data": "^2.5.0",
        "ember-disable-prototype-extensions": "^1.1.0",
        "ember-export-application-global": "^1.0.5",
        "ember-load-initializers": "^0.5.1",
        "ember-resolver": "^2.0.3",
        "ember-sinon": "0.5.1",
        "ember-try": "^0.2.2",
        "glob": "5.0.13",
        "gulp": "3.9.1",
        "gulp-concat": "2.6.0",
        "gulp-header": "1.8.2",
        "gulp-jshint": "1.11.2",
        "gulp-load-plugins": "0.10.0",
        "gulp-rename": "1.2.2",
        "gulp-sourcemaps": "1.6.0",
        "gulp-uglify": "1.5.3",
        "gulp-util": "3.0.7",
        "loader.js": "^4.0.1",
        "lodash": "3.10.1",
        "sinon": "^1.17.3",
        "torii": "0.8.0",
        "vinyl-buffer": "1.0.0",
        "vinyl-source-stream": "1.1.0"
    },
    "directories": {
        "doc": "doc",
        "test": "tests"
    },
    "dist": {
        "shasum": "53ccd86eeb7e2d3102d64fbcf86c74b2a9d3a62c",
        "tarball": "https://registry.npmjs.org/emberfire/-/emberfire-2.0.6.tgz"
    },
    "ember-addon": {
        "configPath": "tests/dummy/config",
        "fastbootDependencies": [
            "firebase"
        ]
    },
    "gitHead": "8937d7e530a2b9e8b85a38c8f4a37ac225ef2f57",
    "homepage": "https://github.com/firebase/emberfire/",
    "keywords": [
        "ember",
        "firebase",
        "realtime",
        "ember-addon"
    ],
    "license": "MIT",
    "maintainers": [
        {
            "name": "firebase"
        }
    ],
    "name": "emberfire",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/firebase/emberfire.git"
    },
    "scripts": {
        "build": "ember build",
        "legacy": "gulp legacy",
        "start": "ember server",
        "test": "ember try:testall"
    },
    "version": "2.0.6",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
