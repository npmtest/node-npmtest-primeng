# npmtest-primeng

#### basic test coverage for  primeng (v4.0.0-rc.3)  [![npm package](https://img.shields.io/npm/v/npmtest-primeng.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-primeng) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-primeng.svg)](https://travis-ci.org/npmtest/node-npmtest-primeng)

####

[![NPM](https://nodei.co/npm/primeng.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/primeng)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-primeng/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-primeng/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-primeng/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-primeng/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-primeng/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-primeng/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-primeng/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-primeng/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-primeng/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-primeng/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-primeng/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-primeng/build/test-report.html](https://npmtest.github.io/node-npmtest-primeng/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-primeng/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-primeng/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-primeng/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-primeng/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-primeng/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-primeng/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-primeng/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-primeng/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "primeng",
    "version": "4.0.0-rc.3",
    "scripts": {
        "tsc": "tsc",
        "tsc:w": "tsc -w",
        "webpack": "webpack",
        "webpack:w": "webpack -w",
        "webpack-dev-server": "webpack-dev-server --inline",
        "build-prod": "webpack --config config/webpack.prod.js",
        "build-dev": "webpack --config config/webpack.dev.js",
        "start": "npm run webpack-dev-server"
    },
    "repository": {
        "type": "git",
        "url": "https://github.com/primefaces/primeng.git"
    },
    "license": "MIT",
    "devDependencies": {
        "@types/node": "^7.0.5",
        "del": "^2.2.0",
        "gulp": "^3.9.1",
        "gulp-concat": "^2.6.0",
        "gulp-flatten": "^0.2.0",
        "gulp-rename": "^1.2.2",
        "gulp-uglify": "^1.5.3",
        "gulp-uglifycss": "^1.0.6",
        "ts-loader": "^0.9.5",
        "typescript": "^2.1.6",
        "html-webpack-plugin": "^2.16.1",
        "webpack": "2.2.1",
        "webpack-dev-server": "2.4.1",
        "webpack-merge": "^3.0.0"
    },
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
