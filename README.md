# npmtest-pigpio

#### basic test coverage for  pigpio (v0.5.1)  [![npm package](https://img.shields.io/npm/v/npmtest-pigpio.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-pigpio) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-pigpio.svg)](https://travis-ci.org/npmtest/node-npmtest-pigpio)

#### Fast GPIO, PWM, servo control, state change notification, and interrupt handling on the Raspberry Pi

[![NPM](https://nodei.co/npm/pigpio.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/pigpio)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-pigpio/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-pigpio/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-pigpio/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-pigpio/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-pigpio/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-pigpio/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-pigpio/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-pigpio/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-pigpio/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-pigpio/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-pigpio/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-pigpio/build/test-report.html](https://npmtest.github.io/node-npmtest-pigpio/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-pigpio/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-pigpio/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-pigpio/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-pigpio/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-pigpio/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-pigpio/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-pigpio/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-pigpio/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "pigpio",
    "version": "0.5.1",
    "description": "Fast GPIO, PWM, servo control, state change notification, and interrupt handling on the Raspberry Pi",
    "main": "pigpio.js",
    "directories": {
        "example": "example",
        "test": "test"
    },
    "scripts": {
        "test": "echo \"Tests can only be run manually from the command line.\" && exit 1",
        "install": "node-gyp rebuild"
    },
    "repository": {
        "type": "git",
        "url": "https://github.com/fivdi/pigpio.git"
    },
    "engines": {
        "node": ">=0.10.0"
    },
    "dependencies": {
        "bindings": "~1.2.1",
        "nan": "~2.6.2"
    },
    "keywords": [
        "gpio",
        "pwm",
        "servo",
        "interrupt",
        "raspberry",
        "pi"
    ],
    "author": "fivdi",
    "license": "MIT",
    "gypfile": true,
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
