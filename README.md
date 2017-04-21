# npmdoc-hbase-client

#### api documentation for  [hbase-client (v1.4.0)](http://github.com/alibaba/node-hbase-client)  [![npm package](https://img.shields.io/npm/v/npmdoc-hbase-client.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-hbase-client) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-hbase-client.svg)](https://travis-ci.org/npmdoc/node-npmdoc-hbase-client)

#### Asynchronous HBase client for Node.js, pure javascript implementation.

[![NPM](https://nodei.co/npm/hbase-client.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/hbase-client)

- [https://npmdoc.github.io/node-npmdoc-hbase-client/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-hbase-client/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-hbase-client/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-hbase-client/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-hbase-client/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-hbase-client/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "hbase-client",
    "version": "1.4.0",
    "description": "Asynchronous HBase client for Node.js, pure javascript implementation.",
    "main": "index.js",
    "files": [
        "index.js",
        "lib/"
    ],
    "scripts": {
        "test": "make test-all"
    },
    "config": {
        "blanket": {
            "pattern": "//^((?!(node_modules|test)).)*$/"
        },
        "travis-cov": {
            "threshold": 85
        }
    },
    "dependencies": {
        "debug": "~1.0.4",
        "eventproxy": "~0.3.1",
        "long": "~1.1.5",
        "readable-stream": "1.1.11",
        "utility": "~0.1.16",
        "zookeeper-watcher": "~0.2.0"
    },
    "devDependencies": {
        "autod": "*",
        "benchmark": "*",
        "blanket": "*",
        "contributors": "*",
        "interceptor": "0.1.4",
        "jshint": "*",
        "mm": "~0.2.1",
        "mocha": "*",
        "moment": "*",
        "pedding": "~1.0.0",
        "should": "3",
        "istanbul": "~0.3.2"
    },
    "homepage": "http://github.com/alibaba/node-hbase-client",
    "repository": {
        "type": "git",
        "url": "git://github.com/alibaba/node-hbase-client.git"
    },
    "keywords": [
        "node-hbase-client",
        "hbase",
        "hbase-client"
    ],
    "author": "fengmk2 <fengmk2@gmail.com> (http://fengmk2.github.com)",
    "license": "MIT"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
