# npmtest-fine-uploader

#### basic test coverage for  [fine-uploader (v5.14.2)](https://github.com/FineUploader/fine-uploader#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-fine-uploader.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-fine-uploader) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-fine-uploader.svg)](https://travis-ci.org/npmtest/node-npmtest-fine-uploader)

#### Multiple file upload plugin with progress-bar, drag-and-drop, direct-to-S3 & Azure uploading, client-side image scaling, preview generation, form support, chunking, auto-resume, and tons of other features.

[![NPM](https://nodei.co/npm/fine-uploader.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/fine-uploader)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-fine-uploader/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-fine-uploader/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-fine-uploader/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-fine-uploader/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-fine-uploader/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-fine-uploader/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-fine-uploader/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-fine-uploader/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-fine-uploader/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-fine-uploader/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-fine-uploader/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-fine-uploader/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-fine-uploader/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-fine-uploader/build/test-report.html](https://npmtest.github.io/node-npmtest-fine-uploader/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-fine-uploader/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-fine-uploader/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-fine-uploader/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-fine-uploader/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-fine-uploader/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-fine-uploader/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-fine-uploader/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-fine-uploader/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Widen Enterprises, Inc."
    },
    "bugs": {
        "url": "https://github.com/FineUploader/fine-uploader/issues"
    },
    "contributors": [
        {
            "name": "Ray Nicholus",
            "url": "http://raynicholus.com"
        }
    ],
    "dependencies": {},
    "description": "Multiple file upload plugin with progress-bar, drag-and-drop, direct-to-S3 & Azure uploading, client-side image scaling, preview generation, form support, chunking, auto-resume, and tons of other features.",
    "devDependencies": {
        "clean-css-cli": "4.0.8",
        "jscs": "3.0.7",
        "jshint": "2.9.4",
        "karma": "1.5.0",
        "karma-firefox-launcher": "1.0.0",
        "karma-mocha": "1.3.0",
        "karma-spec-reporter": "0.0.30",
        "mocha": "3.2.0",
        "node-static": "0.7.9",
        "pica": "latest",
        "uglify-js": "2.7.5"
    },
    "directories": {},
    "dist": {
        "shasum": "2bd3a6fd9ce2c086e968caf093fc4f4064740e16",
        "tarball": "https://registry.npmjs.org/fine-uploader/-/fine-uploader-5.14.2.tgz"
    },
    "homepage": "https://github.com/FineUploader/fine-uploader#readme",
    "keywords": [
        "amazon",
        "api",
        "aws",
        "azure",
        "chunk",
        "chunking",
        "cross-domain",
        "cross-site",
        "drag",
        "drop",
        "file",
        "file-input",
        "file-uploader",
        "input",
        "jquery",
        "jquery-plugin",
        "multiple",
        "preview",
        "progress",
        "resume",
        "s3",
        "selection",
        "upload",
        "widget"
    ],
    "license": "MIT",
    "main": "lib/traditional.js",
    "maintainers": [
        {
            "name": "rnicholus"
        }
    ],
    "name": "fine-uploader",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/FineUploader/fine-uploader.git"
    },
    "scripts": {
        "build": "make clean; make build-all-ui",
        "lint": "make lint",
        "start": "make start-local-dev",
        "test": "make lint && make test"
    },
    "title": "Fine Uploader",
    "types": "typescript/fine-uploader.d.ts",
    "version": "5.14.2",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
