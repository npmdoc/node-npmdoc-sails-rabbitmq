# npmdoc-sails-rabbitmq

#### api documentation for  sails-rabbitmq (v0.12.3)  [![npm package](https://img.shields.io/npm/v/npmdoc-sails-rabbitmq.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-sails-rabbitmq) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-sails-rabbitmq.svg)](https://travis-ci.org/npmdoc/node-npmdoc-sails-rabbitmq)

#### sails-rabbitmq adapter for Sails / Waterline

[![NPM](https://nodei.co/npm/sails-rabbitmq.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/sails-rabbitmq)

- [https://npmdoc.github.io/node-npmdoc-sails-rabbitmq/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-sails-rabbitmq/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-sails-rabbitmq/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-sails-rabbitmq/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-sails-rabbitmq/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-sails-rabbitmq/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "sails-rabbitmq",
    "version": "0.12.3",
    "description": "sails-rabbitmq adapter for Sails / Waterline",
    "main": "dist/adapter.js",
    "scripts": {
        "prepublish": "gulp build",
        "test": "mocha --recursive --reporter spec --compilers js:babel/register --timeout 500"
    },
    "repository": {
        "type": "git",
        "url": "git://github.com/tjwebb/sails-rabbitmq.git"
    },
    "keywords": [
        "sails-rabbitmq",
        "rabbit",
        "rabbitmq",
        "amqp",
        "adapter",
        "sails",
        "waterline",
        "sails.js",
        "plugin"
    ],
    "author": "Travis Webb <me@traviswebb.com>",
    "license": "MIT",
    "readmeFilename": "README.md",
    "dependencies": {
        "lodash": "^3.9.3",
        "rabbit.js": "^0.4.4",
        "babel": "^5.6",
        "gulp": "^3.9",
        "gulp-babel": "^5.1.0",
        "waterline": "^0.10.23"
    },
    "devDependencies": {
        "captains-log": "^0.11.0",
        "mocha": "^2.2.5",
        "sails-disk": "^0.10.8",
        "sails-memory": "^0.10.4"
    },
    "waterlineAdapter": {
        "type": "sails-rabbitmq",
        "interfaces": [
            "pubsub"
        ],
        "waterlineVersion": "^0.10"
    },
    "eslintConfig": {
        "node": true,
        "es6": true
    },
    "engines": {
        "node": ">= 0.12.0"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
