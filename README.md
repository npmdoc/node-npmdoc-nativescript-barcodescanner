# npmdoc-nativescript-barcodescanner

#### api documentation for  [nativescript-barcodescanner (v2.5.0)](https://github.com/eddyverbruggen/nativescript-barcodescanner)  [![npm package](https://img.shields.io/npm/v/npmdoc-nativescript-barcodescanner.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-nativescript-barcodescanner) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-nativescript-barcodescanner.svg)](https://travis-ci.org/npmdoc/node-npmdoc-nativescript-barcodescanner)

#### Scan QR/barcodes with a {N} app.

[![NPM](https://nodei.co/npm/nativescript-barcodescanner.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/nativescript-barcodescanner)

- [https://npmdoc.github.io/node-npmdoc-nativescript-barcodescanner/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-nativescript-barcodescanner/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-nativescript-barcodescanner/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-nativescript-barcodescanner/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-nativescript-barcodescanner/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-nativescript-barcodescanner/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "nativescript-barcodescanner",
    "version": "2.5.0",
    "description": "Scan QR/barcodes with a {N} app.",
    "main": "barcodescanner",
    "nativescript": {
        "platforms": {
            "android": "2.3.0",
            "ios": "2.3.0"
        }
    },
    "scripts": {
        "build": "tsc",
        "demo.ios": "npm run preparedemo && cd demo && tns emulate ios --device \"iPhone 7\"",
        "demo.ios.device": "npm run preparedemo && cd demo && tns platform remove ios && tns platform add ios && tns run ios",
        "demo.android": "npm run preparedemo && cd demo && tns run android",
        "preparedemo": "npm run build && cd demo && tns plugin remove nativescript-barcodescanner && tns plugin add .. && tns install",
        "prepublish": "npm run build && npm run tslint",
        "setup": "npm i && cd demo && npm i && cd .. && npm run build && cd demo && tns plugin add .. && cd ..",
        "test": "npm run tslint && npm run tslint.demo && cd demo && tns build ios && tns build android",
        "tslint": "tslint *.ts",
        "tslint.demo": "tslint demo/app/*.ts"
    },
    "repository": {
        "type": "git",
        "url": "git+https://github.com/eddyverbruggen/nativescript-barcodescanner.git"
    },
    "keywords": [
        "ecosystem:nativescript",
        "NativeScript",
        "Barcode",
        "Barcode Scanner",
        "Bulk",
        "Bulk Scan",
        "Continuous",
        "Flashlight",
        "Torch",
        "Torch",
        "Aztec",
        "Codabar",
        "Code39",
        "Code93",
        "Code128",
        "Data Matrix",
        "EAN8",
        "EAN13",
        "ITF",
        "PDF417",
        "QR",
        "RSS14",
        "UPCA",
        "UPCE"
    ],
    "author": "Eddy Verbruggen <eddyverbruggen@gmail.com>",
    "license": {
        "type": "MIT",
        "url": "https://github.com/eddyverbruggen/nativescript-barcodescanner/blob/master/LICENSE"
    },
    "bugs": {
        "url": "https://github.com/eddyverbruggen/nativescript-barcodescanner/issues"
    },
    "homepage": "https://github.com/eddyverbruggen/nativescript-barcodescanner",
    "devDependencies": {
        "tns-core-modules": "^2.5.1",
        "tns-platform-declarations": "^2.5.0",
        "typescript": "~2.1.0",
        "tslint": "^5.0.0"
    },
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
