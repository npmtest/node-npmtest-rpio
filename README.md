# npmtest-rpio

#### test coverage for  [rpio (v0.9.16)](https://github.com/jperkin/node-rpio#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-rpio.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-rpio) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-rpio.svg)](https://travis-ci.org/npmtest/node-npmtest-rpio)

#### High performance GPIO/i2c/PWM/SPI module for Raspberry Pi

[![NPM](https://nodei.co/npm/rpio.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/rpio)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-rpio/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-rpio/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-rpio/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-rpio/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-rpio/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-rpio/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-rpio/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-rpio/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-rpio/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-rpio/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-rpio/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-rpio/build/test-report.html](https://npmtest.github.io/node-npmtest-rpio/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-rpio/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-rpio/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-rpio/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-rpio/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-rpio/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-rpio/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-rpio/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-rpio/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Jonathan Perkin",
        "url": "http://www.perkin.org.uk/"
    },
    "bugs": {
        "url": "https://github.com/jperkin/node-rpio/issues"
    },
    "dependencies": {
        "bindings": "*",
        "nan": "*"
    },
    "description": "High performance GPIO/i2c/PWM/SPI module for Raspberry Pi",
    "devDependencies": {},
    "directories": {},
    "dist": {
        "shasum": "dc4750db099c7e0e6e6505aa86297f4a23aaf5d6",
        "tarball": "https://registry.npmjs.org/rpio/-/rpio-0.9.16.tgz"
    },
    "engines": {
        "node": ">=0.8"
    },
    "gitHead": "53466f00813e51925d9f1cfaaf29f56168aeeca1",
    "gypfile": true,
    "homepage": "https://github.com/jperkin/node-rpio#readme",
    "keywords": [
        "bcm2835",
        "gpio",
        "gpiomem",
        "i2c",
        "mmap",
        "pi",
        "pwm",
        "raspberry",
        "raspberrypi",
        "raspberry pi",
        "rpi",
        "spi"
    ],
    "license": "(ISC AND GPL-2.0)",
    "main": "./lib/rpio.js",
    "maintainers": [
        {
            "name": "jperkin"
        }
    ],
    "name": "rpio",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/jperkin/node-rpio.git"
    },
    "scripts": {
        "install": "node-gyp rebuild",
        "test": "true"
    },
    "version": "0.9.16"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
