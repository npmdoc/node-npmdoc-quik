# npmdoc-quik

#### api documentation for  quik (v0.11.2)  [![npm package](https://img.shields.io/npm/v/npmdoc-quik.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-quik) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-quik.svg)](https://travis-ci.org/npmdoc/node-npmdoc-quik)

#### A quick way to prototype apps with React and Babel with zero-setup.

[![NPM](https://nodei.co/npm/quik.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/quik)

- [https://npmdoc.github.io/node-npmdoc-quik/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-quik/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-quik/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-quik/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-quik/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-quik/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "quik",
    "description": "A quick way to prototype apps with React and Babel with zero-setup.",
    "keywords": [
        "react",
        "babel",
        "webpack",
        "build",
        "bundle",
        "package",
        "prototype",
        "quik"
    ],
    "main": "dist/index.js",
    "scripts": {
        "build": "del dist/ && babel -sd dist/ src/",
        "coverage": "nyc report --reporter=text-lcov | coveralls",
        "lint": "eslint . --quiet",
        "test": "nyc ava",
        "flow": "flow",
        "prepublish": "npm run build",
        "semantic-release": "semantic-release pre && npm publish && semantic-release post"
    },
    "bin": {
        "quik": "bin/quik.js"
    },
    "repository": {
        "type": "git",
        "url": "https://github.com/satya164/quik.git"
    },
    "author": "Satyajit Sahoo <satyajit.happy@gmail.com> (https://github.com/satya164/)",
    "license": "MIT",
    "dependencies": {
        "autoprefixer": "^6.6.1",
        "babel-core": "^6.22.1",
        "babel-loader": "^6.2.10",
        "babel-plugin-transform-react-constant-elements": "^6.22.0",
        "babel-plugin-transform-react-inline-elements": "^6.22.0",
        "babel-plugin-transform-runtime": "^6.22.0",
        "babel-polyfill": "^6.22.0",
        "babel-preset-es2015": "^6.22.0",
        "babel-preset-react": "^6.22.0",
        "babel-preset-react-hmre": "^1.1.1",
        "babel-preset-stage-1": "^6.22.0",
        "babel-runtime": "^6.22.0",
        "chalk": "^1.1.3",
        "cheerio": "^0.22.0",
        "command-exists": "^1.0.2",
        "css-loader": "^0.26.1",
        "file-loader": "^0.9.0",
        "glob-expand": "^0.2.1",
        "koa": "^1.2.4",
        "koa-compose": "^2.5.1",
        "koa-logger": "^1.3.1",
        "koa-static": "^2.0.0",
        "koa-webpack-dev-middleware": "^1.3.0",
        "koa-webpack-hot-middleware": "^1.0.3",
        "less": "^2.7.2",
        "less-loader": "^2.2.3",
        "lodash": "^4.17.4",
        "memory-fs": "^0.4.1",
        "ncp": "^2.0.0",
        "node-sass": "^4.3.0",
        "opn": "^4.0.2",
        "postcss-loader": "^1.2.2",
        "react": "^15.4.2",
        "react-dom": "^15.4.2",
        "sass-loader": "^4.1.1",
        "style-loader": "^0.13.1",
        "url-loader": "^0.5.7",
        "webpack": "^2.2.0",
        "yargs": "^6.6.0"
    },
    "devDependencies": {
        "ava": "^0.17.0",
        "babel-cli": "^6.22.2",
        "babel-eslint": "^7.1.1",
        "babel-plugin-transform-flow-strip-types": "^6.22.0",
        "coveralls": "^2.11.15",
        "cz-conventional-changelog": "^1.2.0",
        "del": "^2.2.2",
        "del-cli": "^0.2.1",
        "eslint": "^3.13.1",
        "eslint-plugin-ava": "^4.0.1",
        "eslint-plugin-babel": "^4.0.1",
        "eslint-plugin-import": "^2.2.0",
        "eventsource": "^0.2.1",
        "flow-bin": "^0.38.0",
        "mkdirp": "^0.5.1",
        "nyc": "^10.1.2",
        "semantic-release": "^6.3.2"
    },
    "ava": {
        "babel": "inherit",
        "files": [
            "**/*.test.js"
        ]
    },
    "config": {
        "commitizen": {
            "path": "./node_modules/cz-conventional-changelog"
        }
    },
    "version": "0.11.2"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
