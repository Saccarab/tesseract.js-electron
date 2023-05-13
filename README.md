Tesseract.js Electron
=====================

An example to use tesseract.js in electron.

`index.html` downloads Tesseract.js-core and the language data (`.traineddata`) files remotely from a CDN at runtime (the default behavior of Tesseract.js).

`index-offline.html` can be run fully offline, using local copies of Tesseract.js-core and `eng.traineddata`.  To switch to this version, replace `index.html` with `index-offline.html` in `main.js`. 

## Installation

```bash
$ npm install
```

## Run

```bash
$ npm start
```
