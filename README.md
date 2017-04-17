# api documentation for  [paper (v0.10.3)](http://paperjs.org)  [![npm package](https://img.shields.io/npm/v/npmdoc-paper.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-paper) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-paper.svg)](https://travis-ci.org/npmdoc/node-npmdoc-paper)
#### The Swiss Army Knife of Vector Graphics Scripting

[![NPM](https://nodei.co/npm/paper.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/paper)

- [https://npmdoc.github.io/node-npmdoc-paper/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-paper/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-paper/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-paper/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-paper/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-paper/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "browser": {
        "canvas": false,
        "jsdom": false,
        "jsdom/lib/jsdom/living/generated/utils": false,
        "source-map-support": false,
        "./dist/node/window.js": false,
        "./dist/node/extend.js": false
    },
    "bugs": {
        "url": "https://github.com/paperjs/paper.js/issues"
    },
    "contributors": [
        {
            "name": "Jürg Lehni",
            "url": "http://scratchdisk.com"
        },
        {
            "name": "Jonathan Puckey",
            "url": "http://studiomoniker.com"
        }
    ],
    "dependencies": {
        "canvas": "^1.3.5",
        "jsdom": "^9.4.0",
        "source-map-support": "^0.4.0"
    },
    "description": "The Swiss Army Knife of Vector Graphics Scripting",
    "devDependencies": {
        "acorn": "~0.5.0",
        "del": "^2.2.1",
        "gulp": "^3.9.1",
        "gulp-bump": "^2.2.0",
        "gulp-cached": "^1.1.0",
        "gulp-git-streamed": "^1.8.0",
        "gulp-jshint": "^2.0.0",
        "gulp-prepro": "^2.4.0",
        "gulp-qunits": "^2.1.1",
        "gulp-rename": "^1.2.2",
        "gulp-shell": "^0.5.2",
        "gulp-symlink": "^2.1.4",
        "gulp-uglify": "^1.5.4",
        "gulp-uncomment": "^0.3.0",
        "gulp-util": "^3.0.7",
        "gulp-webserver": "^0.9.1",
        "gulp-whitespace": "^0.1.0",
        "gulp-zip": "^3.2.0",
        "husky": "^0.11.4",
        "jshint": "^2.9.2",
        "jshint-summary": "^0.4.0",
        "merge-stream": "^1.0.0",
        "minimist": "^1.2.0",
        "prepro": "^2.4.0",
        "qunitjs": "^1.23.0",
        "require-dir": "^0.3.0",
        "resemblejs": "^2.2.1",
        "run-sequence": "^1.2.2",
        "stats.js": "0.16.0",
        "straps": "^2.1.0"
    },
    "directories": {},
    "dist": {
        "shasum": "d0578c5c218411b6d3f42a0fcb50b11a8511835e",
        "tarball": "https://registry.npmjs.org/paper/-/paper-0.10.3.tgz"
    },
    "engines": {
        "node": ">=4.0.0 <8.0.0"
    },
    "files": [
        "AUTHORS.md",
        "CHANGELOG.md",
        "dist/",
        "examples/",
        "LICENSE.txt",
        "README.md"
    ],
    "gitHead": "3379a81b852bd6ec9446e628c212105ebacf21f0",
    "homepage": "http://paperjs.org",
    "keywords": [
        "vector",
        "graphic",
        "graphics",
        "2d",
        "geometry",
        "bezier",
        "curve",
        "curves",
        "path",
        "paths",
        "canvas",
        "svg",
        "paper",
        "paper.js"
    ],
    "license": "MIT",
    "main": "dist/paper-full.js",
    "maintainers": [
        {
            "name": "lehni"
        },
        {
            "name": "puckey"
        }
    ],
    "name": "paper",
    "optionalDependencies": {
        "canvas": "^1.3.5"
    },
    "repository": {
        "type": "git",
        "url": "git://github.com/paperjs/paper.js.git"
    },
    "scripts": {
        "build": "gulp build",
        "dist": "gulp dist",
        "docs": "gulp docs",
        "jshint": "gulp jshint",
        "load": "gulp load",
        "precommit": "gulp jshint --branch develop",
        "prepush": "gulp test --branch develop",
        "test": "gulp test",
        "zip": "gulp zip"
    },
    "version": "0.10.3"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
