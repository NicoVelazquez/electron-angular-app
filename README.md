# ElectronAngularApp

## Installation

1) 'npm install electron --save-dev'
2) Add electron 'main.js' on root directory
3) Change angular 'index.html' to contain '<base href="./">'
4) Change 'package.json' to contain '"main": "main.js"' on root and inside scripts; '"electron: "ng build && electron ."'

## Run

'npm run electron'
