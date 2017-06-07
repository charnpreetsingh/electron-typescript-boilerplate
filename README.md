# Electron-typescript-boilerplate
A starting point for electron apps using typescript.

## Usage
To run:
``npm run build:all``

To compile Typescript:
``npm run build``

## Other options:
[electron-prebuilt-compile](https://github.com/electron-userland/electron-prebuilt-compile)
makes it easy to incorporate Typescript and other languages in your electron
project. Right now this repository uses `electron` instead, because the
associated typings file are already included in the npm package. In the future,
if electron-prebuilt-compile includes a typings file, this repository will
update to use it instead.
