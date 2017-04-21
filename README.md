# npmtest-xterm

#### basic test coverage for  [xterm (v2.5.0)](https://github.com/sourcelair/xterm.js#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-xterm.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-xterm) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-xterm.svg)](https://travis-ci.org/npmtest/node-npmtest-xterm)

#### Full xterm terminal, in your browser

[![NPM](https://nodei.co/npm/xterm.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/xterm)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-xterm/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-xterm/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-xterm/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-xterm/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-xterm/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-xterm/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-xterm/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-xterm/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-xterm/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-xterm/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-xterm/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-xterm/build/test-report.html](https://npmtest.github.io/node-npmtest-xterm/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-xterm/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-xterm/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-xterm/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-xterm/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-xterm/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-xterm/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-xterm/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-xterm/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "bugs": {
        "url": "https://github.com/sourcelair/xterm.js/issues"
    },
    "contributors": [
        {
            "name": "List of xterm.js contributors. Updated before every release."
        },
        {
            "name": "Aleksandr Andrienko"
        },
        {
            "name": "Alessandro Nadalin"
        },
        {
            "name": "Alexander Olsson"
        },
        {
            "name": "Antonis Kalipetis"
        },
        {
            "name": "Anton Skshidlevsky"
        },
        {
            "name": "Anton Yurovskykh"
        },
        {
            "name": "Austin Robertson"
        },
        {
            "name": "ayapi"
        },
        {
            "name": "Ben Hall"
        },
        {
            "name": "Benjamin Fischer"
        },
        {
            "name": "Bill Church"
        },
        {
            "name": "Bob Reid"
        },
        {
            "name": "bottleofwater"
        },
        {
            "name": "Brian Mock"
        },
        {
            "name": "Carson Anderson"
        },
        {
            "name": "Christian Budde Christensen"
        },
        {
            "name": "Christopher Jeffrey"
        },
        {
            "name": "coderaiser"
        },
        {
            "name": "Daniel Imms"
        },
        {
            "name": "Daniel Risacher"
        },
        {
            "name": "Dan Kaplun"
        },
        {
            "name": "Darin Morrison"
        },
        {
            "name": "Edgar Andrés Margffoy Tuay"
        },
        {
            "name": "Elliot Saba"
        },
        {
            "name": "hiro-su"
        },
        {
            "name": "Ian Lewis"
        },
        {
            "name": "imoses"
        },
        {
            "name": "InDieTasten"
        },
        {
            "name": "Jean Bruenn"
        },
        {
            "name": "Jörg Breitbart"
        },
        {
            "name": "Lucian Buzzo"
        },
        {
            "name": "Maël Nison"
        },
        {
            "name": "Martin Wang"
        },
        {
            "name": "Michael Irwin"
        },
        {
            "name": "Mikko Karvonen"
        },
        {
            "name": "Nicolas Ramz"
        },
        {
            "name": "Paris Kasidiaris"
        },
        {
            "name": "Paris Kasidiaris"
        },
        {
            "name": "runarberg"
        },
        {
            "name": "Saswat Das"
        },
        {
            "name": "Shuanglei Tao"
        },
        {
            "name": "Steven Silvester"
        },
        {
            "name": "Thanasis Daglis"
        },
        {
            "name": "Tine Jozelj"
        },
        {
            "name": "Tyler Jewell"
        },
        {
            "name": "Vincent Woo"
        },
        {
            "name": "yutaka"
        },
        {
            "name": "YuviPanda"
        }
    ],
    "dependencies": {},
    "description": "Full xterm terminal, in your browser",
    "devDependencies": {
        "@types/chai": "^3.4.34",
        "@types/jsdom": "^2.0.30",
        "@types/mocha": "^2.2.33",
        "@types/node": "^6.0.41",
        "browserify": "^13.1.0",
        "chai": "3.5.0",
        "docdash": "0.4.0",
        "express": "4.13.4",
        "express-ws": "2.0.0-rc.1",
        "fs-extra": "^1.0.0",
        "glob": "^7.0.5",
        "gulp": "^3.9.1",
        "gulp-cli": "^1.2.2",
        "gulp-coveralls": "^0.1.4",
        "gulp-istanbul": "^1.1.1",
        "gulp-mocha": "^3.0.1",
        "gulp-sourcemaps": "1.9.1",
        "gulp-typescript": "^3.1.3",
        "jsdoc": "3.4.3",
        "jsdom": "^9.11.0",
        "merge-stream": "^1.0.1",
        "node-pty": "^0.4.1",
        "nodemon": "1.10.2",
        "sleep": "^3.0.1",
        "sorcery": "^0.10.0",
        "tslint": "^4.0.2",
        "typescript": "~2.2.0",
        "vinyl-buffer": "^1.0.0",
        "vinyl-source-stream": "^1.1.0"
    },
    "directories": {},
    "dist": {
        "shasum": "5a6239ba08a40640127e80b3d8180df34a06b499",
        "tarball": "https://registry.npmjs.org/xterm/-/xterm-2.5.0.tgz"
    },
    "files": [
        "*.js",
        "*.json",
        "dist/*.css",
        "dist/**/*.css",
        "dist/*.js",
        "dist/*.js.map",
        "dist/**/*.js",
        "dist/**/*.js.map",
        "lib/*.css",
        "lib/**/*.css",
        "lib/*.js",
        "lib/*.js.map",
        "lib/**/*.js",
        "lib/**/*.js.map",
        "src/*.css",
        "src/**/*.css",
        "src/*.js",
        "src/*.js.map",
        "src/*.ts",
        "src/**/*.js",
        "src/**/*.js.map",
        "src/**/*.ts"
    ],
    "gitHead": "d2f8f9dc1ade223b9c486e99d9c3b499465fe4d1",
    "homepage": "https://github.com/sourcelair/xterm.js#readme",
    "ignore": [
        "demo",
        "test",
        ".gitignore"
    ],
    "license": "MIT",
    "main": "lib/xterm.js",
    "maintainers": [
        {
            "name": "paris"
        }
    ],
    "name": "xterm",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/sourcelair/xterm.js.git"
    },
    "scripts": {
        "build": "gulp build",
        "build:docs": "jsdoc -c jsdoc.json",
        "coveralls": "gulp coveralls",
        "dev": "nodemon -e js,ts,css --watch src --watch demo --exec npm start",
        "lint": "tslint src/*.ts src/**/*.ts",
        "prepublish": "npm run build",
        "prestart": "npm run build",
        "start": "node demo/app",
        "test": "gulp test"
    },
    "version": "2.5.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
