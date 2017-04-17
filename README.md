# api documentation for  [steed (v1.1.3)](https://github.com/mcollina/steed#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-steed.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-steed) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-steed.svg)](https://travis-ci.org/npmdoc/node-npmdoc-steed)
#### horsepower for your modules

[![NPM](https://nodei.co/npm/steed.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/steed)

- [https://npmdoc.github.io/node-npmdoc-steed/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-steed/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-steed/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-steed/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-steed/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-steed/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Matteo Collina"
    },
    "bugs": {
        "url": "https://github.com/mcollina/steed/issues"
    },
    "dependencies": {
        "fastfall": "^1.5.0",
        "fastparallel": "^2.2.0",
        "fastq": "^1.3.0",
        "fastseries": "^1.7.0",
        "reusify": "^1.0.0"
    },
    "description": "horsepower for your modules",
    "devDependencies": {
        "coveralls": "^2.11.6",
        "fastbench": "^1.0.0",
        "istanbul": "^0.4.1",
        "neo-async": "^1.7.0",
        "standard": "^5.4.1",
        "tap-spec": "^4.1.0",
        "tape": "^4.2.2"
    },
    "directories": {},
    "dist": {
        "shasum": "f1525dd5adb12eb21bf74749537668d625b9abc5",
        "tarball": "https://registry.npmjs.org/steed/-/steed-1.1.3.tgz"
    },
    "gitHead": "1bf30bbb18f5d7dae683009a01b40dbbb6636a6e",
    "homepage": "https://github.com/mcollina/steed#readme",
    "keywords": [
        "control",
        "flow",
        "async",
        "series",
        "parallel"
    ],
    "license": "MIT",
    "main": "steed.js",
    "maintainers": [
        {
            "name": "matteo.collina"
        }
    ],
    "name": "steed",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/mcollina/steed.git"
    },
    "scripts": {
        "coverage": "istanbul cover tape test.js; cat coverage/lcov.info | coveralls",
        "test": "standard && tape test.js | tap-spec"
    },
    "version": "1.1.3"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
