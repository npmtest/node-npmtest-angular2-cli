# npmtest-angular2-cli

#### basic test coverage for  [angular2-cli (v0.4.2)](https://github.com/madhusudhand/angular2-cli#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-angular2-cli.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-angular2-cli) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-angular2-cli.svg)](https://travis-ci.org/npmtest/node-npmtest-angular2-cli)

#### Command Line Interface for developing Angular 2 apps

[![NPM](https://nodei.co/npm/angular2-cli.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/angular2-cli)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-angular2-cli/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-angular2-cli/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-angular2-cli/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-angular2-cli/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-angular2-cli/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-angular2-cli/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-angular2-cli/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-angular2-cli/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-angular2-cli/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-angular2-cli/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-angular2-cli/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-angular2-cli/build/test-report.html](https://npmtest.github.io/node-npmtest-angular2-cli/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-angular2-cli/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-angular2-cli/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-angular2-cli/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-angular2-cli/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-angular2-cli/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-angular2-cli/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-angular2-cli/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-angular2-cli/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Madhusudhan Dollu"
    },
    "bin": {
        "ng2": "./bin/ng2"
    },
    "bugs": {
        "url": "https://github.com/madhusudhand/angular2-cli/issues"
    },
    "dependencies": {
        "awesome-typescript-loader": "^2.2.4",
        "bluebird": "^3.4.0",
        "browser-sync": "^2.12.10",
        "child-process-promise": "^2.0.2",
        "chokidar": "^1.5.1",
        "cli-spinners": "^0.1.2",
        "colors": "^1.1.2",
        "commander": "^2.9.0",
        "connect-history-api-fallback": "^1.2.0",
        "export-files": "^2.1.1",
        "fs-extra": "^0.26.7",
        "gulp": "^3.9.1",
        "gulp-cssmin": "^0.1.7",
        "gulp-less": "^3.1.0",
        "gulp-pug": "^3.0.2",
        "gulp-sass": "^2.3.1",
        "loader-utils": "^0.2.16",
        "lodash": "^4.13.1",
        "log-update": "^1.0.2",
        "ncp": "^2.0.0",
        "node-sass": "^3.10.0",
        "pug": "^2.0.0-beta6",
        "systemjs-builder": "^0.15.18",
        "typescript": "^2.0.3",
        "typings-core": "^1.0.1",
        "webpack": "^2.1.0-beta.22"
    },
    "description": "Command Line Interface for developing Angular 2 apps",
    "devDependencies": {
        "eslint": "^2.8.0",
        "eslint-config-airbnb": "^9.0.1",
        "eslint-plugin-import": "^1.8.0",
        "eslint-plugin-jsx-a11y": "^1.0.2",
        "eslint-plugin-react": "^5.0.1"
    },
    "directories": {},
    "dist": {
        "shasum": "44992172e8324508bec4186f03504d72d234b413",
        "tarball": "https://registry.npmjs.org/angular2-cli/-/angular2-cli-0.4.2.tgz"
    },
    "engines": {
        "node": ">= 4.1.0"
    },
    "gitHead": "a0a8421632b746e3e35d0f47176e7502d60f3a75",
    "homepage": "https://github.com/madhusudhand/angular2-cli#readme",
    "keywords": [
        "angular2",
        "cli",
        "ng2"
    ],
    "license": "MIT",
    "main": "./lib/cli/index.js",
    "maintainers": [
        {
            "name": "madhusudhand"
        }
    ],
    "name": "angular2-cli",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/madhusudhand/angular2-cli.git"
    },
    "scripts": {
        "lint": "eslint lib",
        "test": "eslint lib"
    },
    "version": "0.4.2"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
