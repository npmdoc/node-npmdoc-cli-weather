# npmdoc-cli-weather

#### api documentation for  [cli-weather (v2.0.7)](https://github.com/apizzimenti/cli-weather#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-cli-weather.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-cli-weather) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-cli-weather.svg)](https://travis-ci.org/npmdoc/node-npmdoc-cli-weather)

#### Puts the weather in your console.

[![NPM](https://nodei.co/npm/cli-weather.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/cli-weather)

- [https://npmdoc.github.io/node-npmdoc-cli-weather/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-cli-weather/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-cli-weather/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-cli-weather/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-cli-weather/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-cli-weather/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Anthony Pizzimenti"
    },
    "bin": {
        "weather": "./lib/index.js"
    },
    "bugs": {
        "url": "https://github.com/apizzimenti/cli-weather/issues"
    },
    "dependencies": {
        "chalk": "^1.1.3",
        "cli-table2": "^0.2.0",
        "geocoder": "^0.2.2",
        "minimist": "^1.2.0",
        "open": "^0.0.5",
        "request": "^2.79.0",
        "wordwrap": "^1.0.0"
    },
    "description": "Puts the weather in your console.",
    "devDependencies": {
        "jsdoc": "^3.4.3",
        "minami": "^1.1.1",
        "mocha": "^3.2.0"
    },
    "directories": {},
    "dist": {
        "shasum": "a60e7e8aeae7ccad166f88f91048b320f0717f72",
        "tarball": "https://registry.npmjs.org/cli-weather/-/cli-weather-2.0.7.tgz"
    },
    "gitHead": "5aeaf79eb10e657a3d286da8f4f9e445df2279d9",
    "homepage": "https://github.com/apizzimenti/cli-weather#readme",
    "keywords": [
        "weather",
        "cli",
        "command",
        "line",
        "tool",
        "package",
        "node",
        "location"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "apizzimenti"
        }
    ],
    "name": "cli-weather",
    "optionalDependencies": {},
    "preferGlobal": true,
    "repository": {
        "type": "git",
        "url": "git+https://github.com/apizzimenti/cli-weather.git"
    },
    "scripts": {
        "build": "echo 'cleaning folders and generating docs'",
        "postbuild": "jsdoc -c ~/desktop/cli-weather/jsdoc.json",
        "prebuild": "rimraf dist/**/* ../cli-weather-docs/**/*",
        "test": "eslint lib/**"
    },
    "version": "2.0.7"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
