# npmdoc-ttystudio

#### api documentation for  [ttystudio (v0.0.16)](https://github.com/chjj/ttystudio)  [![npm package](https://img.shields.io/npm/v/npmdoc-ttystudio.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-ttystudio) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-ttystudio.svg)](https://travis-ci.org/npmdoc/node-npmdoc-ttystudio)

#### A terminal-to-gif recorder minus the headaches.

[![NPM](https://nodei.co/npm/ttystudio.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/ttystudio)

- [https://npmdoc.github.io/node-npmdoc-ttystudio/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-ttystudio/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-ttystudio/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-ttystudio/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-ttystudio/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-ttystudio/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "ttystudio",
    "description": "A terminal-to-gif recorder minus the headaches.",
    "author": "Christopher Jeffrey",
    "version": "0.0.16",
    "license": "MIT",
    "main": "./index.js",
    "bin": {
        "ttystudio": "./bin/ttystudio"
    },
    "scripts": {
        "start": "./bin/ttystudio ~/ttystudio-test.gif"
    },
    "man": "./man/ttystudio.1",
    "preferGlobal": true,
    "repository": "git://github.com/chjj/ttystudio.git",
    "homepage": "https://github.com/chjj/ttystudio",
    "bugs": {
        "url": "http://github.com/chjj/ttystudio/issues"
    },
    "keywords": [
        "terminal",
        "tty",
        "record",
        "recorder",
        "gif",
        "png",
        "apng"
    ],
    "tags": [
        "terminal",
        "tty",
        "record",
        "recorder",
        "gif",
        "png",
        "apng"
    ],
    "dependencies": {
        "blessed": ">=0.1.80",
        "term.js": ">=0.0.7",
        "pty.js": ">=0.3.0"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
