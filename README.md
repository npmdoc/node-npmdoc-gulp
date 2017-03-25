# api documentation for  [gulp (v3.9.1)](http://gulpjs.com)  [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-gulp.svg)](https://travis-ci.org/npmdoc/node-npmdoc-gulp)
#### The streaming build system

[![NPM](https://nodei.co/npm/gulp.png?downloads=true)](https://www.npmjs.com/package/gulp)

[![apidoc](https://npmdoc.github.io/node-npmdoc-gulp/build/screen-capture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-gulp_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-gulp/build..beta..travis-ci.org/apidoc.html)

![package-listing](https://npmdoc.github.io/node-npmdoc-gulp/build/screen-capture.npmPackageListing.svg)



# package.json

```json

{
    "author": {
        "name": "Fractal",
        "email": "contact@wearefractal.com",
        "url": "http://wearefractal.com/"
    },
    "bin": {
        "gulp": "./bin/gulp.js"
    },
    "bugs": {
        "url": "https://github.com/gulpjs/gulp/issues"
    },
    "dependencies": {
        "archy": "^1.0.0",
        "chalk": "^1.0.0",
        "deprecated": "^0.0.1",
        "gulp-util": "^3.0.0",
        "interpret": "^1.0.0",
        "liftoff": "^2.1.0",
        "minimist": "^1.1.0",
        "orchestrator": "^0.3.0",
        "pretty-hrtime": "^1.0.0",
        "semver": "^4.1.0",
        "tildify": "^1.0.0",
        "v8flags": "^2.0.2",
        "vinyl-fs": "^0.3.0"
    },
    "description": "The streaming build system",
    "devDependencies": {
        "coveralls": "^2.7.0",
        "eslint": "^1.7.3",
        "eslint-config-gulp": "^2.0.0",
        "graceful-fs": "^3.0.0",
        "istanbul": "^0.3.0",
        "jscs": "^2.3.5",
        "jscs-preset-gulp": "^1.0.0",
        "marked-man": "^0.1.3",
        "mkdirp": "^0.5.0",
        "mocha": "^2.0.1",
        "mocha-lcov-reporter": "^0.0.1",
        "q": "^1.0.0",
        "rimraf": "^2.2.5",
        "should": "^5.0.1"
    },
    "directories": {},
    "dist": {
        "shasum": "571ce45928dd40af6514fc4011866016c13845b4",
        "tarball": "https://registry.npmjs.org/gulp/-/gulp-3.9.1.tgz"
    },
    "engines": {
        "node": ">= 0.9"
    },
    "files": [
        "index.js",
        "lib",
        "bin",
        "completion",
        "gulp.1"
    ],
    "gitHead": "9c14e3a13a73a32e424f144d62566671b2fcdbed",
    "homepage": "http://gulpjs.com",
    "license": "MIT",
    "maintainers": [
        {
            "name": "fractal",
            "email": "contact@wearefractal.com"
        },
        {
            "name": "phated",
            "email": "blaine@iceddev.com"
        }
    ],
    "man": [
        "gulp.1"
    ],
    "name": "gulp",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git+https://github.com/gulpjs/gulp.git"
    },
    "scripts": {
        "coveralls": "istanbul cover _mocha --report lcovonly -- -R spec && cat ./coverage/lcov.info | coveralls && rm -rf ./coverage",
        "lint": "eslint . && jscs *.js bin/ lib/ test/",
        "prepublish": "marked-man --name gulp docs/CLI.md > gulp.1",
        "pretest": "npm run lint",
        "test": "mocha --reporter spec"
    },
    "tags": [
        "build",
        "stream",
        "system",
        "make",
        "tool",
        "asset",
        "pipeline"
    ],
    "version": "3.9.1"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module gulp](#apidoc.module.gulp)
1.  boolean <span class="apidocSignatureSpan">gulp.</span>isRunning
1.  number <span class="apidocSignatureSpan">gulp.</span>_eventsCount
1.  object <span class="apidocSignatureSpan">gulp.</span>_events
1.  object <span class="apidocSignatureSpan">gulp.</span>domain
1.  object <span class="apidocSignatureSpan">gulp.</span>seq
1.  object <span class="apidocSignatureSpan">gulp.</span>tasks



# <a name="apidoc.module.gulp"></a>[module gulp](#apidoc.module.gulp)



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
