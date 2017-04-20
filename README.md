# npmdoc-node-webcl

#### api documentation for  node-webcl (v0.9.2)  [![npm package](https://img.shields.io/npm/v/npmdoc-node-webcl.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-node-webcl) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-node-webcl.svg)](https://travis-ci.org/npmdoc/node-npmdoc-node-webcl)

#### A WebCL implementation for desktops with NodeJS

[![NPM](https://nodei.co/npm/node-webcl.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/node-webcl)

- [https://npmdoc.github.io/node-npmdoc-node-webcl/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-node-webcl/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-node-webcl/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-node-webcl/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-node-webcl/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-node-webcl/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "node-webcl",
    "version": "0.9.2",
    "description": "A WebCL implementation for desktops with NodeJS",
    "main": "webcl.js",
    "author": "Mikael Bourges-Sevenier <mikeseven@gmail.com>",
    "keywords": [
        "webcl",
        "opencl"
    ],
    "maintainers": [
        {
            "name": "Mikael Bourges-Sevenier"
        }
    ],
    "licenses": [
        {
            "type": "BSD",
            "url": "https://github.com/mikeseven/node-webcl/blob/master/LICENSES"
        }
    ],
    "repository": {
        "type": "git",
        "url": "https://github.com/mikeseven/node-webcl"
    },
    "directories": {
        "src": "src",
        "lib": "lib",
        "docs": "docs",
        "examples": "examples",
        "test": "test"
    },
    "scripts": {
        "install": "node-gyp rebuild --msvs_version=2013"
    },
    "dependencies": {
        "node-webgl": ">=0.4.2",
        "node-image": ">=0.7.1",
        "nan": "~1.2.0"
    },
    "devDependencies": {
        "chai": "*",
        "mocha": "*"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
